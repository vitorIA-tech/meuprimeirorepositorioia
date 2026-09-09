# 📘 Guia Completo e Didático de Markdown

Bem-vindo ao guia definitivo de Markdown! Este arquivo foi criado para demonstrar **todas as principais funcionalidades** dessa linguagem de marcação leve, muito utilizada para documentação de software (como o famoso `README.md`).

Abra a visualização (Preview) do seu editor de código (como o VS Code) para ver como este texto é renderizado!

---

## 1. Títulos (Headers)

Você pode criar títulos usando a cerquilha (`#`). Quanto mais cerquilhas, menor o título.

# Título de Nível 1
## Título de Nível 2
### Título de Nível 3
#### Título de Nível 4
##### Título de Nível 5
###### Título de Nível 6

---

## 2. Formatação de Texto

Você pode dar ênfase a palavras ou frases de forma bem simples:

* **Negrito:** Use dois asteriscos ou dois underlines. Exemplo: **Texto em negrito** ou __Outro negrito__.
* *Itálico:* Use um asterisco ou um underline. Exemplo: *Texto em itálico* ou _Outro itálico_.
* ***Negrito e Itálico:*** Use três asteriscos. Exemplo: ***Texto muito importante***.
* ~~Tachado:~~ Use dois tis (tildes). Exemplo: ~~Texto riscado~~.

---

## 3. Listas

As listas ajudam a organizar informações.

### Listas Não Ordenadas (Marcadores)
Você pode usar `-`, `*` ou `+`.

* Pão
* Leite
  * Leite desnatado
  * Leite integral (sub-item com recuo de espaços)
- Ovos
+ Manteiga

### Listas Ordenadas (Números)
1. Acordar
2. Tomar café
3. Codar
   1. Revisar PRs (sub-item)
   2. Escrever testes

### Listas de Tarefas (Task Lists)
Ótimas para checklists de PRs ou issues:
- [x] Tarefa concluída
- [ ] Tarefa pendente
- [ ] Outra tarefa pendente

---

## 4. Links

Adicionar links é fundamental para referenciar outros documentos.

**Link direto:** [Google](https://www.google.com)
**Link com título (passe o mouse):** [GitHub](https://github.com "Site do GitHub")

Também podemos usar referências, o que deixa o texto mais limpo:
Aqui está um link para o [StackOverflow][1].

[1]: https://stackoverflow.com "StackOverflow"

---

## 5. Imagens

Muito parecido com os links, mas com um ponto de exclamação no começo.

![Logo do Markdown](https://upload.wikimedia.org/wikipedia/commons/thumb/4/48/Markdown-mark.svg/200px-Markdown-mark.svg.png "Logo do Markdown")

---

## 6. Citações (Blockquotes)

Usadas para destacar citações de outras pessoas ou notas importantes.

> "A simplicidade é a sofisticação máxima."
> — Leonardo da Vinci

Citações também podem ser aninhadas:
> Citação principal
>> Citação dentro da citação

---

## 7. Código

Como pessoa desenvolvedora, esta é a funcionalidade que você mais vai usar!

**Código em linha (Inline):** Use crases simples. Para instalar as dependências, rode `npm install`.

**Bloco de Código (Code Block):** Use três crases para criar um bloco de código. Você pode especificar a linguagem logo após as primeiras crases para habilitar o realce de sintaxe (Syntax Highlighting).

```python
# Exemplo em Python
def saudacao(nome):
    print(f"Olá, {nome}! Bem-vindo ao time.")

saudacao("Estagiário")
```

```javascript
// Exemplo em JavaScript
const somar = (a, b) => a + b;
console.log(somar(2, 2)); // 4
```

---

## 8. Tabelas

As tabelas usam barras verticais `|` e hifens `-`. Você pode alinhar as colunas usando dois pontos `:`.

| Alinhado à Esquerda | Centralizado | Alinhado à Direita |
| :--- | :---: | ---: |
| Linha 1 | Dado A | $10.00 |
| Linha 2 | Dado B | $20.00 |
| Linha 3 | Dado C | $30.00 |

---

## 9. Linhas Horizontais (Divisores)

Use três hifens `---`, asteriscos `***` ou underlines `___` para criar uma linha que separa seções.

---

## 10. Escapando Caracteres

Se você quiser mostrar um caractere que o Markdown normalmente interpretaria (como um asterisco ou uma crase), use a barra invertida `\` antes dele.

\*Isso não ficará em itálico\*
\# Isso não é um título

---

## 11. HTML Embutido

O Markdown suporta HTML nativamente! Se algo não puder ser feito com Markdown (como centralizar um texto ou mudar a cor), você pode usar HTML.

<div align="center">
  <p style="color: blue;"><strong>Este texto foi centralizado e colorido usando HTML!</strong></p>
</div>

<details>
  <summary>Clique aqui para um Spoiler!</summary>
  <p>Você descobriu o segredo do elemento "details" do HTML dentro do Markdown!</p>
</details>

---
*Fim do Guia! Pratique bastante escrevendo seus próprios READMEs.*

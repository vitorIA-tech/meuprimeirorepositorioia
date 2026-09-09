**Comandos Básicos e Variáveis**

```python
nome = "Maria" # String (Texto)
idade = 25 # Integer (Número Inteiro)
altura = 1.68 # Float (Número Decimal)
is_dev = True # Boolean (Verdadeiro ou Falso)

```

**Exibição e Entrada de Dados**

```python
print("Olá, mundo!")
print(f"Meu nome é {nome} e tenho {idade} anos.") # F-String para formatar variáveis
cidade = input("Digite a sua cidade: ") # Receber dados do usuário

```

**Operadores Matemáticos**

```python
soma = 10 + 5
divisao = 10 / 3 # Retorna float: 3.333...
divisao_inteira = 10 // 3 # Retorna int: 3
resto = 10 % 3 # Retorna 1 (Módulo)

```

**Estruturas Condicionais**

```python
nota = 8.5
if nota >= 7:
    print("Aprovado!")
elif nota >= 5:
    print("Recuperação!")
else:
    print("Reprovado!")

```

**Laços de Repetição (Loops)**

```python
# For Loop (para percorrer faixas ou listas)
for i in range(5):
    print(i)

# While Loop (enquanto a condição for verdadeira)
contador = 0
while contador < 3:
    print(contador)
    contador += 1

```

**Estruturas de Dados**

```python
# Listas (ordenadas e mutáveis)
devs = ["Ana", "Bruno", "Carlos"]
devs.append("Daniela") # Adiciona ao final

# Dicionários (chave e valor)
usuario = {"nome": "João", "cargo": "Estagiário"}
print(usuario["cargo"])

```

**Funções**

```python
def saudar(nome):
    return f"Olá, {nome}! Bom trabalho hoje."
print(saudar("Equipe"))

```

**Manipulação de Arquivos**

```python
# O 'with' garante que o arquivo seja fechado automaticamente
with open("log.txt", "w", encoding="utf-8") as arquivo:
    arquivo.write("Registro salvo com sucesso.")

```

**Passo a passo no Git para subir a lista para a branch main:**

1. Volte para a branch principal local:
`git checkout main`
2. Garanta que a sua branch principal está atualizada com a nuvem:
`git pull origin main`
3. Mescle as alterações da sua branch de trabalho para dentro da main:
`git merge feature/pesquisapython`
4. Envie o código unificado para o repositório remoto:
`git push origin main`

A diferença fundamental está em o que o sistema faz versus como ele se comporta.

Requisitos Funcionais (RF): Definem os recursos, serviços e ações diretas que o usuário ou o sistema pode executar. É o comportamento visível e operacional do software.

Requisitos Não Funcionais (RNF): Definem critérios de qualidade, restrições e padrões técnicos que o sistema deve atender para operar bem (desempenho, segurança, usabilidade, disponibilidade).

Requisitos Funcionais (O que o app faz)

Busca e listagem de restaurantes: O usuário pode pesquisar estabelecimentos por categoria (ex.: "pizza", "japonesa") e aplicar filtros por distância e taxa de entrega.

Gerenciamento de carrinho e checkout: O cliente consegue adicionar ou remover itens, selecionar opções de acompanhamento e finalizar o pedido escolhendo a forma de pagamento (cartão, Pix).

Rastreamento em tempo real: O sistema exibe o status atual do pedido (confirmado, em preparo, a caminho) e atualiza a localização do entregador no mapa.

Requisitos Não Funcionais (Como o app se comporta)

Desempenho e tempo de resposta: A tela de checkout e processamento de pagamento deve responder em menos de 2 segundos sob condições normais de rede.

Segurança e conformidade de dados: Todos os dados de cartões de crédito devem ser tokenizados e as comunicações criptografadas via TLS 1.3, em conformidade com as normas PCI-DSS e LGPD.

Disponibilidade e escalabilidade: O sistema deve manter 99,9% de uptime, suportando picos de tráfego de até 50.000 requisições simultâneas durante horários de pico (como noites de fim de semana) sem degradação do serviço.

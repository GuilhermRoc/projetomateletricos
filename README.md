# AutoHome · Luz Automática

Projeto acadêmico de **Materiais Elétricos** do grupo **Newtons**.

Um sistema de iluminação com Arduino que acende sozinho quando escurece e apaga quando a luz natural volta. É o primeiro módulo do AutoHome, uma proposta de automação residencial de baixo custo.

## Como funciona

1. Um módulo sensor de luz (LDR) mede a claridade do ambiente.
2. O Arduino Uno lê o sensor e confirma a leitura por 1 segundo, para evitar que a luz pisque.
3. Quando escurece, o Arduino aciona um módulo relé e acende a lâmpada (no protótipo, um LED).
4. Quando clareia, tudo desliga sozinho.

## Componentes

| Componente | Ligação |
|---|---|
| Módulo sensor de luz (LDR + LM393) | DO → A0 |
| Módulo relé 5V | IN → D6 |
| LED + resistor 330 Ω | D9 |
| Alimentação | 5V e GND nos trilhos do protoboard |

## Site

- `index.html`: página inicial
- `proposta.html`: proposta completa do projeto
- `apresentacao.html`: slides da apresentação (também em `apresentacao.pdf`)
- `integrantes.html`: integrantes do grupo

Feito com HTML e CSS, sem dependências. Para ver localmente, abra o `index.html` no navegador.

## Integrantes

- Guilherme da Rocha Oliveira
- Rafael Moises de Oliveira
- Giovani Marcelino dos Santos
- Mateus Mariano Lack de Brito
- Caua Fernando de Souza Silva

🃏 Batalha de Cartas no Super Trunfo — Projeto em Linguagem C
📌 Descrição
Este projeto simula uma batalha entre duas cartas de cidades no estilo do jogo Super Trunfo, utilizando a linguagem C. Cada carta possui atributos como estado, código, nome da cidade, população, área, PIB, pontos turísticos, além de dois atributos calculados: densidade populacional e PIB per capita.

Neste nível mestre, introduzimos o cálculo de um Super Poder para cada carta, que envolve uma combinação estratégica de atributos. O programa compara todos os atributos numéricos entre as duas cartas e determina o vencedor de cada comparação.

🚀 Funcionalidades
Cadastro de duas cartas com dados completos.

Cálculo da densidade populacional e do PIB per capita.

Cálculo do Super Poder com base nos seguintes atributos:

População

Área

PIB

Pontos turísticos

PIB per capita

Inverso da densidade populacional (quanto menor a densidade, maior o poder).

Comparação entre as cartas em cada atributo.

Exibição dos resultados da batalha carta a carta.

🧠 Lógica do Super Poder
A fórmula usada para o cálculo do Super Poder de cada carta é:

markdown
Copiar
Editar
SuperPoder = população 
           + área 
           + PIB (em bilhões) 
           + pontos turísticos 
           + PIB per capita 
           + (1 / densidade populacional)
Este cálculo utiliza conversão de tipos para manter a precisão nos resultados.

🛠️ Tecnologias Utilizadas
Linguagem C

Compilador GCC

IDEs como VSCode ou Code::Blocks (opcional)

🗃️ Estrutura do Projeto
cpp
Copiar
Editar
📁 super_trunfo/
├── super_trunfo.c   // Código-fonte principal
├── README.md        // (Opcional) Documentação
📸 Exemplo de Saída
bash
Copiar
Editar
Comparação de Cartas:

População: Carta 1 venceu (1)
Área: Carta 2 venceu (0)
PIB: Carta 2 venceu (0)
Pontos Turísticos: Carta 1 venceu (1)
Densidade Populacional: Carta 1 venceu (1)
PIB per Capita: Carta 2 venceu (0)
Super Poder: Carta 1 venceu (1)
🧪 Como Executar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/seu-usuario/super-trunfo.git
cd super-trunfo
Compile o código:

bash
Copiar
Editar
gcc super_trunfo.c -o super_trunfo
Execute:

bash
Copiar
Editar
./super_trunfo
📋 Requisitos
Sistema com terminal bash (Linux/macOS) ou CMD/PowerShell (Windows)

Compilador C (como GCC ou MinGW)

👨‍💻 Autor
Gabriel Pimenta
Desenvolvedor Front-End | Estudante de ADS
🔗 GitHub

🏁 Status
✅ Projeto finalizado e pronto para entrega — Nível Mestre do Desafio Super Trunfo.

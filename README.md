# 🃏 Super Trunfo de Cidades

Batalha de cartas no estilo Super Trunfo, implementada em C.  
Cadastro, cálculo de densidade e PIB per capita, super poder e comparação de duas cartas.

---


## 📖 Sobre

Este projeto simula uma batalha de cartas entre duas cidades, com atributos como:

- População (unsigned long int)  
- Área (float)  
- PIB em bilhões (float)  
- Pontos turísticos (int)  
- Densidade populacional (float, calculada)  
- PIB per capita (float, calculado)  
- Super Poder (float, calculado)  

Ao final, o programa compara cada atributo e indica qual carta venceu.

---

## 🚀 Funcionalidades

- Leitura de dados de duas cartas via teclado.  
- Cálculo de:  
  - Densidade populacional (hab/km²)  
  - PIB per capita (reais)  
  - Super Poder, fórmula:  

    ```c
    superPoder = população 
               + área 
               + (PIB × 1e9) 
               + pontosTurísticos 
               + pibPerCapita 
               + (1 / densidadePopulacional)
    ```
- Exibição formatada de todos os valores.  
- Comparação de atributos e indicação do vencedor (1 = Carta 1, 0 = Carta 2).

---

## 🛠️ Tecnologias

- Linguagem C  
- Compilador GCC  
- Pode usar IDEs como VSCode, Code::Blocks ou terminal puro.

---

## 📂 Estrutura de Diretórios

super-trunfo-cidades/
├── super_trunfo.c # Código-fonte principal
└── README.md # Documentação (este arquivo


---

## 🖥️ Como Compilar e Rodar

Siga os passos abaixo para compilar e executar o programa no seu ambiente local.

### Pré-requisitos

- Ter o compilador GCC instalado (ou outro compilador C compatível)  
- Ter um terminal ou prompt de comando disponível

---

### Passo 1: Clonar o repositório

Se ainda não tem o código, clone o repositório com:

```bash
git clone https://github.com/SEU_USUARIO/super-trunfo-cidades.git
cd super-trunfo-cidades

### Passo 2: Compilar o código
Compile o arquivo super_trunfo.c usando o GCC:

bash
Copiar
Editar
gcc super_trunfo.c -o super_trunfo
Esse comando gera um executável chamado super_trunfo.

### Passo 3: Executar o programa
Para rodar o programa, digite no terminal:

No Linux/macOS:

bash
Copiar
Editar
./super_trunfo
No Windows (Prompt de Comando):

cmd
Copiar
Editar
super_trunfo.exe
Observações
O programa vai pedir que você informe os dados das duas cartas (cidades) via teclado.

Siga as instruções exibidas no terminal para inserir cada atributo.

Após o cadastro, o programa exibirá os cálculos e o resultado da comparação entre as cartas.



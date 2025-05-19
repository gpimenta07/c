# 🃏 Super Trunfo de Cidades

> Batalha de cartas no estilo Super Trunfo, implementada em C.  
> Cadastro, cálculo de densidade e PIB per capita, super poder e comparação de duas cartas.

---

## 📑 Sumário

- [Sobre](#sobre)  
- [Funcionalidades](#funcionalidades)  
- [Tecnologias](#tecnologias)  
- [Estrutura de Diretórios](#estrutura-de-diretórios)  
- [Como Compilar e Rodar](#como-compilar-e-roar)  
- [Exemplo de Uso](#exemplo-de-uso)  
- [Autor](#autor)  
- [Licença](#licença)  

---

## 📖 Sobre

Este projeto simula uma **batalha de cartas** entre duas cidades, com atributos como:

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

1. Leitura de dados de **duas cartas** via teclado.  
2. Cálculo de:
   - **Densidade populacional** (hab/km²)  
   - **PIB per capita** (reais)  
   - **Super Poder**, fórmula:  
     ```
     superPoder = população 
                + área 
                + (PIB × 1e9) 
                + pontosTurísticos 
                + pibPerCapita 
                + (1 / densidadePopulacional)
     ```
3. Exibição formatada de todos os valores.  
4. Comparação de atributos e indicação do vencedor (1 = Carta 1, 0 = Carta 2).

---

## 🛠️ Tecnologias

- Linguagem **C**  
- Compilador **GCC**  
- Pode usar IDEs como **VSCode**, **Code::Blocks** ou terminal puro.

---

## 📂 Estrutura de Diretórios

```bash
super-trunfo-cidades/
├── super_trunfo.c    # Código-fonte principal
└── README.md         # Documentação (este arquivo)
## 🖥️ Como Compilar e Rodar
Clone o repositório:

bash
Copiar
Editar
git clone https://github.com/SEU_USUARIO/super-trunfo-cidades.git
cd super-trunfo-cidades
Compile:

bash
Copiar
Editar
gcc super_trunfo.c -o super_trunfo
Execute:

bash
Copiar
Editar
./super_trunfo

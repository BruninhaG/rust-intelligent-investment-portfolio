# Carteira de Investimentos Inteligente com Rust 🦀

## 📌 Sobre o Projeto
Este projeto consiste no desenvolvimento de uma aplicação robusta e de alta performance para gerenciamento e análise de carteiras de investimentos. Utilizando a linguagem **Rust**, a solução foi desenhada para processar regras de negócio financeiras complexas com o máximo de eficiência, garantindo segurança de memória em tempo de compilação.

## ⚡ Por que Rust no Mercado Financeiro?
A escolha do Rust para este projeto baseia-se em três pilares fundamentais da linguagem que são críticos para sistemas financeiros:
* **Memory Safety:** Garantia de que não haverá vazamentos de memória ou ponteiros nulos (*null pointers*) sem a necessidade de um Garbage Collector pesado.
* **Performance:** Execução em nível de código nativo (próximo ao C/C++), ideal para cálculos de rentabilidade, rebalanceamento e análise de risco.
* **Fearless Concurrency:** Estruturas seguras para processar múltiplas operações simultâneas sem o risco de *data races*.

## 🛠️ Funcionalidades Implementadas
* **Modelagem de Ativos:** Estruturas (`structs`) e enumerações (`enums`) fortemente tipadas para representar ações, fundos e renda fixa.
* **Cálculo de Rentabilidade:** Algoritmos para consolidação de saldos, preço médio e rendimento histórico.
* **Regras de Rebalanceamento:** Lógica inteligente para sugerir aportes com base em metas percentuais estipuladas pelo usuário.
* **Validação de Dados:** Uso de padrões de correspondência (*Pattern Matching*) para tratamento seguro de fluxos e erros.

## 🧰 Conceitos de Rust Aplicados
* **Ownership & Borrowing:** Gerenciamento eficiente de recursos na memória Stack e Heap.
* **Structs e Traits:** Definição de contratos e comportamento de dados financeiros.
* **Error Handling:** Uso rigoroso dos tipos `Result` e `Option` para evitar que a aplicação quebre em produção.

## 🚀 Como Executar
1. Certifique-se de ter o Rust instalado (`rustc --version`).
2. Clone o repositório.
3. Compile e execute o projeto usando o Cargo:
   ```bash
   cargo run
   ```
   ---
   ## 👩‍💻 Autora
   Feito com 💛 por Bruna Guimarães

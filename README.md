# Teste Prático de Programação - Iniflex

Este repositório contém a resolução do teste prático técnico para o processo seletivo da empresa **Iniflex**. O projeto foi desenvolvido com o objetivo de demonstrar boas práticas de Orientação a Objetos, manipulação de coleções, formatação de dados e cálculos numéricos de alta precisão.

---

## 🛠️ Tecnologias e Conceitos Aplicados

- **Linguagem:** Java (JDK 17+)
- **Orientação a Objetos (POO):** Abstração, Herança e Encapsulamento.
- **Precisão Financeira:** Uso de `java.math.BigDecimal` para garantir exatidão em cálculos monetários e percentuais.
- **Manipulação de Datas:** Uso da API `java.time.LocalDate` e formatação com `DateTimeFormatter`.
- **Java Streams & Lambdas:** Processamento eficiente de coleções para filtragem, agrupamentos (`Map`), ordenação e agregações.

---

## 📌 Requisitos Atendidos

1. **Modelagem de Classes:** Criação da classe pai `Pessoa` e subclasse `Funcionario`.
2. **Inserção e Remoção:** População inicial dos dados e remoção condicional por nome.
3. **Formatação de Saída:**
   - Datas no padrão brasileiro (`dd/MM/yyyy`).
   - Valores monetários formatados com separador de milhar e vírgula decimal (`R$ 1.234,56`).
4. **Cálculos e Atualizações:**
   - Aplicação de reajuste salarial de 10%.
   - Cálculo do total geral dos salários.
   - Cálculo da quantidade de salários mínimos (base R$ 1.212,00) por funcionário.
5. **Consultas e Agrupamentos:**
   - Mapeamento dinâmico agrupando funcionários por função (`Map<String, List<Funcionario>>`).
   - Filtragem de aniversariantes específicos (meses 10 e 12).
   - Identificação e cálculo de idade do funcionário mais velho.
   - Ordenação alfabética dos registros.

---

## 🚀 Como Executar o Projeto

### Pré-requisitos
- **Java Development Kit (JDK)** versão 17 ou superior instalada.

### Passo a Passo

1. **Clonar o repositório:**
   ```js
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
   cd NOME_DO_REPOSITORIO
   ```
2. ***Compilar as classes:**
   ```js
       javac Pessoa.java Funcionario.java Principal.java
   ```

3. ***Executar a aplicação:**
   ```js
   java Principal
   ```

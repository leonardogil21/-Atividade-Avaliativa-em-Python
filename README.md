# Atividade Avaliativa — Lógica de Programação com Python 🐍

Este repositório contém a resolução de uma atividade prática focada em lógica de programação, utilizando estruturas de controle (condicionais), laços de repetição (loops) e manipulação de listas e dicionários em Python.

## 📋 Descrição dos Problemas

O projeto consiste em quatro questões que simulam cenários reais de análise de dados e automação de processos:

### 1. Classificação de Temperaturas
* **Problema:** Analisar uma lista de temperaturas semanais e classificá-las em categorias (Frio, Agradável, Quente).
* **Lógica:** Utiliza um laço `for` para percorrer a lista e uma estrutura `if-elif-else` para definir a categoria baseada em faixas de valores. Ao final, um dicionário é utilizado para contabilizar a frequência de cada categoria.

### 2. Sistema de Avaliação de Alunos
* **Problema:** Processar notas escolares para determinar o status acadêmico (Aprovado, Recuperação ou Reprovado) e calcular estatísticas de desempenho.
* **Lógica:** Aplica condicionais para gerar a lista de status e utiliza o método `.count()` e funções de agregação para calcular a quantidade de aprovados e o percentual de reprovados da turma.

### 3. Monitoramento de Consumo de Energia
* **Problema:** Analisar o consumo diário de energia (kWh), identificar picos de consumo e calcular métricas semanais.
* **Lógica:** Realiza a filtragem de dados (list comprehension/append) para identificar dias de alto consumo. Calcula o total e a média através das funções `sum()` e `len()`, disparando um alerta visual caso o limite de dias críticos seja atingido.

### 4. Simulação de Carrinho de Compras
* **Problema:** Aplicar descontos progressivos em uma lista de produtos e calcular a economia total do cliente.
* **Lógica:** Implementa uma regra de negócio onde a porcentagem do desconto varia conforme o valor unitário do item. O script calcula o preço final de cada produto e acumula o valor economizado em uma variável global.

---

## 🛠️ Tecnologias Utilizadas

* **Python 3**
* **Google Colab** (Ambiente de desenvolvimento)
* **Bibliotecas nativas:** Sem dependências externas.

---

## 🚀 Como Executar no Google Colab

Para visualizar e testar o código original, siga os passos abaixo:

1.  Acesse o [Google Colab](https://colab.research.google.com/).
2.  Clique em **Arquivo > Fazer upload de notebook**.
3.  Selecione o arquivo `Leonardo_Gil_p1.ipynb` presente neste repositório.
4.  Para rodar as células, clique no botão "Play" no canto esquerdo de cada bloco de código ou pressione `Ctrl + Enter`.

---

**Desenvolvido por:** [Leonardo Gil](https://github.com/SEU_USUARIO_AQUI)

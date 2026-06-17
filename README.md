# 📊 Sistema Inteligente de Recomendação de Investimentos: Machine Learning e Lógica Fuzzy

Este repositório contém todo o material referente ao Projeto Final Prático da disciplina de **Inteligência Artificial** (Universidade Católica de Brasília - UCB), sob a orientação do Prof. William Malvezzi.

O projeto aborda o **Tema 5 (Recomendação de Investimentos)** e propõe uma arquitetura híbrida de IA para mitigar a rigidez dos sistemas tradicionais de *Suitability* financeiro. A solução integra um modelo de classificação probabilística (Árvore de Decisão) com um motor de processamento de regras cognitivas (Lógica Fuzzy) para recomendar o percentual ideal de alocação em Renda Variável.

---

## 🛠️ Tecnologias e Bibliotecas Utilizadas

O projeto foi desenvolvido em **Python 3** e otimizado para execução no ambiente **Google Colab**. As principais bibliotecas utilizadas são:

* **Manipulação e Análise de Dados:** `pandas`, `numpy`
* **Visualização de Dados:** `matplotlib`, `seaborn`
* **Machine Learning:** `scikit-learn`
* **Lógica Fuzzy:** `scikit-fuzzy`

---

## 📁 Estrutura dos Arquivos

* `Tema05_Recomendação_de_Investimentos.ipynb`: O notebook principal contendo todo o pipeline do projeto (Geração de Dados, EDA, Treinamento ML, Sistema Fuzzy e Casos de Teste).
* `base_investidores.csv`: A base de dados sintética com 150 registros gerada pelo nosso próprio notebook durante a execução.
* `RelatórioFinal.pdf`: A documentação técnica contendo toda a fundamentação teórica, justificativas metodológicas e a conclusão do projeto.

---

## 🚀 Instruções Claras de Execução

Para garantir que o código funcione corretamente e reproduza os mesmos resultados descritos no relatório, siga o passo a passo abaixo:

1. **Acessar o Ambiente:**
   * Recomendamos o uso do **[Google Colab](https://colab.research.google.com/)** para evitar problemas de compatibilidade de ambiente local.
   * Faça o login com sua conta Google e clique em **Arquivo > Fazer upload de notebook**.
   * Selecione o arquivo `.ipynb` deste projeto.

2. **Instalação de Dependências:**
   * A biblioteca de Lógica Fuzzy não é nativa do Colab. A primeira célula de código do notebook contém o comando `!pip install scikit-fuzzy`. 
   * Execute essa primeira célula e aguarde a finalização da instalação.

3. **Execução do Pipeline:**
   * Após a instalação, você pode executar o projeto inteiro de uma só vez clicando no menu superior: **Executar tudo**.
   * **Geração de Dados:** Utilizamos uma semente fixa (`np.random.seed(42)`) para garantir a reprodutibilidade do experimento. Optamos pela escolha do valor "42" por ser uma convenção padrão na comunidade de ciência de dados (uma referência à cultura geek sobre a "resposta para a vida, o universo e tudo mais"), mas sua função técnica é assegurar que qualquer pessoa que execute o código obtenha exatamente os mesmos dados sintéticos. Isso é fundamental para permitir a validação consistente da acurácia e das simulações apresentadas no relatório. A base resultante é salva automaticamente como base_investidores.csv no armazenamento temporário do Colab. obterá exatamente os mesmos dados sintéticos, permitindo a verificação consistente da acurácia e das simulações apresentadas. A base resultante é salva automaticamente como `base_investidores.csv` no armazenamento temporário do Colab.
   * **Fluxo:** O código seguirá automaticamente pelo pré-processamento, plotagem dos gráficos exploratórios, treinamento da Árvore de Decisão, inicialização do Motor Fuzzy e impressão dos resultados dos "Casos de Teste" simulados no final.

4. **Visualização:**
   * Todos os gráficos (Matriz de Confusão, Topologia da Árvore e Gráfico de Defuzzificação por Centroide) serão exibidos diretamente logo abaixo de suas respectivas células de código.

---

## 👥 Equipe Desenvolvedora

* **[Nome do Aluno 1]** - Matrícula
* **[Nome do Aluno 2]** - Matrícula
* **[Nome do Aluno 3]** - Matrícula
*(Adicione ou remova conforme o tamanho do seu grupo)*

# Redes Neurais e Proteômica: Aplicando IA na Descoberta de Tratamentos para o Câncer de Mama

<br>


- **Nome do Estudante**: Marlon de Souza.
- **Curso**: Engenharia de Software.
- **Data de Entrega**: --

<br>

# Resumo

&nbsp;&nbsp;&nbsp;&nbsp; O presente trabalho propõe o uso de ferramentas de Inteligência Artificial (IA), em especial redes neurais artificiais com método K-Fold, para analisar combinações de proteínas e aminoácidos que possam contribuir para o desenvolvimento de novas estratégias terapêuticas no tratamento do câncer de mama. Fundamentado em bioquímica estrutural, química orgânica, proteômica e oncologia, o projeto explora os recentes avanços no mapeamento das estruturas proteicas, como os proporcionados pela AlphaFold — que, em 2020, utilizando IA, foi capaz de auxiliar na catalogação de pouco mais de 200 milhões de proteínas - Praticamente todo o reino animal -, em contraste às cerca de 150 mil identificadas até 2015 após seis décadas de pesquisa por meio de métodos convencionais. Tendo isso em vista, espera-se utilizar IA para analisar combinações de proteínas, e assim, contribuir para um tratamento mais eficaz, ampliando as perspectivas terapêuticas no combate ao câncer de mama.

## 1. Introdução

&nbsp;&nbsp;&nbsp;&nbsp;O câncer de mama representa um dos maiores desafios na área de oncologia devido à sua alta incidência e complexidade biológica. Nesse contexto, a aplicação de ferramentas de Inteligência Artificial (IA) tem se mostrado promissora para o avanço na compreensão e no tratamento da doença. O presente trabalho propõe o uso de IA, em especial redes neurais artificiais com método K-Fold, para analisar combinações de proteínas e aminoácidos com potencial terapêutico na cura ou controle do câncer de mama. A iniciativa se apoia nos fundamentos de bioquímica estrutural, química orgânica e proteômica, áreas que permitem investigar em profundidade as estruturas, funções e reatividade química desses biomoléculas.
 
&nbsp;&nbsp;&nbsp;&nbsp;A base conceitual do projeto reside, em parte, nos resultados obtidos pela AlphaFold, que demonstrou o poder da IA na elucidação de estruturas proteicas. Até 2015, depois de mais de seis décadas de pesquisa, haviam sido catalogadas apenas cerca de 150 mil proteínas por métodos experimentais convencionais. Em 2020, graças aos avanços trazidos pela IA desenvolvida pela AlphaFold, foi possível catalogar mais de 200 milhões de proteínas, abrangendo quase todo o reino animal. Esses números evidenciam o potencial transformador das soluções computacionais na pesquisa biomédica.
 
&nbsp;&nbsp;&nbsp;&nbsp;Assim, a presente proposta busca integrar conhecimentos de oncologia, proteômica e nutrição clínica avançada para desenvolver modelos preditivos capazes de sugerir novas estratégias terapêuticas ou complementares ao tratamento do câncer de mama. A relevância e a originalidade do projeto residem em explorar as possibilidades abertas pela IA para acelerar a identificação de proteínas e aminoácidos promissores, contribuindo para o desenvolvimento de tratamentos personalizados e mais eficazes na área oncológica.

## 2. Descrição do Projeto

- **Tema do Projeto**: 

    - Oncologia: Auxiliar no tratamento do cancer de mama;
    - Proteômica: Estudo das estruturas e funções das proteínas;
    - Bioquímica Estrutural: Estrutura e funças das biomoléculas - Proteínas, aminoacidos e etc;
    - Química Orgânica: Examina a estrutura e reatividade química dos aminoácidos.
    - Redes Neurais Artificias com método K-Fold: Uso de redes neurais artificiais para análise de combinações e de proteinas e aminoacidos.
    - Estudos sobre como funciona o câncer de mama e seus tratamentos;
    - Estudos sobre ia aplicadas para detecção de câncer;
    - Relação de nutrição clinica avançada na área de oncologia no tratamento de pacientes com cancer / pós-cancer;

<br>

- **Problemas a Resolver**: Auxiliar na cura do cancer por meio do uso de inteligencia Artificial

- **Limitações**: A definir

## 3. Especificação Técnica

&nbsp;&nbsp;&nbsp;&nbsp;A seguir, apresenta-se a visão dos aspectos técnicos do projeto, englobando requisitos de software, protocolos, algoritmos, procedimentos de desenvolvimento, formatos de dados, entre outros elementos essenciais à implementação e ao funcionamento da solução proposta.

### 3.1. Requisitos de Software

&nbsp;&nbsp;&nbsp;&nbsp;Nesta seção, são descritos os requisitos necessários para a construção do ambiente de desenvolvimento e execução do projeto, bem como os requisitos funcionais e não funcionais que orientam o comportamento e a qualidade do sistema.

#### 3.1.1. Requisitos Funcionais (RF)

**1. RF01 – Avaliação e comparação de modelos**

&nbsp;&nbsp;&nbsp;&nbsp;O sistema deve fornecer métricas de desempenho (Acurácia, Precisão, Recall, AUC-ROC) e uma matriz de confusão para cada modelo testado, possibilitando a comparação e seleção do melhor classificador.

**2. RF02 – Geração de recomendações**

&nbsp;&nbsp;&nbsp;&nbsp;A partir dos resultados dos modelos, o modelo de IA deve sugerir possíveis combinações de proteínas e aminoácidos com maior potencial terapêutico para o tratamento do câncer de mama.

**3. RF03 – Processamento de dados proteicos**

&nbsp;&nbsp;&nbsp;&nbsp;O sistema deve permitir a entrada de dados de proteínas e aminoácidos, oriundos de bases experimentais ou predições computacionais (e.g., AlphaFold), para posterior análise e correlação com cenários oncológicos.

#### 3.1.2. Requisitos Não Funcionais (RNF)

**RNF01 – Confiabilidade e disponibilidade**

&nbsp;&nbsp;&nbsp;&nbsp;O sistema deve manter registros consistentes dos resultados dos experimentos (logs, pesos dos modelos, parâmetros) e oferecer alta disponibilidade, minimizando o risco de falhas durante as rotinas de treinamento e teste.

### 3.2. Considerações de Design

**1. Módulo de Treinamento e Validação:**

Rodar as rotinas de Machine Learning.

**2. Módulo de Avaliação e Visualização:**

Gera métricas de desempenho, matrizes de confusão e gráficos comparativos.

**3. Camada de Persistência:**

Armazena parâmetros, pesos de modelos, configurações de folds e dados de logs.

### 3.3. Stack Tecnológica

- **Linguagens de Programação**:
    - Python (principal linguagem para Machine Learning e manipulação de dados)
- **Frameworks e Bibliotecas**: 
    - **TensorFlow / Keras:** Criação e treinamento de Redes Neurais Artificiais.
    - **scikit-learn:** Implementação de algoritmos de KNN, validação cruzada (K-Fold) e outras técnicas de aprendizado de máquina.
    - **Pandas e NumPy:** Manipulação e análise de dados em escala.
    - **Matplotlib:** Visualização de resultados (como curvas ROC e matrizes de confusão).

<br>

- **Ferramentas de Desenvolvimento e Gestão de Projeto**:
    - Github projects; 
    - DrawIo (para criação de fluxogramas);
    - Mermaid.js

### 3.4. Avaliação e teste dos modelos de IA

### Métricas de Desempenho

- **Acurácia**: Mede a proporção de todas as previsões corretas em relação ao total de previsões feitas pelo modelo. Ou seja, é a taxa de acertos globais, considerando tanto classes positivas quanto negativas.
- **Precisão**: Mede a proporção de previsões corretas entre todas as previsões positivas feitas pelo modelo. Em outras palavras, é a quantidade de verdadeiros positivos em relação ao total de positivos preditos.
- **Recall (Sensibilidade)**: Proporção de positivos reais que foram corretamente identificados pelo modelo.
- **AUC-ROC**: Métrica que avalia a capacidade do modelo em distinguir entre as classes positivas e negativas.

### Matriz de Confusão

Por exemplo, a matriz de confusão de um Modelo x é apresentada a seguir:



<div align="center">


**----Exemplo matriz de confusão----**



</div>


Imagine que estamos tentando prever se vai chover em Joinville-SC ou não.

- **Verdadeiro Positivo (TP):** O modelo previu que ia chover, e realmente choveu.
- **Falso Positivo (FP):** O modelo previu que ia chover, mas não choveu.
- **Falso Negativo (FN):** O modelo previu que não ia chover, mas choveu.
- **Verdadeiro Negativo (TN):** O modelo previu que não ia chover, e realmente não choveu.

### 3.5. Conceitos de Overfitting e Underfitting

- **Overfitting**: Ocorre quando o modelo se ajusta tão bem aos dados de treinamento que não generaliza bem para novos dados. O modelo "decora" os dados de treinamento, perdendo a capacidade de fazer predições precisas em dados desconhecidos.

- **Underfitting**: Acontece quando o modelo é muito simples e não consegue capturar padrões nos dados. Ele não consegue nem mesmo representar bem os dados de treinamento, resultando em baixa performance tanto em treinamento quanto em teste.

## 4. Próximos Passos

Para definição dos próximos passos será necessário concluir passos anteriores, assim, sendo capaz de analisar os resultados obtidos e 
decidir o melhor caminho para seguir.

### 4.1 Criação de Modelo para diagnóstico de cancer de mama:

&nbsp;&nbsp;&nbsp;&nbsp;Como primeiro passo deste projeto, propõe-se a construção de um modelo de Rede Neural ou KNN, empregando o método de validação cruzada K-Fold, para o diagnóstico de câncer de mama. A base de dados em uso (referida como “Dados de Câncer de Mama”) conta com 569 instâncias e 30 features, obtidas a partir de exames de biópsia (por exemplo, características relacionadas aos núcleos celulares). Essas variáveis permitem distinguir, de forma mais precisa, tumores benignos de tumores malignos, contribuindo para a eficiência dos processos de triagem e diagnóstico.

## 5. Referências

- [AlphaFold](https://www.youtube.com/watch?v=P_fHJIYENdI&t=1217s)
- [Dados Treinamento](http://archive.ics.uci.edu/)
- [Dados Cancer de mama](http://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- A definir

## 7. Avaliações de Professores

Adicionar três páginas no final do RFC para que os Professores escolhidos possam fazer suas considerações e q

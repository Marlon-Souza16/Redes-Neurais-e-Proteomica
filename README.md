# Redes Neurais e Proteômica: Aplicando IA na Descoberta de Tratamentos para o Câncer de Mama

<br>


- **Nome do Estudante**: Marlon de Souza.
- **Curso**: Engenharia de Software.
- **Data de Entrega**: --

<br>

# Resumo

&nbsp;&nbsp;&nbsp;&nbsp; O presente trabalho propõe o uso de ferramentas de Inteligência Artificial (IA), em especial redes neurais artificiais com método K-Fold, para analisar combinações de proteínas e aminoácidos que possam contribuir para o desenvolvimento de novas estratégias terapêuticas no tratamento do câncer de mama. Fundamentado em bioquímica estrutural, química orgânica, proteômica e oncologia, o projeto explora os recentes avanços no mapeamento das estruturas proteicas, como os proporcionados pela AlphaFold — que, em 2020, utilizando IA, foi capaz de auxiliar na catalogação de pouco mais de 200 milhões de proteínas - Praticamente todo o reino animal -, em contraste às cerca de 150 mil identificadas até 2015 após seis décadas de pesquisa por meio de métodos convencionais. Tendo isso em vista, espera-se utilizar IA para analisar combinações de proteínas, e assim, contribuir para um tratamento mais eficaz, ampliando as perspectivas terapêuticas no combate ao câncer de mama.

<br>

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

Descrição detalhada da proposta, incluindo requisitos de software, protocolos, algoritmos, procedimentos, formatos de dados, etc.

### 3.x. Avaliação e teste dos modelos de IA

### Métricas de Desempenho

- **Acurácia**: Proporção de todas as previsões corretas do modelo.
- **Precisão**: Proporção de predições corretas em relação às predições positivas feitas pelo modelo.
- **Recall (Sensibilidade)**: Proporção de positivos reais que foram corretamente identificados pelo modelo.
- **AUC-ROC**: Métrica que avalia a capacidade do modelo em distinguir entre as classes positivas e negativas.

### Matriz de Confusão

Por exemplo, a matriz de confusão de um Modelo x é apresentada a seguir:



<div align="center">


**----Exemplo matriz de confusão----**



</div>


Imagine que estamos tentando prever se vai chover em Joinville ou não.

- **Verdadeiro Positivo (TP):** O modelo previu que ia chover, e realmente choveu.
- **Falso Positivo (FP):** O modelo previu que ia chover, mas não choveu.
- **Falso Negativo (FN):** O modelo previu que não ia chover, mas choveu.
- **Verdadeiro Negativo (TN):** O modelo previu que não ia chover, e realmente não choveu.

### 3.x. Conceitos de Overfitting e Underfitting

- **Overfitting**: Ocorre quando o modelo se ajusta tão bem aos dados de treinamento que não generaliza bem para novos dados. O modelo "decora" os dados de treinamento, perdendo a capacidade de fazer predições precisas em dados desconhecidos.

- **Underfitting**: Acontece quando o modelo é muito simples e não consegue capturar padrões nos dados. Ele não consegue nem mesmo representar bem os dados de treinamento, resultando em baixa performance tanto em treinamento quanto em teste.

### 3.1. Requisitos de Software
- Apresentar os requisitos do tema proposto.
- **Lista de Requisitos:** Apresentar uma lista contendo os Requisitos Funcionais (RF) e Não-Funcionais (RNF).
- **Representação dos Requisitos:** Representar os RFs por meio de um Diagrama de Casos de Uso (UML).

### 3.2. Considerações de Design

- Discussão sobre as escolhas de design, incluindo alternativas consideradas e justificativas para as decisões tomadas.
- **Visão Inicial da Arquitetura**: Descrição dos componentes principais e suas interconexões.
- **Padrões de Arquitetura**: Indicação de padrões específicos utilizados (ex.: MVC, Microserviços).
- **Modelos C4**: Detalhamento da arquitetura em níveis: Contexto, Contêineres, Componentes, Código.

### 3.3. Stack Tecnológica

- **Linguagens de Programação**: Python
- **Frameworks e Bibliotecas**: 
    - TensorFlow;
    - Sklearn;
    - Keras;
    - Pandas;
    - Numpy;

<br>

- **Ferramentas de Desenvolvimento e Gestão de Projeto**:
    - Github projects; 
    - DrawIo (para criação de fluxogramas);
    - Mermaid.js

### 3.4. Considerações de Segurança

Análise de possíveis questões de segurança e como mitigá-las.

## 4. Próximos Passos

Descrição dos passos seguintes após a conclusão do documento, com uma visão geral do cronograma para Portfólio I e II.

## 5. Referências

- [AlphaFold](https://www.youtube.com/watch?v=P_fHJIYENdI&t=1217s)
- [Dados Treinamento](http://archive.ics.uci.edu/)
- [Dados Cancer Pulmão](http://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic)
- A definir

## 7. Avaliações de Professores

Adicionar três páginas no final do RFC para que os Professores escolhidos possam fazer suas considerações e q

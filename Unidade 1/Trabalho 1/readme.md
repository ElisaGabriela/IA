# Trabalho 1 - Unidade 1 - Inteligência artificial

## Objetivos
Objetivo : Pesquise e apresente um trabalho sobre o algoritmo Naïve-Bayes para a detecção de Spam em
mensagens de email ou para classificar páginas de texto com base em um tema de interesse (esporte,
política, ...etc.) presente nas palavras que aparecem nas páginas.
O algoritmo Naïve-Bayes é uma técnica estatística que usa a teoria de probabilidade para classificar dados
em categorias. Ele é amplamente utilizado em tarefas de classificação, como a detecção de spam em
mensagens de email ou classificação de páginas de texto com base em um tema específico. Neste trabalho,
vamos explorar como o algoritmo Naïve-Bayes pode ser usado para detectar spam em mensagens de email e classificar páginas de texto com base em um tema de interesse.

## Detecção de Spam em mensagens de email
A detecção de spam em mensagens de e-mail é uma das aplicações mais comuns do algoritmo NaïveBayes. A ideia básica por trás da detecção de spam é que as mensagens de spam tendem a ter certas
características em comum, como palavras-chave específicas, linguagem agressiva, uso excessivo de letras
maiúsculas, entre outras. Por outro lado, as mensagens legítimas tendem a ter um estilo de linguagem mais
formal e apresentam informações mais relevantes para o usuário.
O algoritmo Naïve-Bayes pode ser usado para detectar spam em mensagens de e-mail, analisando o
conteúdo da mensagem e classificando-a como spam ou não-spam com base em sua probabilidade
condicional. O algoritmo Naïve-Bayes é "ingênuo" porque assume que as palavras são independentes umas
das outras e não considera a ordem em que elas aparecem na mensagem. Isso simplifica o cálculo das
probabilidades e torna o algoritmo mais eficiente.
Para treinar o modelo, é necessário um conjunto de dados rotulados que contenham exemplos de
mensagens de spam e mensagens legítimas. O modelo pode então calcular a probabilidade de cada
palavra aparecer em uma mensagem de spam ou em uma mensagem legítima, bem como a probabilidade
de uma mensagem ser spam ou não. Quando uma nova mensagem é recebida, o modelo calcula a
probabilidade condicional de a mensagem ser spam ou não com base na frequência de cada palavra na
mensagem. Se a probabilidade de a mensagem ser spam for maior do que a probabilidade de não ser
spam, a mensagem é classificada como spam e, caso contrário, como não spam.

## Classificação de páginas de texto com base em um tema de interesse
Outra aplicação do algoritmo Naïve-Bayes é a classificação de páginas de texto com base em um tema de
interesse. A classificação de texto é uma tarefa importante em muitas áreas, como na análise de
sentimentos, no reconhecimento de idiomas e na classificação de documentos.
O algoritmo Naïve-Bayes pode ser usado para classificar páginas de texto com base em um tema
específico, como esporte, política ou tecnologia. O modelo pode ser treinado com um conjunto de dados
rotulados que contenham exemplos de páginas de texto relacionadas a cada tema. O modelo pode então
calcular a probabilidade de cada palavra aparecer em uma página de texto relacionada a um determinado
tema e a probabilidade de uma página ser relacionada a um tema específico.
Quando uma nova página de texto é recebida, o modelo calcula a probabilidade condicional de a página
estar relacionada a um determinado tema com base na frequência de cada palavra na página. Se a
probabilidade de a página estar relacionada a um determinado tema for maior do que a probabilidade de
não estar relacionada, a página é classificada como relacionada a esse tema e, caso contrário, como não
relacionada.
O algoritmo Naïve-Bayes tem se mostrado eficaz em tarefas de classificação de texto, como a classificação
de notícias em categorias temáticas ou a análise de sentimentos em textos de mídias sociais.



**UTILIZANDO INTELIGÊNCIA ARTIFICIAL PARA IDENTIFICAÇÃO DE NOTÍCIAS FALSAS**

  

**FACULDADE DE TECNOLOGIA DE SÃO JOSÉ DOS CAMPOS**

  

Trabalho de Graduação apresentado à Faculdade de Tecnologia de São José dos Campos, como parte dos requisitos necessários para a obtenção do título de Tecnólogo em Banco de Dados.

  

Orientador: Prof. Me. Emanuel Mineda Carneiro

São José dos Campos, 2020

Dados Internacionais de Catalogação-na-Publicação (CIP)

Divisão de Informação e Documentação

  

REFERÊNCIA BIBLIOGRÁFICA

  

SOUZA, Mateus. Utilizando inteligência artificial para identificação de notícias falsas. 2020. 999f. Trabalho de Graduação - FATEC de São José dos Campos: Professor Jessen Vidal.

  

NOME(S) DO(S) AUTOR(ES): Mateus Machado de Souza

TÍTULO DO TRABALHO: Utilizando inteligência artificial para identificação de notícias falsas

TIPO DO TRABALHO/ANO: Trabalho de Graduação/2020.

  

  

É concedida à FATEC de São José dos Campos: Professor Jessen Vidal permissão para reproduzir cópias deste Trabalho e para emprestar ou vender cópias somente para propósitos acadêmicos e científicos. O autor reserva outros direitos de publicação e nenhuma parte deste Trabalho pode ser reproduzida sem a autorização do autor.

  

_____________________________________

  

MATEUS MACHADO DE SOUZA

  

UTILIZANDO INTELIGÊNCIA ARTIFICIAL PARA IDENTIFICAÇÃO DE NOTÍCIAS FALSAS

  

Trabalho de Graduação apresentado à Faculdade de Tecnologia de São José dos Campos, como parte dos requisitos necessários para a obtenção do título de Tecnólogo em Banco de Dados.

  

1. **INTRODUÇÃO**

  


Após a popularização da internet, acelerada principalmente após os anos 2000 (INTERNET GROWTH STATISTICS), novos espaços para diversos tipos de discussão online são criados. O fenômeno da ascensão das redes sociais tem destaque em especial, pois conectam as pessoas, diminuem a distância

física e tem assumido um papel de extensão da identidade individual. São também um meio para compartilhamento de conteúdo e ideias, o que pode ser na verdade bastante relevante para a época atual, onde grande parte das pessoas se informa pela internet.

A propagação de informações falsas tem encontrado seu vetor de propagação neste cenário, uma vez que, remover dados da internet é uma tarefa quase impossível, dado que são replicados em incontáveis dispositivos e servidores de forma muito rápida. É possível observar a influência exercida sobre o comportamento de uma sociedade em 2016, durante a eleição no Estados Unidos, onde as últimos cinco meses antes ao dia da eleição, 30 milhões de publicações feitas no twitter de 2.2 milhões de usuários diferentes, contém 25% de notícias falsas ou tendenciosas (Bovet, A., 2019).

É uma tarefa extremamente árdua checar manualmente a quantidade de notícias que circulam e identificar quais são falsas ou não. Isso pode tornar difícil proteger a sociedade dos efeitos coletivos dessa desinformação, tendo diversas consequências inclusive a desestabilização da democracia.

  

Este trabalho propõe a utilização de inteligência artificial, para acelerar o problema extremamente complexo de checar notícias, através do uso mais especificamente de stance detection.

  

**1.1. Objetivos do Trabalho**

O objetivo geral deste é utilização de inteligência artificial, para acelerar o problema extremamente complexo de checar a veracidade de notícias.

Para a consecução deste objetivo foram estabelecidos os objetivos específicos:

-   Realizar uma investigação sobre as implementações de stance detection no campo de identificações de notícias falsas;
    
-   Realizar a pesquisa por data sets em português que possam servir para o propósito deste trabalho;
    
-   Implementar um sistema capaz de identificar notícias falsas utilizando stance detection.

  

**1.2. Conteúdo do Trabalho**

  


O presente trabalho está estruturado em seis capítulos, cujo conteúdo é sucintamente apresentado a seguir:

No Capítulo 2 é feita a fundamentação das tecnologias necessárias para o entendimento do trabalho.

O Capítulo 3 apresenta o desenvolvimento da solução para a identificação de notícias falsas.

No Capítulo 4 são apresentados os resultados obtidos a partir do modelo desenvolvido.

O Capítulo 5 apresenta as considerações finais deste trabalho a partir da análise dos resultados obtidos.

**2. FUNDAMENTAÇÃO TÉCNICA**

**2.1. Machine Learning**

Machine Learning é uma aplicação do campo de inteligência artificial (IA) com capacidade de realizar tarefas para as quais a aplicação não foi programada explicitamente, identificado automaticamente padrões em dados e usando-os para predizer o dado futuro (Kevin P. Murphy, 2012).

**2.2. Stance Detection**

Stance Detection é a tarefa de identificar a partir de um texto, se o autor é a favor ou contra um alvo. É similar a análise de sentimentos, entretanto, possui a diferença de que o alvo pode nem sempre estar explícito na sentença, ou ainda, a sentença pode ser positiva em relação ao alvo, e ainda sim ser inferido que o autor é contra o alvo (tópico ou instituição, por exemplo). Isso torna o stance detection mais complexo, mas em geral pode trazer mais informações (Krejzl, P., Steinberger, J., 2016).

------------------------

REFERÊNCIAS

  

Bovet, A., Makse, H.A. Influence of fake news in Twitter during the 2016 US presidential election.  NATURE COMMUNICATION, Vol. 10, p. 03-04, 2019

History and Growth of the Internet from 1995 till Today. INTERNET GROWTH STATISTICS. Disponível em https://www.internetworldstats.com/emarketing.htm Acesso em: 25/05/2020

The MIT Press, Massachusetts Institute of Technology (Cambridge, Massachusetts). Kevin P. Murphy. Machine Learning: A Probabilistic Perspective. 2012.

Krejzl, P., Steinberger, J., 2016, UWB at SemEval-2016 Task 6: Stance Detection, Proceedings of SemEval 2016, pages 408-412, ACL

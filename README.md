# DDD - Domain Driven Design

Domain Driven Design significa Projeto Orientado à Domínio. É uma filosofia de desenvolvimento que foi divulgada por Eric Evans em 2003.

> Ele percebeu que um conjunto de boas práticas de desenvolvimento, trabalho em equipe e estratégias de negócio podem contribuir para que um projeto complexo seja bem sucedido.

O DDD procura construir software de qualidade, utilizando-se de padrões táticos e estratégicos para se atingir boas práticas de modelagem e desenvolvimento.

Defende a ideia de que toda a equipe envolvida na criação do sistema, seja do ponto de visto técnico ou do negócio, possua conhecimento sobre o Domínio do Problema.


## O que é um padrão?

Um padrão é uma regra de três partes que expressa a relação entre um **contexto (1)**, um **problema (2)** e uma **solução (3)**.


## DDD é uma arquitetura?

Normalmente, aprendemos e colocamos em prática um modelo de análise e desenvolvimento de softwares semelhante aos passos a seguir:

1. Os analistas e especialistas de negócios fazem um levantamento funcional e elaborarão um documento extenso de especificação funcional. Talvez um DBA participe para MER, documentos e diagramas.  
2. Então, arquitetos e/ou líderes técnicos desenham a arquitetura do projeto.  
3. Então, os desenvolvedores começam a codificar e implementar os requisitos.

![Exemplo de tradição de desenvolvimento](https://www.lambda3.com.br/wp-content/uploads/2017/10/desmistificandooddd_1.png)

Porém, boa parte desse modelo não funciona, por inúmeras razões.

As mudanças serão necessárias para atender as necessidades atuais dos usuários, e não as de meses atrás.

Os desenvolvedores podem encontrar dificuldades em implementar as mudanças dentro de um padrão imposto. Isso gera complexidade técnica acidental.

E, à medida que o sistema vai crescendo, a complexidade técnica acidental fica maior do que a própria complexidade do negócio.

![Crescimento da complexidade técnica](https://www.lambda3.com.br/wp-content/uploads/2017/10/desmistificandooddd_2.png)

E, desenvolver software de uma forma em que não seja possível realizar mudanças estruturais durante o desenvolvimento, normalmente leva a projetos de baixa qualidade.


### Onde o DDD entra nisso?

O DDD é uma filosofia que é voltada ao domínio do negócio.

O entendimento do domínio do negócio é um processo crescente, onde a comunicação e cooperação da equipe é necessária à todo momento, diferentemente do modelo tradicional, onde a comunicação é realizada apenas em algumas etapas do projeto.

Nessa filosofia, temos um fluxo de comunicação contínua e colaborativa, por meio de uma única linguagem.


### Fluxo de análise e desenvolvimento com linguagem ubíqua

![Fluxo de análise e desenvolvimento com linguagem ubíqua](https://www.lambda3.com.br/wp-content/uploads/2017/10/desmistificandooddd_3.png)

O código reflete ao domínio, estando na mesma linguagem dos especialistas de negócios e usuários. Termos técnicos são substituídos por termos que usuário possa compreender.

O time de desenvolvimento como um todo se torna responsável pela arquitetura do projeto. O arquiteto ainda pode até existir, porém, fica em uma posição mais colaborativa e próxima do dia a dia do desenvolvimento.

A implementação da solução é emergente. Começando simples e crescendo junto com o entendimento do domínio, e não em etapas separadas.

A energia e foco do time, seja técnico ou não, é direcionada apenas à um objetivo, o de solucionar o problema do domínio, de uma forma em que o código reflita o domínio.

Mesmo o DDD não sendo um padrão de arquitetura, ele afeta como as decisões arquiteturais são tomadas, e o próprio papel do arquiteto no time.


### DDD é o modelo ideal para se trabalhar?

Depende! O DDD é um modo de lidar com domínios complexos. Se o domínio em questão for simples, será mais eficiente utilizar designs mais simples.

> O DDD é voltado para domínios complexos, e depende da quebra de barreiras de comunicação entre especialistas de negócio e especialistas técnicos, além do engajamento do time técnico em programar de forma que o código reflita o domínio. Se uma dessas variáveis for negativa, provavelmente o DDD não serve para o cenário que você está lidando.

Está claro que o DDD não é uma arquitetura, nem uma bala de prata que resolverá qualquer problema que vier.


# Referências

[Desmistificando o DDD](https://www.lambda3.com.br/2017/10/desmistificando-o-ddd/)  
[Domain Driven Design: Entenda o que é](https://programadoresbrasil.com.br/2020/04/domain-driven-design-o-que-e/)

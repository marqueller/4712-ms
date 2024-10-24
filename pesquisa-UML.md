Criar um diagrama UML

1.1 O que é UML?
A Linguagem de modelagem unificada (UML) foi criada para estabelecer uma linguagem de modelagem visual comum, semanticamente e sintaticamente rica, para arquitetura, design e implementação de sistemas de software complexos, tanto estruturalmente quanto para comportamentos. Além do desenvolvimento de software, a UML tem aplicações em fluxos do processo na fabricação.

É análoga aos modelos utilizados em outros campos, e é composta por diferentes tipos de diagramas. De modo geral, diagramas UML descrevem o limite, a estrutura e o comportamento do sistema e os objetos nele contidos.

A UML não é uma linguagem de programação, mas existem ferramentas que podem ser usadas para gerar código em várias linguagens por meio de diagramas UML. A UML tem uma relação direta com a análise e o design orientados a objetos.

A UML e seu papel na modelagem e no design orientados a objetos
Existem muitos paradigmas ou modelos de resolução de problemas na ciência da computação, que é o estudo de algoritmos e dados. Há quatro categorias modelo de resolução de problemas: linguagens imperativas, funcionais, declarativas e orientadas a objetos (POO). Em linguagens orientadas a objetos, os algoritmos são expressos através da definição de ‘objetos’, e por meio da interação dos objetos uns com os outros. Esses objetos são coisas a serem manipulados, e eles existem no mundo real. Eles podem ser edifícios, widgets em um desktop ou seres humanos. 

Linguagens orientadas a objetos dominam o mundo da programação porque elas modelam objetos do mundo real. A UML é uma combinação de várias notações orientadas a objetos: design orientado a objetos, técnica de modelagem de objetos e engenharia de software orientada a objetos.

A UML usa os pontos fortes destas três abordagens para apresentar uma metodologia mais consistente e mais fácil de usar. A UML representa as melhores práticas para desenvolver e documentar aspectos diferentes da modelagem de software e sistemas de negócios

1.2 1. Diagrama de Casos de Uso
Ator: Usuário (Leitor)

Casos de Uso:

Buscar Livro
Reservar Livro
Emprestar Livro
Devolver Livro
2. Diagrama de Classes
Classes:

Livro

Atributos: título, autor, ISBN, disponibilidade
Métodos: verificarDisponibilidade(), reservar(), emprestar()
Usuário

Atributos: nome, ID, endereço, telefone
Métodos: buscarLivro(), reservarLivro(), emprestarLivro(), devolverLivro()
Bibliotecário

Atributos: nome, ID, turno
Métodos: adicionarLivro(), removerLivro(), atualizarLivro()
3. Diagrama de Sequência
Cenário: Um usuário empresta um livro.

O Usuário solicita o empréstimo de um livro.
O Sistema verifica a disponibilidade do livro.
Se disponível, o Sistema registra o empréstimo.
O Sistema atualiza a disponibilidade do livro.
O Usuário recebe a confirmação do empréstimo
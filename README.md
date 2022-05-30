# Abstraindo um Bootcamp usando Programação Orientada a Objetos em Java

## 1) O objetivo principal é colocar em prática umas das principais ferramentas da OO: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO, através de um projeto Java.

1.1) Vamos ABSTRAIR o DOMÍNIO Bootcamp e MODELAR seus ATRIBUTOS E MÉTODOS;

1.2) Criaremos as CLASSES: Bootcamp, Cursos, Mentorias e Devs e vamos relaciona-las;

1.3) As CLASSES Curso, Mentoria e Devs também serão MODELADOS, ou seja, criaremos seus ATRIBUTOS E MÉTODOS;

1.4) Para que o código fique mais legível e de fácil manutenção, iremos utilizar de algumas das ferramentas que o PARADIGMA DE ORIENTAÇÃO A OBJETOS (POO) nos oferece: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO;

1.5) E para representar CLASSES que foram criadas e relacionadas, iremos transforma-las em OBJETOS;

## 2) Paradigma de Programação Orientado a Objetos (POO)

2.1) A visão de Orientação a Objetos (OO) é aquela de um mundo de objetos que interagem.

2.2) Este paradigma é um modelo de análise, projeto e programação baseado na aproximação entre o mundo real e o mundo virtual, através da criação e interação entre classes, atributos, métodos, objetos, entre outros.

2.3) São 4 os pilares principais do POO: ABSTRAÇÃO, ENCAPSULAMENTO, HERANÇA E POLIMORFISMO.

* 2.3.1) ABSTRAÇÃO:
  Habilidade de concentrar-se nos aspectos essenciais de um domínio, ignorando características menos importantes ou acidentais. Nesse contexto, objetos são abstrações de entidades existentes no domínio em questão.

* 2.3.2) ENCAPSULAMENTO:
  Encapsular significa esconder a implementação dos objetos. O encapsulamento favorece principalmente dois aspectos de um sistema: a manutenção e a evolução.

* 2.3.3) HERANÇA:
  Permite que você defina uma classe filha que reutiliza (herda), estende ou modifica o comportamento de uma classe pai. A classe cujos membros são herdados é chamada de classe base. A classe que herda os membros da classe base é chamada de classe derivada.

* 2.3.4) POLIMORFISMO:
  Capacidade de um objeto poder ser referenciado de várias formas. Cuidado, polimorfismo não quer dizer que o objeto fica se transformando, muito pelo contrário, um objeto nasce de um tipo e morre daquele tipo, o que pode mudar é a maneira como nos referimos a ele. A capacidade de tratar objetos criados a partir das classes específicas como objetos de uma classe genérica é chamada de polimorfismo.

## 3) Conceitos Fundamentais (POO)

* 3.1) DOMÍNIO: Domínio da aplicação, também conhecida como camada de negócio ou de objetos de negócio, é aquela onde estão localizadas as classes que fazem parte do domínio do problema, ou seja, classes correspondentes a objetos que fazem parte da descrição do problema.

* 3.2) CLASSE: Um elemento do código que tem a função de representar objetos do mundo real. Dentro dela é comum declararmos atributos e métodos, que representam, respectivamente, as características e comportamentos desse objeto.

* 3.3) ATRIBUTO: Atributos são, basicamente, a estrutura de dados que vai representar a classe. Os atributos também são conhecidos como VARIÁVEL DE CLASSE, e podem ser divididos em dois tipos básicos: atributos de instância e de classe.

* 3.4) VARIÁVEL: Uma “região de memória (do computador) previamente identificada cuja finalidade é armazenar os dados ou informações de um programa por um determinado espaço de tempo”.

* 3.5) MÉTODO: Os métodos representam os estados e ações dos objetos e classes.

* 3.6) OBJETO: Em POO, objeto é um "molde" de uma determinada classe, que passa a existir a partir de uma instância da classe. A classe define o comportamento do objeto, usando atributos (propriedades) e métodos (ações). Objeto em ciência da computação, é uma referência a um local da memória que possui um valor. Um objeto pode ser uma variável, função, ou estrutura de dados.

* 3.7) INSTÂNCIA: Uma instância de uma classe é um novo objeto criado dessa classe, com o operador new. Instanciar uma classe é criar um novo objeto do mesmo tipo dessa classe. Uma classe somente poderá ser utilizada após ser instanciada.

## 4) Linguagem de Programação vs Paradigma de Linguagem de Programação

* 4.1) LINGUAGEM DE PROGRAMAÇÃO: É uma linguagem formal que, através de uma série de instruções, permite que um programador escreva um conjunto de ordens, ações consecutivas, dados e algoritmos para criar programas que controlam o comportamento físico e lógico de uma máquina.

* 4.2) Seguem alguns exemplos de como as linguagens de programação podem ser classificadas:

### 4.3) Nível de abstração:

* 4.3.1) Baixo Nível: Assembly

* 4.3.2) Médio Nível: C, C++, D, Objective C, etc.

* 4.3.3) Alto Nível: Java, C#, PHP, Javascript, etc.

* 4.3.4) Altíssimo Nível: Python, Ruby, Elixir, etc.

### 4.4) Paradigma de programação:

* 4.4.1) Programação Estruturada: C, Pascal, Ada, etc.

* 4.4.2) Programação Orientada a Objetos: Java, C#, C++, Objective C, D, etc.

* 4.4.3) Programação Funcional: Lisp, Scheme, Erlang, Elixir, etc.

### 4.5) Linguagens classificadas pela arquitetura da aplicação:

* 4.5.1) Desktop: C, C++, Object Pascal, Java, etc.

* 4.5.2) Web: PHP, Ruby, Javascript, Java, etc.

### 4.6) Tipo de execução:

* 4.6.1) Linguagens compiladas: C, C++, Pascal, D, GO, etc.

* 4.6.2 Linguagens Interpretadas: Python, Ruby, PHP, Javascript, etc.

* 4.6.3) Linguagens Hibridas: Java, Erlang, Elixir, etc.

## 5) Paradigma de Linguagem de Programação

* 5.1) É um conjunto de características que podem ser utilizados para categorizar determinado grupo de linguagens. Um paradigma pode oferecer técnicas apropriadas para uma aplicação específica.

## 6) Paradigmas Principais e seus Subparadigmas

### 6.1) Paradigma Imperativo: Neste paradigma, o programa descreve o processamento necessário para solucionar o problema. Assim, o paradigma imperativo é caracterizado por execução sequencial de instruções, pelo uso de variáveis que representam posições de memória e pelo uso de instruções de atribuição que alteram os valores dessas variáveis.

* 6.1.1) Vejamos alguns Subparadigmas do Paradigma Imperativo e exemplos linguagens de programação que adotam esses subparadigmas.

* 6.1.2) Paradigma estruturado: ALGOL 58 e ALGOL 60

* 6.1.3) Paradigma concorrente: Java e Ada

* 6.1.4) Paradigma Orientado a Objetos: Smalltalk e Java

### 6.2) Paradigma Declarativo: Este paradigma é o modelo no qual os resultados são descritos, mas os passos para chegar aos resultados não são estabelecidos.

* 6.2.1) Vejamos alguns Subparadigmas do Paradigma Declarativo e exemplos linguagens de programação que adotam esses subparadigmas:

* 6.2.2) Paradigma Funcional: Lisp e Haskell

* 6.2.3) Paradigma Lógico: Prolog
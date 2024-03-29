# Repositório JAVA:
 #### Nele será depositado todo material de apoio e estudo durante o aprendizado da linguagem de programacao JAVA.

## Teclas de atalho:
  - 'ALT + Shif + R' = Renomear nomes de Variáveis.
  - 'Ctrl + Shift + F' = Ambienta código.
  - 'Ctrl + Shift + O' = Importa pacote.
  - 'Botão direito -> Source -> Generate Getters and Setters'.

## Documentação:
## 1. Introdução:
### 1.1 Organização Classes e Bibliotecas:
#### [Caelum](https://www.caelum.com.br/apostila-java-orientacao-objetos/pacotes-organizando-suas-classes-e-bibliotecas/#acesso-aos-atributos-construtores-e-mtodos). 
	
## 2. Conceitos de programação:
 #### [Material de apoio](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/02-conceitos-de-programacao.pdf). 

## 3. Introdução de linguagem Java:
 #### [Material de apoio](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/03-introducao-linguagem-java.pdf).
   
## 4. Estrutura sequencial:
 #### [Material de apoio](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/04-estrutura-sequencial.pdf).
  
## 5. Introdução à Programação Orientada a Objetos:
 #### [Material de apoio](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/08-classes-atributos-membros-staticos.pdf).
 #### [Material de apoio II](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/09-construtores-this-sobrecarga-encapsulamento.pdf).

###   5.1. Classes:
 ####  - Toda classe em Java é uma subclasse da classe Object
  - É um tipo estruturado que pode conter (membros):
    - Atributos (dados/campos);
    - Métodos (funções/operações);
  - A Classe também pode prover muitos outros recursos, tais como:
    - Construtores;
    - Sobrecarga;
    - Encapsulamento;
    - Herança;
    - Polimorfismo;  
###   5.2. Membros estáticos:
  - Também chamados membros de classe.
    - Em oposição a membros e instância.
  - São membros que fazem sentido independentemente de objetos. Não precisam de objeto para serem chamados. São chamados a partir do próprio nome da classe.
  - Aplicações comuns:
    - Classes utilitárias.
    - Declaração de constantes.
###   5.3. Construtores:
 #### É uma operação especial da classe, que executa no momento da instanciação do objeto.
  - Usos comuns:
    - Iniciar valores dos atributos.
    - Permitir ou obrigar que o objeto receba dados / dependências no momento de sua instanciação (injeção de dependência).
  - Se um construtor customizado não for especificado, a classe disponibiliza o construtor padrão:
    - Product p = new Product();
  - É possível especificar mais de um construtor na mesma classe (sobrecarga). 
###   5.4. Palavra this:
 #### - É uma referência para o próprio objeto.
  - Usos comuns:
    - Diferenciar atributos de variáveis locais
    - Passar o próprio objeto como argumento na chamada de um método ou construtor  
###   5.5. Sobrecarga:
  - É um recurso que uma classe possui de oferecer mais de uma operação com o mesmo nome, porém com diferentes listas de parâmetros.  
###   5.6 Encapsulamento:
  - É um princípio que consiste em esconder detalhes de implementação de uma classe, expondo apenas operações seguras e que mantenham os objetos em um estado consistente.
  - Regra de ouro: o objeto deve sempre estar em um estado consistente, e a própria classe deve garantir isso.
###   5.7 Modificadores de acesso:
 - **private**: A única classe capaz de acessar os atributos, construtores e métodos privados é a própria classe. Classes, como conhecemos, não podem ser **private**, mas atributos, construtores e métodos sim.
 - **(nada)**:  Se nenhum modificador for utilizado, todas as classes do mesmo pacote têm acesso ao atributo, construtor, método ou classe.
 - **protected**: Aquilo que é **protected** pode ser acessado por todas as classes do mesmo pacote e por todas as classes que o estendam, mesmo que essas não estejam no mesmo pacote. Somente atributos, construtores e métodos podem ser **protected**.
 - **public**: Todos podem acessar aquilo que for definido como public. Classes, atributos, construtores e métodos podem ser public.
 - **final**: Evita que a classe seja herdada.
  
## 6. Comportamento de memoria, arrays e listas:
 #### [Material de apoio](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/10-memoria-arrays-e-listas.pdf).
 
### 6.1 Deslocação de memoria:
 - Objetos alocados dinamicamente, quando não possuem mais referência para eles, serão desalocados pelo garbage collector.
 - Variáveis locais são desalocadas imediatamente assim que seu escopo local sai de execução.
### 6.2 Vetores:
#### - Em programação, "vetor" é o nome dado a arranjos unidimensionais
  - Arranjo (array) é uma estrutura de dados:
  - Homogênea (dados do mesmo tipo)
  - Ordenada (elementos acessados por meio de posições)
  - Alocada de uma vez só, em um bloco contíguo de memória
### 6.3 Listas:
 #### - Lista é uma estrutura de dados:
- Homogênea (dados do mesmo tipo);
  - Ordenada (elementos acessados por meio de posições);
  - Inicia vazia, e seus elementos são alocados sob demanda;
  - Cada elemento ocupa um "nó" (ou nodo) da lista;
- Comandos:
  - _size()_ : Tamanho da lista;
  - _get(posição)_ : Obtem elemento na lista;
  - _add()_, _add(tipo,objeto)_ : Inserir elementos na lista;
  - _remove()_, _removeIf()_ : Remover elemento da lista;
  - _indexOf()_, _lastIndexOf()_ : Encontrar posição de elemento;
### 6.3 Matrizes:
 - "matriz" é o nome dado a arranjos bidimensionais
	
## 7 Enumerações, Composição:
#### [Material de apoio](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/13-enumeracoes-composicao).

### 7.1 Enumeração:
 - É um tipo especial que serve para especificar de forma literal um conjunto de constantes relacionadas.
###	7.2 Composição:
#### - É um tipo de associação que permite que um objeto contenha outro

## 8. Herança, Polimorfismo:
#### [Caelum](https://www.caelum.com.br/apostila-java-orientacao-objetos/heranca-reescrita-e-polimorfismo/).
###	8.1 Herança:
 - É um tipo de associação que permite que uma classe herde todos dados e comportamentos de outra
  - **Ex:** Podemos nos referir a um **Gerente** como sendo um _Funcionario_. Se alguém precisa falar com um _Funcionario_ do banco, pode falar com um **Gerente!** Porque? Pois **Gerente** é um _Funcionario_. Essa é a semântica da herança.
###	8.2 Polimorfismo "Muitas formas":
 - Polimorfismo é a capacidade de um objeto poder ser referenciado de várias formas. "Ao contrario do nome _"polimorfismo"_ não tem nada a ver com mudança, o objeto nasce de um tipo e **morre** daquele tipo"
### 8.3 Classes Abstratas:
 - São classes que não podem ser instanciadas.
 - É uma forma de garantir herança total: somente subclasses não abstratas podem ser instanciadas, mas nunca a superclasse abstrata.
### 8.4 Métodos abstratas:
 - São métodos que não possuem implementação.
 - Métodos precisam ser abstratos quando a classe é genérica demais para conter sua implementação.
 - Se uma classe possuir pelo menos um método abstrato, então esta classe também é abstrata.
 
## 9. Trabalhando com Date:
#### [Converter String para Date](https://www.alura.com.br/artigos/como-converter-string-para-date-em-java).

## 10. Interfaces:
#### [Caelum](https://www.caelum.com.br/apostila-java-orientacao-objetos/interfaces/16-interfaces).

## 11. Generics, Set, Map:
#### [Material de apoio](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/17-generics-set-map).

## 12. Programação Funcional e expressões lambda:
#### [Material de apoio](https://github.com/alissonpospor/JAVA/blob/master/material-de-apoio-do-curso/18-programacao-funcional-expressoes-lambda).

### 12.1 Predicate:
#### [Material de Apoio](https://docs.oracle.com/javase/8/docs/api/java/util/function/Predicate.html).
### 12.2 Consumer:
#### [Material de Apoio](https://docs.oracle.com/javase/8/docs/api/java/util/function/Function.html).
### 12.3 Function:
#### [Material de Apoio](https://docs.oracle.com/javase/8/docs/api/java/util/function/Consumer.html).
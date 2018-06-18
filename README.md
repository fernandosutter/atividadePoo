## Assinatura de método

A **assinatura** é o jeito de identificar um método de forma única. Em linguagens onde vários métodos podem ter o mesmo nome, você precisa ter uma outra forma de evitar a ambiguidade. O compilador precisa saber qual dos métodos com mesmo nome você está chamando. Então você precisa se valer de informações extras disponíveis no método para tomar uma decisão.

## Construtor

O **construtor** é definido como um método cujo nome deve ser o mesmo nome da **classe** e sem indicação do tipo de retorno nem mesmo **void**. O construtor é unicamente invocado no momento da criação do objeto através do operador **new**.

## Encapsulamento

**Encapsulamento** vem de encapsular, que em programação orientada a objetos significa juntar o programa em partes, o mais isoladas possível. A ideia é tornar o software mais flexível, fácil de modificar e de criar novas implementações.

## Escopo de classe

Refere-se aos limites de uma variável.

Ex:
```
int a = 10;  
for (int i = 0; i < 10; i++)   
{  
   System.out.println("Olá " + i + " " + a);   //ok, a existe dentro do for.
}  
System.out.println(a);  
System.out.println(i);  //Ops, i não existe aqui, só dentro do for.
```

## Escopo de objeto



## Getters/Setters

**GETTER** é quando vc quer pegar um valor, por exemplo um valor de um TextField.

**SETTER** é quando vc deseja setar ou enviar algo, algum valor.

Ex:
```
TextField nome = new TextField();
nome.setText("FULANO"); //aqui um exemplo de SETTER, que aplicará a string FULANO em NOME.
TextField trazNome = new TextField();
traznome.setText(nome.getText()); //exemplo de GETTER, que retornara o valor digitado em NOME
```
## Instanciação

A **instanciação** é um processo por meio do qual se realiza a cópia de um objeto (classe) existente. Uma classe, a qual tem a função de determinar um tipo de dado, deve ser instanciada para que possamos utilizá-la.

## Palavra reservada final

A **palavra reservada final** (minusculo, java e case sensitive) serve para dizer que a "coisa" é final ou seja, o que foi decidido não pode ser modificado. Isto é diferente de constante. Em java não ha constantes, ha variáveis que só podem ser modificadas 1 vez.

## Palavra reservada instanciof

**Instanceof**: Determina se um objeto é a instancia de uma classe, superclasse ou interface.

## Palavra reservada new

 **New**: Usada para instanciar um objeto.
 
 Ex:
 ```
 TextField nome = new TextField();
 ```

## Palavra reservada public/private

**Private**: Faz com que um método ou variável possa ser acessado somente de dentro da própria classe.       

**Public**: Faz com que uma classe, método ou variável possa ser acessado a partir de qualquer outra classe.

## Palavra reservada this

**This**: Variável de referência que diz respeito a instancia atual de um objeto.

## Relacionamento de Agregação

A **agregação** representa um vínculo fraco entre duas classes, ou seja, a classe FILHA faz sentido mesmo se a classe PAI deixar de existir. Se a classe PAI for apagada, a classe FILHA continuará existindo sem problemas.

![UML Agregação](http://www.cleibsonalmeida.blog.br/site/wp-content/uploads/2012/08/uml_agregacao.gif)

## Relacionamento de Composição

A **composição** representa um vínculo forte entre duas classes, ou seja, uma classe FILHA só faz sentido se uma classe PAI existir. Se a classe PAI for apagada, a classe FILHA automaticamente deixará de existir.

![UML Composição](http://www.cleibsonalmeida.blog.br/site/wp-content/uploads/2012/08/uml_composicao.gif)

## Relacionamento de dependência

Na UML, um **relacionamento de dependência** é um relacionamento no qual um elemento, o cliente, usa ou depende de outro elemento, o fornecedor. Você pode usar os relacionamentos de dependência nos diagramas de classe, diagramas de componentes, diagramas de implementação e diagramas de caso de uso para indicar que uma alteração para o fornecedor deve exigir uma alteração para o cliente.

## Sobrecarga de método

**Sobrecarga de método** permite a existência de vários **métodos** de mesmo nome, porém com assinaturas levemente diferentes ou seja variando no número, tipo de argumentos, no valor de retorno e até variáveis diferentes.

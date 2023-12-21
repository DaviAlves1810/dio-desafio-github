
## **Objetos**

Os objetos são uma estrutura de dados fundamental e desempenham um papel central na linguagem. Eles são usados para representar e armazenar dados de maneira estruturada, e suas propriedades podem conter valores de vários tipos, incluindo números, strings, funções e até mesmo outros objetos.

Você pode criar objetos em JavaScript de várias maneiras. A forma mais comum é usando a sintaxe de objeto literal:

![[Pasted image 20231213153902.png|290]]

Os objetos podem ser dinamizados quando são utilizadas as [[Classes e Instâncias]]. Podemos chamar de "método" funções dentro do objeto como "**saudacao**"; nesse caso, toda vez que digitarem "saudacao()", o console imprimirá a palavrá "Olá!".


### **Métodos**


Um método em JavaScript é uma função que está associada a um objeto. A sintaxe básica para definir um método dentro de um objeto é atribuir uma função a uma propriedade do objeto.

![[Pasted image 20231213183519.png]]


Você pode chamar um método usando a notação de ponto.

![[Pasted image 20231213183708.png]]

Exemplo prático:

![[Pasted image 20231213183825.png]]

Neste exemplo, `acelerar` é um método do objeto `carro`. Quando chamamos `carro.acelerar()`, a função associada a `acelerar` é executada.

Lembre-se de que a palavra-chave `this` é usada dentro de métodos para se referir ao próprio objeto ao qual o método pertence.
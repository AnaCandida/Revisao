 
## Programação orientada a objetos - POO

Programação orientada a objetos: é um **paradigma de programação** que modela os dados e comportamentos como se fossem objetos do mundo real

Pyton é multi-paradigma com suporte nativo à **POO**, como outas:C++, C#, .NET, Java, Object Pascal, Objective-C, SuperCollider, Ruby e Smalltalk.

### Poo serve para:
 - organizar o código;
-  re-utilização de código em contextos semelhantes.
- 

## Objetos
São criados/instanciados pelas CLASSES. Possuem dois elementos:
1. ***Propriedades/atributos*** Ex: ligado/desligado, canal, canal máximo/mínimo, volume, volume máximo/mínimo
2. ***Comportamentos*** Ex: mudar canal/volume para cima/baixo, ligar/desligar▹
	

## Classes

 - ***Construtor***: init -> um método especial que inicializa o objeto e define a sua estrutura (seus atributos) durante o processo de instanciação. Dentro do método construtor que declaramos aos atributos do objeto

 - **Métodos***: Para representar métodos em Python usamos uma sintaxe semelhante à de uma função, com algumas diferenças: 1)o método deve ser declarado no contexto da classe, 2) o método deve ter, **obrigatóriamente o parâmetro self** `self` que é é a palavra Python que representa uma referência para o objeto atual
```
class Pessoa:
    def __init__(self, nome, idade): ## construtor + paramêtros
        self.nome = nome
        self.idade = idade
	
	def falar(self,mensagem): método + paramêtros
		print(mensagem)
```

São estruturas usadas para definir um novo tipo de dados (criado pela programadora).
Classes descrevem o que um objeto vai ser e se comportar, mas elas não criam o objeto em si.

## Herança
## Polimorfismo
## Abstratas 



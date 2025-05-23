### O que é um Sistema de Controle de Versão (VCS)?

O Sistema de Controle de Versão (VCS) é um sistema que gerencia e monitora as mudanças em um sistema de arquivos ao decorrer de um projeto. Ele registra todas as modificações que são feitas nos arquivos, isso permite que os desenvolvedores consigam acompanhar as alterações feitas pelos outros usuarios, restaurar versões anteriores e trabalhar em conjunto de forma mais eficiente. A medida que os ambientes de desenvolvimento de softwares aceleraram, os VCS ajudam as equipes de software a trabalhar de forma mais veloz e funcional. O VCS protege o código-fonte tanto de catástrofes quanto
da degração casual causada por erros humanos e consequências nao intencionais. Equipes de software que não utilizam nenhuma forma de VCS frenquentemente enfrenta problemas como a falta de noção de sobre quais mudanças feitas no código estão disponíveis para os usúarios ou a criação de alterações incompatíveis entre dois trabalhos não relacionados.

## Vantagens de usar um Sistema de Controle De Versão

## Exemplos de Sistema de Controle de Versão

Git  
Mercurial  
SubVersion




# O que é POO (Programação Orientada a Objetos)

A Programação Orientada a Objetos (POO) é um modelo de programação que organiza seu código em volta de objetos, esse modelo permite a simplificação de programas complexos dividindo-os em unidades chamadas de "objetos", cada objeto é uma entidade autônoma, pois possui atributos e comportamentos independentes. Ou seja, cada objeto é uma entidade única, com atributos e ações específicas para ele. Além disso o POO possui 4 pilares: abstração, encapsulamento, herança e polimorfismo, tornando a programação mais organizada e eficiente.Comparada a modelos de programação mais tradicionais, como a programação procedural, a POO oferece uma perspectiva e prática de programação mais organizada e escalável para o desenvolvimento de software. Enquanto a programação procedural se concentra em funções e na sequência de execução de tarefas, a POO agrupa tarefas (métodos) com os dados que manipulam (objetos), resultando em um código mais intuitivo e adaptável. A modularidade da POO também se traduz em uma colaboração mais eficiente entre os desenvolvedores. Em grandes equipes, diferentes grupos podem trabalhar em módulos separados sem interferir no trabalho uns dos outros em nenhum momento. Em ambientes de desenvolvimento ágil, onde várias iterações e revisões são comuns, essa eficiência na colaboração faz toda a diferença.


## Abstração
A abstração é um dos pilares da Programação Orientada a Objetos que envolve a identificação e a modelagem das características e comportamentos essenciais de um objeto, ignorando os detalhes irrelevantes ou secundários para o contexto em questão.

#### Exemplo: Uma classe abstrata "FormaGeometrica" define um método abstrato "calcularArea". Classes filhas como "Circulo", "Retangulo" e "Triangulo" herdam o método da classe "FormaGeometrica" e implementam o método "calcularArea" de acordo com suas formas específicas. 

## Encapsulamento

Em POO, o encapsulamento é um dos pilares que  envolve esconder os detalhes internos de uma classe e controlar o acesso aos seus atributos e métodos. Isso é feito através da definição de níveis de acesso (público, protegido, privado) e da utilização de métodos  para controlar a interação com os atributos. 

#### Exemplo: Um personagem de jogo tem vida, energia, pontos, etc. O encapsulamento garante que apenas métodos específicos podem alterar esses valores, evitando trapaças e erros no jogo. 

## Herança
Em POO, a herança é um mecanismo que permite que uma classe filha herde atributos e métodos de uma classe pai. Este mecanismo promove a reutilização de código e a organização do código em uma hierarquia de classes.

#### Exemplo: Uma classe pai chamada "Pessoa" define atributos genéricos como nome, idade e endereço, e métodos como "exibirInformacoes" e "alterarInformacoes". Classes filhas como "Aluno", "Professor" e "Funcionario" herdam da classe "Pessoa" seus métodos e atributos.

## Polimorfismo
O polimorfismo, em Programação Orientada a Objetos (POO), permite que objetos de classes diferentes respondam a um mesmo método de forma diferente, dependendo da sua classe. É como se um comando  pudesse ter diferentes interpretações dependendo do objeto que o recebe.

#### Exemplo: Imagine uma classe Animal com um método emitirSom(). Classes filhas como Cachorro e Gato podem sobrescrever este método para emitir sons específicos (latido e miado, respetivamente).

## 5 Vantagens do POO

### 1. Facilidade de Manuntenção
### 2. Reutilização de Código
### 3. Escalabilidade
### 4. Modelagen Intuitiva
### 5. Colaboração Eficiente

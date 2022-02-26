# Casos de Uso

## 1. Introdução

Os casos de usos é uma das formas de detalhar a comunicação entre um determinado sistema e seus usuários (atores). Os casos de uso devem prover um resultado observável e de valor para os atores e/ou interessados no sistema.

## 2. Diagrama de caso de uso UML

Através da linguagem de modelagem (UML), o diagrama de caso de uso é uma forma de detalhar a comunicação entre um determinado sistema e seus usuários (atores), e para criar um, deve-se utilizar de um conjunto de símbolos e conectores específicos.

Deve-se utilizar um ou mais diagramas de caso de uso quando for necessário dar uma visão geral do relacionamento entre casos de uso, atores e sistema. E é muito indicado para complementar um caso de uso descrito em texto.

## 3. Elementos do diagrama de caso de uso

- **Caso de Uso:** é representado por uma forma oval rotulada. E são os diferentes usos que um usuário pode possuir, estruturando assim o diálogo entre os participantes e o sistema.
- **Atores:** são os usuários que interagem com o sistema. Um ator pode ser uma usuário do sistema ou atá mesmo um outro sistema que interage com o seu sistema. É representado por um boneco palito.
- **Sistema:** sequência específica de ações, interações e comportamento entre os atores, sistemas e metas. Para a representação do sistema é desenhado um retângulo em torno dos casos de uso.
- **Metas:** resultado final da maioria dos casos de uso.

## 4. Relacionamentos

Os relacionamentos são usados para representar as interações entre os atores e os casos de uso do sistema.

### 4.1 Inclusão (Include)

Mostra a dependência entre um caso de uso base e um caso de uso incluído, sempre que uma caso de uso base é realizado o caso incluído também é realizado.

<center>
<figure>
  <img width="300" src="../../assets/img/casos_de_uso/include.png" />
  <figcaption>Figura 1: Exemplo de relacionamento include (inclusão).</figcaption>
</figure>
</center>

### 4.2 Extensão (extend)

É usado para mostrar o comportamento opcional, comportamento que é executado sobre algumas condições.

<center>
<figure>
  <img width="300" src="../../assets/img/casos_de_uso/extend.png" />
  <figcaption>Figura 2: Exemplo de Relacionamento extend (extensão).</figcaption>
</figure>
</center>

### 4.3 Herança ou Generalização (generalization)

É a generalização entre um caso de uso e outro, em que um caso de uso é especialização de outro. É representado por uma seta de generalização partindo de um caso para o outro.

<center>
<figure>
  <img width="300" src="../../assets/img/casos_de_uso/generalization.png" />
  <figcaption>Figura 3: Exemplos de Relacionamento generalization (herança).</figcaption>
</figure>
</center>
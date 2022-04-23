# Casos de Uso

## 1. Introdução

<p align="justify">
Os casos de usos é uma das formas de detalhar a comunicação entre um determinado sistema e seus usuários (atores). Os casos de uso devem prover um resultado observável e de valor para os atores e/ou interessados no sistema.
</p>

## 2. Diagrama de caso de uso UML

<p align="justify">
Através da linguagem de modelagem (UML), o diagrama de caso de uso é uma forma de detalhar a comunicação entre um determinado sistema e seus usuários (atores), e para criar um, deve-se utilizar de um conjunto de símbolos e conectores específicos.
</p>
<p align="justify">
Deve-se utilizar um ou mais diagramas de caso de uso quando for necessário dar uma visão geral do relacionamento entre casos de uso, atores e sistema. E é muito indicado para complementar um caso de uso descrito em texto.
</p>

## 3. Elementos do diagrama de caso de uso

- **Caso de Uso:** é representado por uma forma oval rotulada. E são os diferentes usos que um usuário pode possuir, estruturando assim o diálogo entre os participantes e o sistema.
- **Atores:** são os usuários que interagem com o sistema. Um ator pode ser um usuário do sistema ou até mesmo de um outro sistema que interage com o seu sistema. É representado por um boneco palito.
- **Sistema:** sequência específica de ações, interações e comportamento entre os atores, sistemas e metas. Para a representação do sistema é desenhado um retângulo em torno dos casos de uso.
- **Metas:** resultado final da maioria dos casos de uso.

## 4. Relacionamentos

<p align="justify">
Os relacionamentos são usados para representar as interações entre os atores e os casos de uso do sistema.
</p>

### 4.1 Inclusão (Include)

<p align="justify">
Mostra a dependência entre um caso de uso base e um caso de uso incluído, sempre que uma caso de uso base é realizado o caso incluído também é realizado.
</p>

<center>
<figure>
  <img width="300" src="../../assets/img/casos_de_uso/include.png" />
  <figcaption>Figura 1: Exemplo de relacionamento include (inclusão).</figcaption>
</figure>
</center>

### 4.2 Extensão (extend)

<p align="justify">
É usado para mostrar o comportamento opcional, comportamento que é executado sobre algumas condições.
</p>

<center>
<figure>
  <img width="300" src="../../assets/img/casos_de_uso/extend.png" />
  <figcaption>Figura 2: Exemplo de Relacionamento extend (extensão).</figcaption>
</figure>
</center>

### 4.3 Herança ou Generalização (generalization)

<p align="justify">
É a generalização entre um caso de uso e outro, em que um caso de uso é especialização de outro. É representado por uma seta de generalização partindo de um caso para o outro.
</p>

<center>
<figure>
  <img width="300" src="../../assets/img/casos_de_uso/generalization.png" />
  <figcaption>Figura 3: Exemplos de Relacionamento generalization (herança).</figcaption>
</figure>
</center>

## 5. Diagramas UML

### 5.1 Fluxo de conta

<center>
<figure>
  <img width="100%" src="../../assets/img/casos_de_uso/Fluxo_novo_assinante.png" />
  <figcaption>Figura 4: Fluxo de Conta.</figcaption>
</figure>

| Caso 01 - Fluxo de conta | Informações | 
| ------- | ----------- |
| Descrição | <ul><li>O usuário deve ser capaz de criar uma conta</li><li>O usuário deve ser capaz de acessar uma conta já existente</li></ul> |
| Pré-condições | Acesso à internet |
| Atores | Usuário, Cliente |
| Ação | <ul><li>O usuário cria uma conta utilizando seus dados</li><li>O usuário deve ser capaz de acessar sua conta com login e senha </li></ul> |
| Fluxo principal | <ul><li>O usuário acessa o prime video</li><li>O usuário seleciona a opção de criar uma conta ou entrar em uma já existente</li></ul> |
| Pós-condições | O usuário poderá navegar na aplicação |

</center>

### 5.2 Fluxo de conteúdo

<center>
<figure>
  <img width="100%" src="../../assets/img/casos_de_uso/Fluxo_assistir_conteudo.png" />
  <figcaption>Figura 5: Fluxo de conteúdo.</figcaption>
</figure>

| Caso 02 - Fluxo de conteúdo | Informações | 
| ------- | ----------- |
| Descrição | O usuário deve ser capaz de assistir um título |
| Pré-condições | Internet, uma conta válida e um título |
| Ator | Perfil |
| Ação | O usuário assiste um título |
| Fluxo principal | <ul><li>O usuário deve selecionar um título</li><li>O usuário deve assistir um título</li></ul> |
| Pós-condições | <ul><li>O usuário poderá realizar operações no título</li><li>O usuário poderá navegar na página do título selecionado</li></ul>|

</center>

### 5.3 Fluxo de conteúdo extra

<center>
<figure>
  <img width="100%" src="../../assets/img/casos_de_uso/Fluxo_Conteudo_extra.png" />
  <figcaption>Figura 6: Fluxo de conteúdo extra.</figcaption>
</figure>

| Caso 03 - Fluxo de conteúdo extra | Informações | 
| ------- | ----------- |
| Descrição | O usuário deve ser capaz de assinar conteúdos extras |
| Pré-condições | Possuir uma conta da Amazon Prime Video |
| Ator | Assinante, Amazon |
| Ação | O usuário irá contratar novas assinaturas para ter acesso a conteúdo extra |
| Fluxo principal | <ul><li>O usuário irá escolher um conteúdo extra</li><li>O usuário seleciona a opção forma de pagamento</li><li>O usuário fornece seus dados</li><li>A Amazon confirmará o pagamento</li><li>O usuário terá acesso ao novo conteúdo</li></ul> |
| Pós-condições | O usuário terá acesso ao conteúdo contratado |

</center>

## 6. Referências

Diagrama de caso de uso UML: o que é, como fazer e exemplos. Disponível em: <https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>. Acesso em: 26 de fev. de 2022.

PIMENTEL, Andrey Ricardo. Projeto de Software Usando a UML. 2007.

## 7. Histórico de Versionamento

|Versão|Data de modificação|Descrição da modificação|Autor|Revisor|
|-|-|-|-|-|
|1.0|26/02/2022|Criação do documento de casos de uso|[Antonio Igor](https://github.com/antonioigorcarvalho) e [Lameque Fernandes](https://github.com/lamequefernandes)||
|1.1|26/02/2022|Adição dos diagramas e tabelas|[Antonio Igor](https://github.com/antonioigorcarvalho) e [Lameque Fernandes](https://github.com/lamequefernandes)||

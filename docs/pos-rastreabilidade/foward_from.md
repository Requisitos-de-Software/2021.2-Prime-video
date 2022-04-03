# Foward-From

## 1. Introdução

<p align="justify">
  A Rastreabilidade forward-from (para frente, a partir de), trata da ligação entre os requisitos, artefatos de desenho e implementação (Sayão e Leite. Rastreabilidade de Requisitos. ISSN 0103-9741). 
</p>

## 2. Metodologia

<p align="justify">
  Existem na literatura, várias ferramentas e propostas para dar suporte ao processo de rastreabilidade, porém optamos por utilizar o Meta-Modelo de Toranzo em conjunto com a Matriz de Rastreabilidade. 
</p>

<p align="justify">
  Matriz de rastreabilidade de requisitos é uma ferramenta que explicita a relação direta dos requisitos entre si ou com os outros componentes do projeto. Assim, caso alguma alteração seja feita no projeto, sabe-se quais requisitos serão afetados com tal mudança [1].
</p>

<p align="justify">
  Em sua proposta para melhoria da rastreabilidade entre requisitos, Toranzo [2] propõe a classificação das informações a serem rastreadas em meta-modelo para auxiliar no rastreamento do requisito, além de um metamodelo intermediário e um processo de rastreabilidade. 
</p>

<p align="justify">
  Dessa forma, tendo em vista a grande disponibilidade de recursos na literatura sobre o uso do modelo de Toranzo [2] e Matriz de Rastreabilidade, decidimos então adota-los para guiar a criação deste documento.
</p>

## 3. Requisitos Funcionais

<p align="justify">
  
</p>

<center>

#### Tabela 1: Níveis de classificação definidos no Meta-modelo de Toranzo

| Categoria | Definição |
|:---------:|:---------:|
|Ambiental|Informações oriundas do contexto no qual a organização está inserida.|
|Organizacional|Informações pertencentes à organização (missão, objetivos e estratégias).|
|Gerencial|Informações que auxiliam a gerência do projeto.|
|Desenvolvimento|Informações associadas aos diversos artefatos gerados ao longo do processo de desenvolvimento (artefatos de requisitos, diagramas, códigos, casos de teste e outros).|

<figcaption> Fonte:  Sayão e Leite. Rastreabilidade de Requisitos. ISSN 0103-9741 </figcaption>

</center>

<br/><br/>

<center>

#### Tabela 2: Listagem dos requisitos funcionais

| Requisito | Épico | História de Usuário | Cenário | Léxico | Caso de Uso | Categoria |
| --------- | ----- | -- | ------- | ------ | ------------ | ----- |
| RF01 - O usuário deve conseguir visualizar os termos e aviso de privacidade |      |    |         |        |             |         |
| RF02 - O usuário deve ter a opção de ocultar uma serie/filme da sua tela inicial |       |    |         |        |             |         |
| RF03 - O usuário deve poder remover títulos da sua lista	 |   Épico 1 - Conta    |  US09  |    C04     |  L - 21 Explorar, L - 33 Originals, L - 49 Watch Party   |      Caso 2 - Fluxo de conteúdo       |         |
| RF04 - O usuário deve ser capaz de comprar conteúdo extra	 |   Épico 2 - Perfil   |  US23  |    C05     |    L - 34 Pedidos    |      Caso 03 - Fluxo de conteúdo extra       |         |
| RF05 - O usuário deve ser capaz de registrar seu feedback sobre titulo	 |   Épico 3 - Conteúdo    |  US50 e US52   |    C05     |  L - 03 Alugar, L - 07 Canais e L - 30 Loja   |      Caso 03 - Fluxo de conteúdo extra       |         |
| RF06 - O usuário deve poder acessar a página de ajuda da plataforma |   Épico 3 - Conteúdo    |  US26  |    ---     |    L - 02 Ajuda   |      ---       |         |
| RF07 - O usuário deve ser capaz de passar para o proximo episódio ainda na reprodução do atual |   Épico 3 - Conteúdo   |  US27  |   C03   |    ---    |      Caso 2 - Fluxo de conteúdo       |         |
| RF08 - O usuário deve poder escolher qual episódio assistir de um título |   Épico 3 - Conteúdo   |  US32  |    C03     |    L - 04 Assistir, L - 16 Documentário, L - 22 Extra, L - 44 Série e L - 49 Watch Party    |      Caso 02 - Fluxo de conteúdo       |         |
| RF09 - O usuário deve ser capaz de desabilitar a reprodução automática |   Épico 3 - Conteúdo    |  US31 e US34  |    C03     |   L - 04 Assistir     |      Caso 02 - Fluxo de conteúdo       |         |
| RF10 - O usuário deve ser capaz de visualizar títulos recomendados |   Épico 3 - Conteúdo    |  US38  |    C04     |    L - 36 Recomendado    |      Caso 02 - Fluxo de conteúdo       |         |
| RF11 - O usuário deve ser capaz de assistir ao trailer dos títulos |       |    |         |        |             |         |
| RF12 - O usuário deve ser capaz de pular a abertura dos titulos |       |    |         |        |             |         |
| RF13 - O usuario deve conseguir ver quais filmes/series ele assistiu anteriormente |       |    |         |        |             |         |
| RF14 - O usuário deve poder escolher qual temporada assistir de um título |       |    |         |        |          |            |
| RF15 - O usuário deve poder adicionar novos perfis à sua conta |       |    |         |        |             |         |
| RF16 - O usuário deve poder editar seu avatar ou nome de perfil |       |    |         |        |             |         |
| RF17 - O usuário deve poder adicionar títulos à sua lista |       |    |         |        |             |         |
| RF18 - O usuário deve ter a opção de realizar uma busca |       |    |         |        |             |         |
| RF19 - O usuário deve poder filtrar a sua busca |       |    |         |        |             |         |
| RF20 - O usuário deve ter a opção de alterar os meios de pagamento | Épico 3 - Conteúdo | US10 |         |        | --- |         |
| RF21 - O usuário deve ser capaz de baixar os títulos | Épico 3 - Conteúdo | US24 |         |        | --- |         |
| RF22 - O usuário deve ser capaz de escolher o idioma de áudio | Épico 3 - Conteúdo | US36 |         |        | --- |         |
| RF23 - O usuário deve ser capaz de escolher o idioma da legenda | Épico 3 - Conteúdo | US37 |         |        | --- |         |
| RF24 - O usuário deve ser capaz de tirar a legenda | Épico 3 - Conteúdo | US42  |         |        | Caso 2 - Fluxo de conteúdo |         |
| RF25 - O usuário deve poder escolher a qualidade do vídeo | Épico 3 - Conteúdo | US42 |  |  | --- |         |
| RF26 - O usuário deve poder usar a opção de tela cheia | Épico 3 - Conteúdo | US42 |  |  | Caso 2 - Fluxo de conteúdo |         |
| RF27 - O usuário deve poder realizar login na plataforma | Épico 1 - Conta | US12 |  |  | Caso 1 - Fluxo de conta |         |
| RF28 - O usuário deve poder realizar logout na plataforma | Épico 1 - Conta | US13 |  |  | Caso 1 - Fluxo de conta |         |
| RF29 - O usuário pode excluir perfis | Épico 1 - Conta | US21 |  |  | Caso 1 - Fluxo de conta |         |
| RF30 - O usuário pode usar o Watch party | Épico 3 - Conteúdo | US25 |  |  | --- |         |
| RF31 - O usuário pode pode alugar canais, filmes e series | Épico 3 - Conteúdo  | US51 |  |  | Caso 3 - Fluxo de conteúdo extra |         |
| RF32 - O usuário pode pode ocultar vídeos | Épico 3 - Conteúdo | US45 |  |  | Caso 2 - Fluxo de conteúdo |         |
| RF33 - O usuário pode desvincular os dispositivos | Épico 1 - Conta  | US17 |  |  | --- |         |
| RF34 - O usuário pode excluir historico de navegação |  |    |  |  | --- |         |
| RF35 - O usuário pode ver informações dos atores | Épico 1 - Perfil | US44 |  |  | Caso 2 - Fluxo de conteúdo |         |
| RF36 - O usuário pode diminuir o consumo de dados | --- | --- |  |  | --- |         |
| RF37 - O usuário pode ver detalhes da obra | --- | --- |  |  | Caso 2 - Fluxo de conteúdo |         |
| RF38 - O usuário deve conseguir acessar um título pelo nome completo ou apenas parte dele | Épico 3 - Conteúdo | US49 |  |  | Caso 2 - Fluxo de conteúdo |         |
| RF39 - O usuário deve poder criar um perfil infantil | Épico 1 - Perfil | US18 |  |  | Caso 1 - Fluxo de conta |         |

<figcaption>Fonte: Próprio autor</figcaption>

</center>

## 4. Referências

> Sayão, Miriam. Leite, Julio Cesar Sampaio do Prado. Rastreabilidade de Requisitos. ISSN 0103-9741. Disponível em: <https://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf>. Acesso em: 02 abril 2022.

> [1] Matriz de Rastreabilidade de Requisitos: saiba como gerenciar as mudanças no escopo. Disponível em: <https://artia.com/blog/matriz-de-rastreabilidade/>. Acesso em: 02 abril 2022.

> [2] Antonio Carlos Souza; Caio Dias; Márcio Macedo. AADSP: Gerencia de Requisitos - São Paulo/SP - Ed. Ixtlan, Agosto/2018. ISBN: 978-85-8197-689-1. Disponível em: <https://labrasoft.ifba.edu.br/assets/files/pdf/Livro_AADSP.pdf>. Acesso em: 02 abril 2022.

## 5. Histórico de Versionamento

| Data | Versão | Descrição | Autores | Revisor |
| :--: | :----: | :-------: | :-------: | :-------: |
| 02/04/2022  | 1.0 | Criação do documento de Pós-Rastreabilidade Foward-from |  | a definir |
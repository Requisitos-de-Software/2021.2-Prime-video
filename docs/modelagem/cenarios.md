# Cenários

## 1. Introdução

<p align='justify'>
    &emsp; A criação de cenários é uma importante etapa do processo de modelagem de requisitos. Os cenários são representações de ações que podem ser realizadas pelos usuários dentro do sistema. São utilizados principalmente para se compreender as principais interações presentes na inteface ou no sistema.
</p>


## 2. Metodologia

<p align='justify'>
    &emsp; Cada cenário presente neste documento possuirá os seguintes elementos característicos:
    <ul>
        <li><strong>Título:</strong> Breve descrição da tarefa a ser realizada
        <li><strong>Contexto:</strong> Detalhamento da ação realizada pelos atores.
        <li><strong>Atores:</strong> São as pessoas que vão interagir com o sistema e realizar as tarefas/ações.
        <li><strong>Objetivo:</strong> O que o ator espera conseguir realizando a ação.
        <li><strong>Recursos:</strong> Tudo aquilo que deve ser utilizado pelo ator para que ele possa realizar a tarefa.
        <li><strong>Episódios:</strong> Passo a passo de como o cenário será feito.
        <li><strong>Exceção:</strong> São acontecimentos que impedem a realização da ação pelo usuário.
    </ul>
</p>




## 3. Cenários

### C01

<table>
        <tr>
            <th colspan="2" style="text-align:center">Criação de Perfil</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Página Inicial;<br>
            -Pré Condição: Estar logado na plataforma, assinatura ativa no Amazon Prime.</td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Assinantes</td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Criar um novo perfil para sua conta</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Assinante loga na sua conta;<br>
            -Assinante clica em "Adicionar novo Perfil";<br>
            -Assinante escolhe o nome e a foto do perfil;<br>
            -Assinante define se o perfil é infantil ou não;<br>
            -Assinante salva as alterações.
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet.
            </td>
        </tr>
</table>

### C02

<table>
        <tr>
            <th colspan="2" style="text-align:center">Busca por Título</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Página Inicial;<br>
            -Pré Condição: Estar logado na plataforma.</td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>-Assinantes;<br>
            -Não Assinantes.
            </td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Encontrar um título diretamente pelo seu nome</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Usuário acessa o Prime Video;<br>
            -Usuário clica na lupa no canto superior direito;<br>
            -Usuário digita o nome do título que deseja visualizar.
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet;<br>
            -Usuário se esquece do nome do título.
            </td>
        </tr>
</table>


### C03

<table>
        <tr>
            <th colspan="2" style="text-align:center">Assistir Título</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Página Inicial ou página de visualização do título;<br>
            -Pré Condição: Estar logado na plataforma, assinatura ativa no Amazon Prime.</td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Assinantes
            </td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Assistir algum título da escolha do assinante</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Assinante acessa o Prime Video;<br>
            -Assinante escolhe qual título deseja assistir;<br>
            -Assinante clica no título para poder assistí-lo.
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet ou conexão lenta;<br>
            -Assinante escolhe um título que não faz parte do seu pacote.
            </td>
        </tr>
</table>

### C04

<table>
        <tr>
            <th colspan="2" style="text-align:center">Minha Área</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Página Inicial;<br>
            -Pré Condição: Estar logado na plataforma, assinatura ativa no Amazon Prime.</td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Assinantes
            </td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Poder ter acesso rápido e fácil aos títulos para assistir mais tarde.</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Assinante acessa o Prime Video;<br>
            -Assinante escolhe qual título deseja adicionar à sua lista;<br>
            -Assinante clica no botão "Adicionar à sua lista".<br>
            -Assinante clica em "Minha Área" no canto superior esquerdo;<br>
            -Assinante acessa sua área e escolhe qual título deseja visualizar.
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet.
            </td>
        </tr>
</table>

### C05

<table>
        <tr>
            <th colspan="2" style="text-align:center">Alugar Conteúdo Extra</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Página Inicial;<br>
            -Pré Condição: Estar logado na plataforma, assinatura ativa no Amazon Prime.</td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Assinantes
            </td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Assistir conteúdos que não estão disponíveis apenas com a assinatura do Prime Video.</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Assinante acessa o Prime Video;<br>
            -Assinante clica em "Loja" no canto superior esquerdo;<br>
            -Assinante clica no botão "Alugar Título";<br>
            -Assinante escolhe o meio de pagamento.
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet;<br>
            -Meio de pagamento inválido.
            </td>
        </tr>
</table>

### C06

<table>
        <tr>
            <th colspan="2" style="text-align:center">Assinar Canais Extra</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Página Inicial;<br>
            -Pré Condição: Estar logado na plataforma, assinatura ativa no Amazon Prime.</td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Assinantes
            </td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Assistir conteúdos de outro canal ou plataforma de streaming</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Assinante acessa o Prime Video;<br>
            -Assinante clica em "Canais" no canto superior esquerdo;<br>
            -Assinante escolhe qual canal deseja assinar;<br>
            -Assinante escolhe o meio de pagamento.
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet;<br>
            -Meio de pagamento inválido.
            </td>
        </tr>
</table>

### C07

<table>
        <tr>
            <th colspan="2" style="text-align:center">Alterar Meio de Pagamento</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Tela de configurações da Amazon;<br>
            -Pré Condição: Estar logado na plataforma, assinatura ativa no Amazon Prime.</td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Assinantes
            </td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Assinante deseja mudar sua forma de pagamento</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video;<br>
            -Meio de pagamento válido.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Assinante acessa o Prime Video;<br>
            -Assinante clica no seu perfil no canto superior direito;<br>
            -Assinante clica no botão "Conta e configurações";<br>
            -Assinante loga com sua conta da Amazon;<br>
            -Assinante clica em alterar meio de pagamento;<br>
            -Assinante seleciona uma nova forma de pagamento.
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet;<br>
            -Meio de pagamento inválido.
            </td>
        </tr>
</table>

### C08 

<table>
        <tr>
            <th colspan="2" style="text-align:center">Reprodução Automática</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Tela de configurações da Amazon;<br>
            -Pré Condição: Possuir Assinatura ativa no Amazon Prime.</td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Assinantes
            </td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Poder habilitar ou desabilitar a reprodução automática.</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Assinante acessa o Prime Video;<br>
            -Assinante clica no seu perfil no canto superior direito;<br>
            -Assinante clica no botão "Conta e configurações";<br>
            -Assinante clica na aba "Reprodutor";<br>
            -Assinante escolhe a opção do "Auto Play".
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet.
            </td>
        </tr>
</table>

### C09

<table>
        <tr>
            <th colspan="2" style="text-align:center">Realizar Logout</th>
        </tr>
         <tr>
            <td>Contexto</td>
            <td>-Local: Página Inicial;<br>
            -Pré Condição: Estar logado na plataforma, assinatura ativa no Amazon Prime.
            </td>
        </tr>
        <tr>
            <td>Atores</td>
            <td>Assinantes
            </td>
        </tr>
        <tr>
            <td>Objetivo</td>
            <td>Realizar logout na plataforma</td>
        </tr>
        <tr>
            <td>Recursos</td>
            <td>-Dispositivo com acesso à internet;<br>
            -Dispositivo suportado pelo Prime Video.
            </td>
        </tr>
        <tr>
            <td>Episódios</td>
            <td>-Assinante acessa o Prime Video;<br>
            -Assinante clica no seu perfil no canto superior direito;<br>
            -Assinante clica na opção "Sair".
            </td>
        </tr>
        <tr>
            <td>Exceção</td>
            <td>-Queda de energia;<br>
            -Perda de conexão com a internet.
            </td>
        </tr>
</table>


## 4. Referências

Barbosa, S. D. J.; Silva, B. S. da; Silveira, M. S.; Gasparini, I.; Darin, T.; Barbosa, G. D. J. (2021);Interação Humano-Computador e Experiência do usuário.

SERRANO, Milene; SERRANO, Maurício. Requisitos - Aula 10.


## 5. Histórico de Versionamento

|Versão|Data de modificação|Descrição da modificação|Autor|Revisor|
|-|-|-|-|-|
|1.0|25/02/2022|Criação do documento de cenários|[Caio Santos](https://github.com/caiobsantos)|-|
|1.1|01/03/2022|Adição dos cenários|[Caio Santos](https://github.com/caiobsantos)|-|
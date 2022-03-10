# NFR Framework

## 1. Introdução

<p align='justify'>
    &emsp; O NFR Framework é uma abordagem orientada a processos, onde os requisitos não-funcionais são explicitamente representados como metas a serem obtidas (CHUNG, 1995). Eles estão relacionados com o comportamento de um sistema e descrevem como o sistema faz e não o que faz.
O NFR Framework explicitam relacionamentos entre os requisitos que, inicialmente, não eram observados, para obter prioridades entre os requisitos e assim fornecem informações/dados importantes sobre possíveis problemas/conflitos de adaptação e integração do sistema, incluindo restrições na arquitetura (usabilidade, portabilidade e disponibilidade) e no próprio projeto (custo e tempo).
  </p>
  <p align='justify'>
    &emsp;Seu objetivo é ajudar desenvolvedores na implementação de soluções personalizadas, levando em consideração as características do domínio e do sistema em questão. Tais características incluem Requisitos Não-funcionais, prioridades e carga de trabalho. Esses fatores determinam a escolha de alternativas de desenvolvimento para um determinado sistema.(SILVA, 2019, p. 30).
</p>

## 2. Metodologia
<p align='justify'>
    &emsp;Para a criação do presente documento, foi utilizado o NFR framework para definir as  funcionalidades dos requisitos não-funcionais através da implementação de diagramas, elaborados a partir de análise das funcionalidades do Prime Video. 
</p>
  
## 3. NFR Framework

O funcionamento do NFR framework pode ser visualizado em termos da construção, elaboração, análise e revisão incremental e interativa de um gráfico de interdependência de softgoal conhecido como "Softgoal Interdependency Graph (SIG)" (CHUNG et al., 2000).

<table>
    <thead>
        <tr>
            <th>Legenda</th>
            <th></th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>
                <img width="80" src="../../assets/img/nfr/softgoal.png">
            </td>
            <td>Softgoal:  um objetivo que não possui uma clara definição nem critérios de satisfação precisos.</td>
        </tr>
        <tr>
            <td>
                <img width="80" src="../../assets/img/nfr/softgoal-op.png">
            </td>
            <td>Softgoal de Operacionalização: Uma possível solução que satisfaz um softgoal.</td>
        </tr>
        <tr>
            <td>
                <center>
                    <span style="font-size:18pt">+</span>
                </center>
            </td>
            <td>HELP(+): Contribuição parcialmente positiva entre um softgoal descendente e um softgoal ascendente.</td>
        </tr>
        <tr>
            <td>
                <center>
                    <span style="font-size:18pt">++</span>
                </center>
            </td>
            <td>MAKE(++): fornece uma contribuição suficientemente positiva (MAKE) entre um softgoal descendente e um softgoal ascendente que é concebida no nível mais alto de satisfação</td>
        </tr>
        <tr>
            <td>
                <img width="80" src="../../assets/img/nfr/contribuicao-and.png">
            </td>
            <td>Contribuição AND: determina que se os softgoals descendentes forem satisfeitos os softgoals ascendentes serão satisfeitos.</td>
        </tr>
        <tr>
            <td>
                <img width="80" src="../../assets/img/nfr/rotulo-satisfeito.png">
            </td>
            <td>Satisfeito.</td>
        </tr>
        <tr>
            <td>
                <img width="80" src="../../assets/img/nfr/rotulo-fracamente-satisfeito.png">
            </td>
            <td>Fracamente Satisfeito.</td>
        </tr>
        <tr>
            <td>
                <img width="80" src="../../assets/img/nfr/rotulo-negado.png">
            </td>
            <td>Negado.</td>
        </tr>
    </tbody>
</table>

## 3.1 Usabilidade

<figure>
    <img 
        src="../../assets/img/nfr/Usabilidade-sem-propagacao.png" alt="usabilidade-sem-propagacao"
    >
    <figcaption>Figura 1: NFR - Usabilidade sem propagação</figcatpion>
    <br/>
    <span>
        <a href="../../assets/img/nfr/Usabilidade-sem-propagacao.png">
            Ampliar visualização
        </a>
    </span>
</figure>

<figure>
    <img 
        src="../../assets/img/nfr/Usabilidade-com-propagacao.png" alt="usabilidade-com-propagacao"
    >
    <figcaption>Figura 2: NFR - Usabilidade com propagação</figcatpion>
    <br/>
    <span>
        <a href="../../assets/img/nfr/Usabilidade-com-propagacao.png">
            Ampliar visualização
        </a>
    </span>
</figure>

## 3.2 Portabilidade

<figure>
    <img 
        src="../../assets/img/nfr/Portabilidade-sem-propagacao.png" alt="portabilidade-sem-propagacao"
    >
    <figcaption>Figura 3: NFR - Portabilidade sem propagação</figcatpion>
    <br/>
    <span>
        <a href="../../assets/img/nfr/Portabilidade-sem-propagacao.png">
            Ampliar visualização
        </a>
    </span>
</figure>

<figure>
    <img 
        src="../../assets/img/nfr/Portabilidade-com-propagacao.png" alt="portabilidade-com-propagacao"
    >
    <figcaption>Figura 4: NFR - Portabilidade com propagação</figcatpion>
    <br/>
    <span>
        <a href="../../assets/img/nfr/Portabilidade-com-propagacao.png">
            Ampliar visualização
        </a>
    </span>
</figure>

## 3.3 Disponibilidade

<figure>
    <img 
        src="../../assets/img/nfr/Disponibilidade-sem-propagacao.png" alt="disponibilidade-sem-propagacao"
    >
    <figcaption>Figura 5: NFR - Disponibilidade sem propagação</figcatpion>
    <br/>
    <span>
        <a href="../../assets/img/nfr/Disponibilidade-sem-propagacao.png">
            Ampliar visualização
        </a>
    </span>
</figure>

<figure>
    <img 
        src="../../assets/img/nfr/Disponibilidade-com-propagacao.png" alt="disponibilidade-com-propagacao"
    >
    <figcaption>Figura 6: NFR - Disponibilidade com propagação</figcatpion>
    <br/>
    <span>
        <a href="../../assets/img/nfr/Disponibilidade-com-propagacao.png">
            Ampliar visualização
        </a>
    </span>
</figure>

## 3.4 Desempenho

<figure>
    <img 
        src="../../assets/img/nfr/Desempenho-sem-propagacao.png" alt="desempenho-sem-propagacao"
    >
    <figcaption>Figura 7: NFR - Desempenho sem propagação</figcatpion>
    <br/>
    <span>
        <a href="../../assets/img/nfr/Desempenho-sem-propagacao.png">
            Ampliar visualização
        </a>
    </span>
</figure>

<figure>
    <img 
        src="../../assets/img/nfr/Desempenho-com-propagacao.png" alt="desempenho-sem-propagacao"
    >
    <figcaption>Figura 8: NFR - Desempenho com propagação</figcatpion>
    <br/>
    <span>
        <a href="../../assets/img/nfr/Desempenho-com-propagacao.png">
            Ampliar visualização
        </a>
    </span>
</figure>

## 4. Resultado

Optamos por utilizar o NFR Framework, pois ele trata os Requisitos não-funcionais (RNF) de uma forma específica além de ser amplamente utilizado pela comunidade acadêmica. Com ele foi possível mapear as interdependecias entre os RNF e os impactos de um sobre os outros, sendo isso tudo possível de ser visualizado graças ao grafo de Interdepêndencia de Softgoal - Softgoal Interdependency Graph (SIG). No mais, vale resaltar que não objetivamos criar um catálogo completo que cubra 100% dos RNF, já que o mesmo está sempre em contante evolução, mas esperamos que este catálogo apresente uma boa cobertura sobre os RNF.

## 5. Referências
CHUNG, L. e NIXON, B., “Using Non-Functional Requirements to Systematically Support Change”, 1995. Acesso em 08 de Março de 2022.<br></br>
BRITO, Isabel; NFR Framework. jaejaneiro, (2007-2008). Disponível em: <http://jaejaneiro.orgfree.com/engsofnfr.pdf>. Acesso em: 08 de Março 2022.<br></br>
SILVA, Reinaldo Antônio da. NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. 2019

## 6. Histórico de Versionamento

|Versão|Data de modificação|Descrição da modificação|Autor|Revisor|
|-|-|-|-|-|
|1.0|07/03/2022|Criação do documento do NFR Framework|[Douglas Monteles](https://github.com/douglasmonteles) e [Sávio Cunha](https://github.com/savioc2)||

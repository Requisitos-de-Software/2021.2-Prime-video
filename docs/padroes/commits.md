# Políticas de Commit

Padronização dos commits no projeto. 


## Semântica do Commit

Os commits devem seguir o seguinte padrão:


### Princípios:

#### Commits atômicos

Sempre dividir em pequenos commits, para melhor manutenção e rastreamento.

#### Commits em português

Foi decidido que todos os commits serão em pt-BR.

### Formato:
```
<tipo>: assunto
```

#### Tipos:

- ```fix```: correções
- ```docs```: relacionado a documentação

#### Assunto:

- Deve possuir até 50 caracteres
- Deve haver apenas letras minúsculas

*Exemplo de commit:*
```
git commit -m "docs: adicionado politicas de commit"
```

## Histórico de Versões

| Data       | Versão | Descrição                      | Autor             |
| :--------: | :----: | :----------:                   | :---------------: |
| 14/02/2022 |  1.0   | Criação da política de commits | [Lameque Fernandes](https://github.com/LamequeFernandes)|


## Referências

DARTORA, João. Tudo o que você precisa saber sobre commits semânticos. *Ilegra*. Disponível em: <https://ilegra.com/blog/tudo-o-que-voce-precisa-saber-sobre-commits-semanticos/>. Acesso em: 14 de fev. de 2022.

Políticas de Commit. Disponível em: <https://fga-eps-mds.github.io/2020.1-Grupo6/policies/commits/>. Acesso em: 14 de fev. de 2022.
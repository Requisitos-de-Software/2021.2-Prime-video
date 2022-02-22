# Políticas de Commit

Padronização dos commits no projeto. 


## 1. Semântica do Commit

Os commits devem seguir o seguinte padrão:


### 1.1 Princípios:

#### 1.1.1 Commits atômicos

Sempre dividir em pequenos commits, para melhor manutenção e rastreamento.

#### 1.1.2 Commits em português

Foi decidido que todos os commits serão em pt-BR.

### 1.2 Formato:
```
<tipo>: assunto
```

#### 1.2.1 Tipos:

- ```fix```: correções
- ```docs```: relacionado a documentação

#### 1.2.2 Assunto:

- Deve possuir até 50 caracteres
- Deve haver apenas letras minúsculas

*Exemplo de commit:*
```
git commit -m "docs: adicionado politicas de commit"
```

## 2. Referências

DARTORA, João. Tudo o que você precisa saber sobre commits semânticos. *Ilegra*. Disponível em: <https://ilegra.com/blog/tudo-o-que-voce-precisa-saber-sobre-commits-semanticos/>. Acesso em: 14 de fev. de 2022.

Políticas de Commit. Disponível em: <https://fga-eps-mds.github.io/2020.1-Grupo6/policies/commits/>. Acesso em: 14 de fev. de 2022.


## 3. Histórico de Versionamento

| Data       | Versão | Descrição                      | Autor             |
| :--------: | :----: | :----------:                   | :---------------: |
| 14/02/2022 |  1.0   | Criação da política de commits | [Lameque Fernandes](https://github.com/LamequeFernandes)|

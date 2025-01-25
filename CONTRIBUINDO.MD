# Contribuindo

As seguintes informações fornecem um conjunto de diretrizes para contribuir no repositório principal `DevOpsBrHub/AWSHub`. Use seu melhor julgamento e, se perceber espaço para melhorias, proponha alterações neste documento.

## Primeiros passos

O primeiro passo é encontrar uma issue que você deseja corrigir. Para identificar as issues que acreditamos ser boas para contribuições de iniciantes, adicionamos o rótulo [good first issue](https://github.com/DevOpsBrHub/AWSHub/issues).

Após encontrar uma issue existente que você deseja trabalhar ou se tiver uma nova issue para criar, continue abaixo.

## Propondo mudanças

Para contribuir com uma proposta de mudança, siga o seguinte fluxo de trabalho:

1. [Faça um fork do repositório](https://github.com/DevOpsBrHub/AWSHub).

2. [Adicione um upstream](https://docs.github.com/en/github/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) para que você possa atualizar seu fork.

3. Clone seu fork para seu computador.

4. Crie uma branch e nomeie-a de forma apropriada.

5. Trabalhe em apenas uma alteração principal por pull request.

6. Certifique-se de que todos os testes estão passando localmente.

7. Em seguida, repita o seguinte processo:

    1. Faça o commit das suas alterações. Escreva uma mensagem de commit simples e direta. Para saber mais, veja [Como Escrever uma Mensagem de Commit no Git](https://chris.beams.io/posts/git-commit/).

    2. Envie suas alterações para seu fork remoto. Para adicionar seu remoto, você pode copiar/colar o seguinte:

    ```sh
    #Remover origin
    git remote remove origin

    #Definir um novo remote
    git remote add my_awesome_new_remote_repo [insira-o-link-encontrado-na-abas-de-origem-do-seu-repo]

    #Verificar novo remote
    git remote -v

    > my_awesome_new_remote_repo  [link-encontrado-na-abas-de-origem-do-seu-repo] (fetch)

    > my_awesome_new_remote_repo  [link-encontrado-na-abas-de-origem-do-seu-repo] (push)

    #Enviar alterações para o seu repositório remoto
    git push <nome_do_seu_remote>

    #exemplo: git push my_awesome_new_remote_repo
    ```

    3. Crie um PR no repositório `AWSHub`. Deve haver um modelo de PR para ajudá-lo a fazer isso.

    4. Aguarde a revisão das suas alterações. Se você for um mantenedor, pode atribuir seu PR a um ou mais revisores. Se não for um mantenedor, um dos mantenedores irá atribuir um revisor.

    5. Após receber o feedback de um revisor, faça as alterações solicitadas, faça o commit delas na sua branch e envie novamente para seu fork remoto.

    6. Após a aprovação, fique à vontade para realizar o squash & merge!

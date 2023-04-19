- Configura��o do Git:
  - precisamos configurar o ambiente. Ent�o devemos configurar o 'name' e o 'email', usando da seguinte forma:
- Depois de instalados o GIT, abra o gitBash, e vamos configurar pela linha de comando.

- com o terminal aberto, digite o seguinte comando, para configurar o 'name':
    - git config --globar user.name nomeUsuarioQueEstaNoGitHub
    > *onde nomeUsuarioQueEstaNoGitHub = o seu nome de usu�rio do gitHub*
- logo ap�s, digite o seguinte comando, para configurar o 'email':
    - git config --global user.email emailcadastradonogit@gmail.com
    > *onde emailcadastradonogit@gmail.com = o seu e-mail cadastrado no gitHub*
- logo ap�s, digite o seguinte comando, para verificar se foi configurado corretamento:
    - git config --list

- se na lista de configura��o aparecer o nome e e-mail que voc� digitou, as configura��es est�o corretas..
caso contr�rio, repita o passo para configurar corretamente.
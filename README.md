# Git Config

Configurações de atalhos para o git

## Como Utilizar

- Coloque o arquivo _.gitconfig_ na pasta de _Users_ do seu SO

- Em _.gitconfig_ no campo _user_ altere os dados para o seu usuário

## Atalhos

- ### c

  Encurta a realização do commit

  ***

  #### Exemplo

  ```bash
     //Antes
     $ git add --all
     $ git commit -m <your_message>

     //Depois
     $ git c <your_message>
  ```

- ### s

  Encurta a realização do git status

  ***

  #### Exemplo

  ```bash
    //Antes
    $ git status -s

    //Depois
    $ git s
  ```

- ### l

  Realiza um log rico de informações formatado

  #### Exemplo

  ```bash
    //Antes
    $ git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s %C(cyan)%cn, %C(green)%cr'

    //Depois
    $ git l
  ```

  - ### r

  Encurta a realização do git remote

  #### Exemplo

  ```bash
    //Antes
    $ git remote add origin <yourrepostiory>

    //Depois
    $ git r <your_repository>
  ```

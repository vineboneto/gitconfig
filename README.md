# Git Config

Configurações de atalhos para o git

## Como Utilizar

- Coloque o arquivo _.gitconfig_ na pasta de _Users_ do seu SO

- Em _.gitconfig_ no campo _user_ altere os dados para o seu usuário

## Alias

Encurta a realização do commit

---

#### Exemplo

```shell
   //Antes
   $ git add --all
   $ git commit -m <your_message>

   //Depois
   $ git c <your_message>
```

Encurta a realização do git status

---

#### Exemplo

```shell
  //Antes
  $ git status -s

  //Depois
  $ git s
```

---

Realiza um log rico de informações formatado

---

#### Exemplo

```shell
  //Antes
  $ git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s %C(cyan)%cn, %C(green)%cr'

  //Depois
  $ git l
```

Encurta a realização do git remote

---

#### Exemplo

```shell
  //Antes
  $ git remote add origin <yourrepostiory>

  //Depois
  $ git r <your_repository>
```

Encurta a Criação de tags

---

#### Exemplo

```shell
  //Antes
  $ git tag "0.0.1" -m "0.0.1"

  //Depois
  $ git tg "0.0.1"
```

Buca todas as tags de forma decrescente

---

#### Exemplo

```shell
  //Antes
  $ git -c 'versionsort.suffix=-' tag --list --sort=-v:refname

  //Depois
  $ git tags
```


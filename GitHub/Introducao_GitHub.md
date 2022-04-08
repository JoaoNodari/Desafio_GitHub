# Introdução do GitHub
**GitHub** é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo.



## Estalando o Git no Sistema Operacional:

[Download Oficial] (https://git-scm.com/downloads)



### Configurando Usuário e Email

Antes de iniciar, configure o usuário e o email que aparecerá no histórico de commits:

```git config user.name "seu.usuario```

```git config user.name "seu.usuario@usuario.com```

### Repositório

Existem duas formas de criar um repositório

- Clonar Repositório
- Criar um novo Repositório

### Clonando um Repositório

Para clonar, é necessário acessar o gerenciador de repósitorio e copiar o link de clone, em seguida abrir o CMD e digitar os seguintes comando.

```git clone https://github.com/JoaoNodari/Desafio_GitHub.git\```

### Criar um novo Repositório

Para criar um novo repositório acesse o GitHub, e após logar clique em `Repositórios > Novo Repositório` de um nome para o seu repositório e salve.

Após isso abra o CMD e faça:

**Para criar o projeto***

```mkdir meuprojetogit```

**Entre na pasta**

```cd meuprojetogit```

**Inicie o Git**

```git init```

O comando *git init* vai criar uma pasta oculta .git.

Agora devemos informar ao GitHub que esse diretório deve manter comunicação com o repositório que criamos anteriormente:

**Comando para configurar a origem remota do repositório**

```git remote add origin https://teste.com.br/seu.usuario/meuprojetogit.git```

## Comandos Básicos

**Sempre que queira consultar se há diferenças entre a versão local e a remota, utilize esse comando:**

```git status```

**Para adicionar a alteração utilize:** 

```git add .```

**Agora que sinalizamos ao Git que queremos alterar a versão remota do arquivo, vamos iniciar o processo de commit com utilizando o comando:**

``git commit -m "comentário"``

**O ultimo passo é realizar o comando `git push`, responsável por empurrar as alterações do nosso computador até o repositório remoto: **

``git push origin maste``

**Para baixar alteração do repositório remoto:**

``git pull``




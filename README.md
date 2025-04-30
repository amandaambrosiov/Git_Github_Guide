# 🐙 Guia Rápido - Git e Github

Git e GitHub são ferramentas essenciais no desenvolvimento de software moderno, usadas principalmente para controle de versão, colaboração em equipe e gestão de código-fonte. Apesar de estarem intimamente relacionados, eles são ferramentas diferentes com propósitos complementares.

### 🔧 Git

Git é um sistema de controle de versão distribuído, permite que desenvolvedores acompanhem as mudanças feitas em arquivos ao longo do tempo, revertam alterações, criem versões alternativas do código (branches), e colaborem de forma eficiente, mesmo sem conexão com a internet.

### ☁️ GitHub

GitHub é uma plataforma online que hospeda repositórios Git. Ele oferece uma interface gráfica na web, além de ferramentas para facilitar a colaboração entre desenvolvedores, como:
* Controle de permissões e contribuições;
* Pull requests (para revisão de código);
* Issues (para rastrear bugs e ideias);
* Actions (integração contínua e automações);
* Wikis e documentação do projeto.

## Comandos básicos Git

### 🛠️ Configuração inicial

#### Definir nome de usuário:
~~~
git config --global user.name "Seu Nome"        
~~~

#### Definir e-mail do usuário:
~~~
git config --global user.email "seu@email.com"  
~~~

#### Ver configurações atuais:
~~~
git config --list
~~~

### 📁 Criar ou Clonar Repositórios


#### Iniciar um repositório Git:
~~~
git init
~~~

#### Clonar um repositório existente:
~~~
git clone https://github.com/user/repositorio.git
~~~

### 📄 Adcionar e commitar arquivos:

#### Verificar status dos arquivos:
~~~
git status
~~~

#### Adicionar todos os arquivos ao staging:
~~~
git status
~~~

#### Fazer um commit:
~~~
git commit -m "mensagem do commit"
~~~

### ☁️ Trabalhando com repositórios remotos:

#### Adicionar repositório remoto (GitHub):
~~~
git remote add origin https://github.com/user/repositorio.git
~~~

#### Enviar código para o GitHub:
~~~
git push -u origin main
~~~

#### Atualizar seu código com mudanças do GitHub:
~~~
git pull
~~~

####  Buscar atualizações sem mesclar:
~~~
git fetch
~~~

### 🌿 Trabalhando com Branches 

####  Ver todas as branches:
~~~
git branch
~~~

####  Criar nova branch:
~~~
git branch nome-da-branch
~~~

####  Mudar para outra branch:
~~~
git checkout nome-da-branch
~~~

####  Criar e mudar para nova branch:
~~~
git checkout nome-da-branch
~~~

####  Mesclar branch com a atual:
~~~
git merge nome-da-branch
~~~

####  Deletar uma branch:
~~~
git branch -d nome-da-branch
~~~

### 🔙 Desfazer mudanças

####  Desfazer último commit (mantendo mudanças):
~~~
git reset --soft HEAD~1
~~~

####  Desfazer último commit e apagar mudanças:
~~~
git reset --hard HEAD~1
~~~

####  Desfazer mudanças locais em um arquivo:
~~~
git checkout -- arquivo.txt
~~~

### 🧼 Comandos úteis

####  Guardar mudanças temporariamente:
~~~
git stash
~~~

####  Restaurar mudanças guardadas:
~~~
git stash apply
~~~

####  Ver diferenças entre arquivos:
~~~
git diff
~~~

####  Força o push da branch atual (HEAD) para o repositório remoto:
~~~
git push -f origin HEAD
~~~






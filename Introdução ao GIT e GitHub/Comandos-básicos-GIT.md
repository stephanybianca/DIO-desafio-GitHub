# Comandos básicos do GIT

### Ajuda

git help

git help <qualquer_comando_git>

### Configuração

São armazenadas no arquivo .gitconfig localizadas dentro do diretório do usuário do Sistema Operacional. 

**Setar email**


git config --global user.email (coloca o seu email do github de preferencia)

*ex:* git config --global user.email steamaral26@gmail.com

**Setar usuário**


git config --global user.name

**Listar configurações**


git config --list

**Setar ferramenta de merge**


git config --global merge.tool vimdiff

**Setar editor**


git config --global core.editor vim

### Repositório Local

**Criar novo repositório**


git init



**Verificar estado dos 
arquivos/diretórios**


git status



### Adicionar arquivo/diretório (staged area)

**Adicionar um arquivo em específico**


git add meu_arquivo.txt



**Adicionar um diretório em específico**


git add meu_diretorio



**Adicionar todos os arquivos/diretórios**


git add .    



**Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)**
git add -f arquivo_no_gitignore.txt



### Comitar arquivo/diretório

**Comitar um arquivo**


git commit meu_arquivo.txt



**Comitar vários arquivos**


git commit meu_arquivo.txt meu_outro_arquivo.txt



**Comitar informando mensagem**


git commit meuarquivo.txt -m "minha mensagem de commit"



### Remover arquivo/diretório

**Remover arquivo**


git rm meu_arquivo.txt



**Remover diretório**


git rm -r diretorio



### Visualizar histórico



**Criar novo repositório**


git init



**Verificar estado dos 
arquivos/diretórios**
git status

### Adicionar arquivo/diretório (staged area)

**Adicionar um arquivo em específico**


git add meu_arquivo.txt



**Adicionar um diretório em específico**


git add meu_diretorio



**Adicionar todos os arquivos/diretórios**


git add .    



**Adicionar um arquivo que esta listado no .gitignore (geral ou do repositório)**


git add -f arquivo_no_gitignore.txt



### Comitar arquivo/diretório

**Comitar um arquivo**


git commit meu_arquivo.txt



**Comitar vários arquivos**


git commit meu_arquivo.txt meu_outro_arquivo.txt



**Comitar informando mensagem**


git commit meuarquivo.txt -m "minha mensagem de commit"



### Remover arquivo/diretório

**Remover arquivo**


git rm meu_arquivo.txt



**Remover diretório**


git rm -r diretorio



### Visualizar histórico

**Exibir histórico**


git log



**Exibir histórico com diff das duas últimas alterações**


git log -p -2



### Repositório Remoto

**Exibir os repositórios remotos**


git remote

git remote -v



 **Vincular repositório local com um repositório remoto**



git remote add origin + link copiado do GitHub 


ex: git remote add origin https://github.com/stephanybianca/DIO-desafio-GitHub.git



**Exibir informações dos repositórios remotos**



git remote show origin



**Renomear um repositório remoto**


git remote rename origin curso-git



**Desvincular um repositório remoto**


git remote rm curso-git



**Enviar arquivos/diretórios para o repositório remoto**

*O primeiro **push*** de um repositório deve conter o nome do repositório remoto e o branch*

git push -u origin main



*Os demais pushes não precisam dessa informação*
git push



### Atualizar repositório local de acordo com o repositório remoto

**Atualizar os arquivos no branch atual**


git pull



**Buscar as alterações, mas não aplica-las no branch atual**


git fetch



**Clonar um repositório remoto já existente**


git clone + link do repositorio 

ex: git clone https://github.com/stephanybianca/DIO-desafio-GitHub.git



## Contribuições

Listagem de comando criada com base nos meus conhecimentos adquiridos (estou começando agora). 

Sinta-se a vontade para realizar correções e adicionar mais informações

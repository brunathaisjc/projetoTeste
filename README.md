#CONTROLE DE VERSÃO - GIT E GITHUB

CRIANDO UM REPOSITÓRIO {

No terminal do Git Bash:

1.Configurar o usuário:
git config --global user.name'brunathaisjc'

2.Configurar o email:
git config --global user.email 'btgnasc@gmail.com'

3.Clonar repositório do Github: (Para colar no gitbash use o shift + insert)
git clone https://github.com/brunathaisjc/Api-com-Python.git

Aqui o git vai criar uma pasta no diretorio do meu usuário(C:\Usuários\bruna) com o nome do repositorio criado. Este comando puxa o repositório(pasta) do Github para o computador.

4.Depois disso precisamos acessar a pasta pelo terminal do git.
Aqui ele vai estar como 'main'. 

Para subir um arquivo para para o Github precisamos seguir três passos:
git add (vai levar o arquivo para aárea de stage)
git commit (é o comando para escrever com uma mensagem sobre a alteração ou aquele arquivo)
git push (é o comando para o envio de fato, o empurrão)

5. Adicionando um arquivo:
git add README.md

5.1. Adicionando todos:
git add .

6. Fazendo uma descrição do arquivo/alteração com o commit:
git commit -m 'Adicionando o README'

7. Dando o empurrão com o push:
git push -u origin main

Se você não quiser fazer isso pelos terminais Git ou VS Code, você pode usar o 'Source Control" do VS Code.

} 

ENVIANDO PROJETO PRONTO {

1. Pelo terminal devemos entrar na pasta a ser enviada para inicializar o versionamento. Aqui o GIT BASH vai criar uma pasta .git no diretório.
git init

2. Fazer o commit normal
git commit -m 'commit inicial'

3. Agora é necessário criar um repositório no Github e usar o link para fazer o remote.
Aqui enviamos os arquivos do nosso computador para o link através do comando remote.
git remote add origin https://github.com/brunathaisjc/Api-com-Python.git




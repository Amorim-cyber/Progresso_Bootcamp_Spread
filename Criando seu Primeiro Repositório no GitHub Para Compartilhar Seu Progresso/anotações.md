INÍCIO

A finalidade dessa etapa foi ensinar o dev iniciante a como criar e baixar seu primeiro repositório no gitHub segue abaixo os passos resumidos:

1) Crie uma conta github

2) Depois de logar na conta crie o seu repositório por meio desse <a href=" https://github.com/new">link</a>

3) Digite o título e a descrição do seu repositório e crie

4) Crie uma pasta no seu diretório local aonde será linkado o seu repositório

5) Repositório criado agora abra o git bash dentro do seu diretório local

6) Digite os seguintes comandos:
`git init
git remote add origin <Endereço HTTPS do seu repositório>
git branch -M main
git add .
git commit -m "Primeiro commit"
git push -u origin main`

7) PRONTO, seu repositorio está linkado a seu diretório local.

8) Para incluir novos arquivos utilize os seguintes comandos:
`git add .
git commit -m "Descrição breve do seu commit"
git push -u origin main`

---------------------------------

ALTERNATIVA

- Você pode adicionar diretamente no site do git novos arquivos.

- Caso queira passar os arquivos do repositório github para uma pasta local utilize o seguinte comando:

`git pull <Endereço HTTPS do seu repositório>`
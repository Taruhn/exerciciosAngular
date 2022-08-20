#Respostas:

(1): Descreva com suas palavras como é feita a instalação do Framework Angular passo-a-passo.
1 - Crie uma nova pasta vazia no local que deseja.

2 - Dentro da pasta, acesse o prompt de comando usando o caminho onde
está a pasta, para isso é só escrever "cmd" na box que mostra o caminho da
pasta.

2 - Dentro do Prompt de comando, use o seguinte código para instalar
"npm install -g @angular/cli", e em seguida aperte Enter. 

3 - Depois de instalado, no cmd use "ng version", ele vai mostrar a 
versão do angular que foi colocada, e com isso o angular está instalado.

4 - Após instalado com as depedências, para criar um novo arquivo em angular, use "ng new helloWorld",
com isso ele vai criar o arquivo com o nome helloWorld.

5 - Depois disso, no CMD, use o comando "cd helloWorld", quando utilizado, ele vai entrar na pasta do arquivo.

6 - Para abrir o servidor do arquivo angular, no CMD digite "ng serve --open", depois o execute, quando executado
ele vai carregar e vai aparecer no navegador o arquivo angular com o link "http://localhost:4200/" como padrão do sistema.

 
(5):Observe e compare o repositório local e o repositório remoto.

Há diferenças? 
- Sim possúi diferenças.

Se sim, quais? 
- A principal delas é na pasta node_modules com as dependências do angular que não estão dentro do github.

Por que essas diferemças ocorrem? 
- As diferenças ocorrem por causa do .gitignore que é um arquivo utilizado para ignorar os arquivos dentro dele que estão relacionados
 no momento de executar o comando push para o repositório do github.

(6): Apague o repositório local e clone o remoto devolta para sua máquina e rode o projeto.
     Após clonar o projeto, você precisará baixar as dependências desse projeto.

Qual comando do Node instala as dependências? 
- O comando utilizado para instalar é "npm install" ou "npm i".

Como o Node sabe quais dependências precisam ser instaladas?
- O Node reconhece as dependências que são excenciais para serem instaladas pelo arquivo "package-lock.json" que aponta
 todas as dependências que o projeto deve utilizar.
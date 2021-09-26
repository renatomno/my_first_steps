1. Após criado a sua conta no GitHub, crie um repositório remoto público chamado "my_first_steps" e cole o link aqui;

    	https://github.com/renatomno/my_first_steps

2. Crie um diretório em sua máquina e o vincule ao seu repositório remoto "my_first_steps" utilizando os comandos git necessários para a realização desta tarefa. Cole aqui a cadeia de comando que você utilizou para a realização desta tarefa.

    Utilizando o terminal, criei uma pasta qualquer:

    	mkdir alpha_git

    Selecionei-a para navegação

     	cd alpha_git

    Iniciei o git

    	git init

    E fiz o link do repositório com a pasta local

    	git remote add origin https://github.com/renatomno/my_first_steps

    Agora tenho um diretório vinculado ao meu repositório remoto

3. Dentro do diretório em sua máquina, crie um arquivo chamado "ola_mundo.txt", adiciona algum texto da sua preferência e adicione-o ao seu repositório remoto utilizando os comandos git necessário para a realização desta tarefa. Cole aqui a cadeia de comandos que você utilizou para a realização desta tarefa.

    Criação do arquivo

    	touch ola_mundo.txt

    Edição do arquivo

    	vi ola_mundo.txt

    Passando o arquivo para a fase de Stage

    	git add ola_mundo.txt

    Fazendo commit do arquivo com comentário

    	git commit -m "add ola_mundo.txt"

    Fazendo o upload para o repositório remoto

    	git push -u origin master

4. Se não existir em seu diretório, adiciona ao seu diretório um arquivo com o nome de ".gitignore". Em seguida, crie um arquivo chamado "serei_ignorado.txt" e adicione algum texto dentro dele. Adiciona a instrução ao arquivo ".gitignore" para que as alterações realizadas no arquivo "serei_ignorado.txt" não seja controlado pelo git. Cole aqui o conteúdo que você utilizou no ".gitignore" para a realizar esta tarefa.

    Criando os arquivos

    	touch .gitignore serei_ignorado.txt

    Editando o arquivo de texto

    	vi serei_ignorado.txt

    Editando o arquivo ".gitignore" (vi .gitignore), basta adicionar o nome do arquivo que queremos que seja ignorado. Logo, em sua primeira linha está escrito "serei_ignorado.txt"..

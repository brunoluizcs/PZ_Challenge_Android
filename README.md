# PZ_Challenge_Android
Programming Challenge for Android Developers

# Photozig - Desafio de programação Android

## Instruções de entrega do desafio

1. Primeiro, faça um fork deste projeto para sua conta no Github (crie uma se você não possuir).
2. Desanexe o fork do seu projeto (Instrucao de Desanexar abaixo) e apague (ou esconda com private) o seu fork.
2. Em seguida, implemente o projeto tal qual descrito abaixo, em seu próprio repositório depois de estar desanexado.
3. Crie as instruções de instalação e execução do aplicativo em seu readme.md
4. Por fim, envie o link do seu repositório para avaliarmos seu código

Desanexar: duplicate the repository: a) Create a new repository on GitHub, b) Clone the forked repository you want to detach from its parent, and c) Push all branches in this clone to your new repository.

## Requisitos do projeto

1. Carregar um json dinamicamente a partir da url `http://pbmedia.pepblast.com/pz_challenge/assets.json`, fazer o parse e criar uma interface (lista) com os objetos disponíveis no json. Na lista mostrar o nome ("name") e a imagem ("im") do objeto;

2. Para cada objeto da lista têm que ter uma opção para fazer o download e outra pra ir para outra tela "B", começar o download e quando terminar tocar o vídeo e áudio;

3. Na tela "B", onde tocará o vídeo background ("bg") juntamente com o áudio ("sg"), o background deve tocar em looping até o áudio terminar;

* Bônus 1: Desenvolver uma fila para gerenciar os downloads na qual o último elemento inserido deve ter prioridade para terminar. Exemplo:

	Insere na fila A;
	Insere na fila B;
	Insere na fila C;
	
	O download do objeto C deve terminar primeiro, depois B e depois A. Mostrar um log cada vez que um download começar e quando terminar;

* Bônus 2: Ter uma opção de ir para o item próximo e anterior a partir dessa tela, sem ter que voltar para a lista e selecionar outro item.

* Bônus 3: Para os objetos que contenham textos ("txts"), a interface deve mostrar os textos centralizados em cima do vídeo background no tempo especificado ("time").

Para carregar os assets utilizar a url base do campo ("assetsLocation") + o nome do arquivo especificado em cada objeto.

## Avaliação

Seu projeto será avaliado conforme os critérios:

1. Atende funcionalmente o que foi pedido;
2. Interpretação dos requisitos e do json fornecido;
3. Documentar o que é necessário para configurar o ambiente e rodar sua aplicação na maquina do avaliador;
4. Boas práticas de programação e Design Pattern;
5. Código bem escrito, fácil de entender e manter;
6. Interface e uso da aplicação pelo Usuário;

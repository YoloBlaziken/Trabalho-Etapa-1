Goncalo Ramos Morais a28642
Jogo: AutoPong

Pasta: .config
Tem o ficheiro dotnet tools json que serve para mostrar a versão

Pasta: .vs
Serve para caches temporários 

Pasta: .vscode
Serve para abrir o ficheiro em diferentes sistemas operativos

Pastas: AutoPong.Android/DesktopGL/iOS/WindowsDX
Tem uso para o jogar poder ser usado nos diferentes sistemas operativos

Pasta: AutoPong.Core
Onde tem o próprio código do jogo

Pasta: Game
Audiosource.cs:
Serve para o áudio do jogo, calcular se o som é agudo ou grave e interromper sons se outro começar

Game1.cs:
Serve para carregar a janela do jogo e registrar os commandos com os inputs diferentes

InputState.cs:
Ler o estado do input, seja tecla pressionada, rato a ser movido, ou butão segurado, para facilitar tradução para diferentes inputs e resoluções

WaveType.cs:
Carrega os diferentes tipos de sons no AudioSource.cs

AutoPongGame.cs 
-Fazer uma resolução
-Fazer as peças
-Fazer físicas para a bola
-Texturas
-Aleatoriedade
-Sistema de pontos
-Efeitos sonors
-Limites do jogo
-Visualizar rato
-Loop do jogo
-Desenhar os objetos da tela
-Limite dos objetos
-Criar texturas se não existir
-Posições dos objetos
-Pontuação
-Efeitos sonoros

Ficheiro: AutoPong.sln
O código tem os propósitos:
- Mostrar que é um executável de Windows
- Poder rodar em versões futuras
- Carregar tudo de uma só vez
- Desligar otimização para rodar mais rápido ao abrir
- Aparecer na resolução certa
- Usar o DirectX para renderização
- Compilar tudo para que a engine consigar ler tudo
- Restaurar ferramentas do dotnet

Ficheiro README:
Comentários do desenvolvedor (seja como o jogo foi feito, controlos ou créditos)
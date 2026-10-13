# SpaceImpact

Este projeto é uma adaptação para web do clássico jogo **Space Impact** do famoso “Nokia tijolão”.

![Tela do nokia](Sprites/nokia.png)

version: 1.0.0

# Descrição do funcionamento.
Você joga utilizando o mouse para controlar a nave que dispara automaticamente.

Utilize os botôes P ou ESC para pausar o jogo.

Utilize o botão esquerdo do mouse ou a barra de espaço para ativar sua habilidade especial.

# Instruções para execução.
Clone o repositório do jogo em sua máquina ou baixe o arquivo zip e o descompacte

Após clonar/baixar o zip você tera algumas opções para rodar o jogo:
- A primeira é abrindo o repositório do jogo no vscode e rodando utilizando o live server. Abra o repositorio e com o botão direito do mouse clique no arquivo index.html e então clique na opção "Open with Live Server".
- Outra maneira de executar é usando o servidor HTTP do Python. Dentro da pasta do jogo, rode no terminal:

```bash
python3 -m http.server 5500
```
Depois abra no navegador: http://localhost:5500

Se no seu sistema o comando for python em vez de python3, use:
```bash
python -m http.server 5500
```
- Outra opção é usar o Node.js com o pacote http-server:
```bash
npx http-server
```

# Divisão de responsabilidades entre os membros do grupo.

Carlos Verçosa
- Menu Inicial
- Inimigos comuns
- Level e Boss 1
- Level e Boss 2
- Level e Boss 3

Nilson Andrade dos Santos Junior
- Trilha sonora
- Power ups e vidas extras
- Level e Boss 4
- Level e Boss 5
- Level e Boss 6


Letícia de Souza Natividade
- Menu de pausa
- Tela de fim do jogo
- Level e Boss 7
- Level e Boss 8
- conquistas

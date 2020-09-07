# wsl2-x11
Esse repositório serve para guardar como exibir comandos gráficos do wsl no windows 10, usando o x11.

1) Instale o Xming:
https://xming.softonic.com.br/download

2) Instale seu comando gráfico no seu S.O. do wsl (por exemplo: apt-get install gnuplot-x11)

3) Use o comando a seguir para abrir o seu comando gráfico dentro de um terminal windows (conectado ao seu wsl):
DISPLAY=localhost:0.0 gnuplot

Pronto, seu comando gráfico será exibido pelo Xming.


Referência: https://www.youtube.com/watch?v=Eck2x50BEzE

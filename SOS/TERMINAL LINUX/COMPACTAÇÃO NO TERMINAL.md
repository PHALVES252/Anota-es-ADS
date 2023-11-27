 O tar é um arquivador, sendo assim, ele não compacta apenas junta

Poder ser usuado o gzip para compactar

comandos

gz- compactador pelo gzip
bzip2- compactador pelo bzip2

-c   criar um novo arquivo
-x extrai arquivo de um arquivo compactado
-j filtra
-t lista o conteudo do arquivo
-f uso do arquivo para gravação

comando no terminal
tar -cf aulasLinux.tar aulas*

tar- tipo de arquivo 
-c vai criar um arquivo , uma pasta
f  o arquivo vai ser gravado na pasta
aulasLinux.tar  nome da pasta 
aulas*- irá juntar todos os arquivo que começem com aulas indepedentemente do que venha depois


Para compactar basta colocar um z antes do f, o arquivo vai ser compactado com gzip

tar -czf aulasLinux.tar aulas*




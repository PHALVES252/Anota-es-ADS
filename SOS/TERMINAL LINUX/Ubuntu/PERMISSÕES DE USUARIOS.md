
Digitando ls -l em uma pasta,  você sabe as permissões para um determinado arquivo

A esquerda do arquivo haverá um sequencia de tres variaveis compostas por carcteres separadas por um traço, dessa maneira

-rwxr-xr---

Primeiro carcteres diz o tipo de arquivo, um d é um diretorio. um l um link a um arquivo um - é um arquivo comun

2 ao 4 caracteres- permisões do dono do arquivo(paulo)

Para modificar as permissões de uma arquivo, utilize um comando CHMOD

Passo a Passo:

Primeiro no terminal utilize o comando cd para entrar na pasta de Documents
cd Documents

Para  visualizar todos os arquivo da pasta documents utilize o comando ls -l
![[Pasted image 20231025111247.png]]

Repare que em seu canto esquerdo há uma sequencia de carcteres separadas por um traço
-rw-rw-r

![[Pasted image 20231025113434.png]]


Para incluir uma permissão user o seguinte comando
![[Pasted image 20231026104425.png]]
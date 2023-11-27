
No exemplo irei usar um tabela de rh onde há uma coluna para anos em que um funcionario ficou sem receber promoção, há muitos possibilidade, nesse caso, deve se questinar o setor de rh o criterio para recbeber promoção, nesse caso, o criterios será de cinco anos.

Sendo assim, iremos criar uma tabela condicional, como o proprio nome diz que ´com uma condição, que irá utilizar a tabela "Anos sem promoção" para atribuir um nome de StatusPromo.

Clique em trasnformar dados
Adicionar Coluna
coluna condicional
em nome da nova coluna escreva STATUSPROMO(opcional)
em nome da coluna, seleciona a coluna que será usada para criar a coluna condicional, nesse exemplo Anos sem promoção
em operador selecione o atribuito será maior, menor ou igual, nesse caso, maior ou igual
em valor selecione um numero a ser comparado, nesse caso, será o 5, no caso se na coluna anos sem promoção estiver com 4, ele vai pegar esse 4 e vai verificar se ele é maior ou igual a 4
A saida será o resultado de anos sem promoção for maior ou igual a 5, nesse caso será "Com promoção"
Nesse caso apenas a condição maior que 5 gerando a saida com promoção irá aparecer na tela crie uma segunda condição em " Criar clausula" em em vez do operador ser "maior ou igual" selecione menor que , a saida será  sem promoção
clique em ok, logo em seguida em "Fechar e aplicar"


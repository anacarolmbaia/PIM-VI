## Sistema de cadastro de lojas 

Como solicitado no manual do PIM VI de Gestão de TI, o sistema realiza o cadastro de lojas e tem como base o Nome, Tipo (Matriz ou Filial) e CNPJ. Esses dados são salvos em um arquivo de texto que é utilizado como um "Banco de Dados". 

Esse arquivo será criado automaticamente na primeira execução do script e é consultado todas as vezes que a opção “Listar” é selecionada, pois para tal ação, o programa considera todos os dados como uma string e os exibe na tela através do Terminal Linux. 

 

## Como usar 

Para usar o programa, basta o arquivo "index.c" e um compilador para fazê-lo funcionar na máquina. 

O código foi desenvolvido em ambiente Linux, no entanto, pode ser executado em outros ambientes, só é importante verificar a atuação de alguns comandos como o sleep(1) ou o system("clear") que são próprios do SO Linux. 

 

## Observação 

Vale ressaltar que apenas as funções “Cadastrar” e “Listar” estão funcionando corretamente. Já nas outras funções orientam o usuário a realizar o que se pede de forma manual. 

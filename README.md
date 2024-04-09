1 - Desafios Python: O grande depósito

Descrição do sexto desafio: Você foi contratado por um banco para desenvolver um programa que auxilie seus clientes a realizar depósitos em suas contas.
O programa deve solicitar ao cliente o valor do depósito e verificar se o valor é válido. Se o valor for maior do que zero, o programa deve adicionar o valor ao saldo da conta.
Caso contrário, o programa deverá exibir uma mensagem de erro. O programa deve solicitar apenas uma vez o valor do depósito.

Entrada
O programa deve utilizar o Scanner para receber o valor do depósito digitalizado pelo cliente. Os valores podem ser decimais, representando valor em reais.

Saída
O programa deve exibir uma mensagem de sucesso quando um valor de depósito válido para informado e o saldo da conta para atualizado.
Se o valor for "0", deverá imprimir uma mensagem encerrando o programa. Caso um valor inválido seja digitado, o programa deverá exibir uma mensagem de erro solicitando um novo valor.

    print("Encerrando o programa...")
   
else:
    print("Valor invalido! Digite um valor maior que zero.")

"Valor invalido! Digite um valor maior que zero."


2 - Desafios Python: Organizando seus ativos

Descrição do terceiro desafio: Após uma análise cuidadosa realizada pela equipe de desenvolvimento de uma empresa bancária, foi identificado a necessidade de uma nova funcionalidade para otimizar os processos e melhorias da experiência dos usuários. Agora, sua tarefa é implementar uma solução que organize em ordem alfabética uma lista de ativos que será informada pelos usuários. Os ativos são representados por strings que representam seus tipos, como por exemplo: Reservas de liquidez, Ativos intangiveis e dentre outros.

Entrada
A primeira entrada consiste em um número inteiro que representa a quantidade de ativos que o usuário possui. Em seguida, o usuário deverá informar, em linhas separadas, os tipos (strings) dos respectivos ativos.

Saída
Seu programa deve exibir a lista de Ativos organizada em ordem alfabética. Cada ativo deve ser apresentado em uma linha separada.

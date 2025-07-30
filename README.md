Este é um sistema bancário simples implementado em Python, que permite aos usuários realizar operações básicas como depósito, saque, visualização de extrato, criação de novos usuários e contas bancárias.

Funcionalidades

O sistema oferece as seguintes funcionalidades:

•
Depósito: Adiciona um valor ao saldo da conta.

•
Saque: Retira um valor do saldo da conta, respeitando um limite diário de saques (3) e um limite máximo por saque (R$ 500).

•
Extrato: Exibe todas as movimentações da conta e o saldo atual.

•
Novo Usuário: Permite o cadastro de um novo usuário com CPF, nome completo, data de nascimento e endereço.

•
Nova Conta: Cria uma nova conta bancária vinculada a um usuário existente (identificado pelo CPF).

•
Listar Contas: Exibe todas as contas cadastradas no sistema.

Como Executar

1.
Salve o código: Salve o código Python fornecido em um arquivo chamado main.py.

2.
Execute o arquivo: Abra um terminal ou prompt de comando, navegue até o diretório onde você salvou o arquivo e execute o comando:

Exemplos de Uso

Ao executar o programa, um menu será exibido. Você pode interagir com o sistema digitando as opções correspondentes.

Plain Text


================ MENU =================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=> 


Exemplo de Criação de Usuário e Conta

1.
Criar Usuário: Digite nu e siga as instruções:

2.
Criar Conta: Digite nc e informe o CPF do usuário:

Exemplo de Depósito e Saque

1.
Depositar: Digite d e informe o valor:

2.
Sacar: Digite s e informe o valor:

Exemplo de Extrato

1.
Extrato: Digite e:

Estrutura do Código

O código é organizado em funções para cada operação, facilitando a manutenção e a leitura:

•
menu(): Exibe o menu de opções.

•
depositar(): Lida com a operação de depósito.

•
sacar(): Lida com a operação de saque, incluindo validações de limite e número de saques.

•
exibir_extrato(): Mostra o extrato da conta.

•
criar_usuario(): Cadastra um novo usuário.

•
filtrar_usuario(): Função auxiliar para buscar um usuário pelo CPF.

•
criar_conta(): Cria uma nova conta bancária.

•
listar_contas(): Lista todas as contas cadastradas.

•
main(): Função principal que orquestra o fluxo do programa.


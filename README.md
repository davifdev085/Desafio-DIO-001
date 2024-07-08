# Desafio-DIO-001
# Registro de Transações Bancárias em Java

Este programa simples em Java permite ao usuário registrar transações bancárias, calcular o saldo final da conta e exibir todas as transações realizadas.

## Funcionalidades

1. **Entrada de Dados**:
   - O programa solicita ao usuário informar o saldo inicial da conta.
   - Em seguida, solicita o número total de transações que o usuário deseja realizar.

2. **Entrada de Transações**:
   - Para cada transação, o programa solicitará ao usuário:
     - O tipo de transação: Digite 'D' para depósito ou 'S' para saque.
     - O valor da transação.

3. **Saída**:
   - Utilizando listas (ArrayList ou LinkedList), o programa armazenará cada transação, que incluirá um tipo (Depósito ou Saque) e um valor.
   - Ao final das transações, o programa exibirá o saldo final da conta e a lista de transações.

## Exemplos

### Exemplo 1:

#### Entrada:

2500
2
D
100
S
500

#### Saída Esperada:

Saldo: 2100.0
Transações:

Depósito de 100.0
Saque de 500.0

### Exemplo 2:

#### Entrada:
900
1
S
100

#### Saída Esperada:
Saldo: 800.0
Transações:

Saque de 100.0

### Exemplo 3:

#### Entrada:
0
0
#### Saída Esperada:
Saldo: 0.0
Transações: Nenhuma transação realizada.

## Executando o Programa

1. **Compilação**: Para compilar o programa, certifique-se de ter o JDK instalado e execute o comando:
javac RegistroTransacoesBancarias.java


2. **Execução**: Após compilar, execute o programa com o comando:
java RegistroTransacoesBancarias


3. **Instruções de Uso**: Siga as instruções na linha de comando para fornecer as entradas necessárias conforme solicitado pelo programa.

## Notas

- Certifique-se de testar o programa com os exemplos fornecidos e com outros casos possíveis para garantir seu correto funcionamento.


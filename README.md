<div align="center">
<img src="https://hermes.digitalinnovation.one/assets/diome/logo-full.svg" alt="Logo Bootcamp" width="80">
<h1> Coding The Future Vivo <br> Python AI Backend Developer </h1>
<img src="https://hermes.dio.me/files/assets/ef695d25-f647-45eb-b1ad-a25c124b28ca.png" alt="Logo Bootcamp" width="220">
</div>
 
 <h1 align="center"> Sistema Bancário em POO com Python </h1>

Este é um desafio de projeto do **Coding The Future Vivo - Python AI Backend Developer** 

Desafio: Modelando o Sistema Bancário em POO com Python

**Funcionalidades** 🛠️

## Cliente 👤
A classe `Cliente` representa os clientes do banco. Cada cliente possui um endereço e pode ter uma ou mais contas bancárias associadas.

## Pessoa Fisica 🧑
A classe `PessoaFisica` é uma subclasse de `Cliente`, que adiciona atributos específicos para representar pessoas físicas, como nome, data de nascimento e CPF.

## Conta 💰
A classe `Conta` representa uma conta bancária. Cada conta possui um número, uma agência, um saldo, um cliente associado e um histórico de transações. As contas podem ser de diferentes tipos, como conta corrente ou poupança.

## Conta Corrente 🏦
A classe `ContaCorrente` é uma subclasse de `Conta`, que adiciona atributos específicos para contas correntes, como limite de saldo e limite de saques.

## Transacao 🔄
A classe abstrata `Transacao` representa uma transação bancária. Possui métodos abstratos para realizar e registrar transações.

## Saque 💸 e Deposito 💳
As classes `Saque` e `Deposito` são subclasse de `Transacao`, que representam transações de saque e depósito, respectivamente. Elas implementam os métodos abstratos de `Transacao`.

## Data e Hora 🕐
O projeto utiliza uma implementação robusta de data e hora, que não apenas registra transações com precisão, mas também apresenta essas informações de forma clara e organizada, permitindo aos usuários uma compreensão instantânea das atividades em suas contas

## Implementação do Log e do log.txt 💾
O projeto inclui uma funcionalidade de log para registrar eventos importantes, como a criação de novos clientes e contas. O log é feito utilizando o módulo logging do Python e é armazenado no arquivo log.txt. Cada registro no arquivo de log contém informações detalhadas, incluindo o tipo de operação realizada, o nome do cliente, o número da conta e a data e hora em que a operação ocorreu. Isso oferece uma forma organizada e fácil de rastrear as atividades dentro do sistema bancário, proporcionando transparência e controle sobre as operações realizadas.

## Dependências 🔧

Este projeto utiliza a biblioteca `colorama` para adicionar cores ao terminal. Para instalar essa biblioteca, execute o seguinte comando no terminal:

`pip install colorama`

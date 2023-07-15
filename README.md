<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>Menu de Controle de Conta Bancária</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f7f7f7;
      margin: 0;
      padding: 20px;
    }

    h1 {
      color: #333;
      text-align: center;
    }

    p {
      color: #666;
      margin-bottom: 10px;
    }

    ul {
      list-style-type: disc;
      padding-left: 20px;
    }

    li {
      margin-bottom: 10px;
    }

    pre {
      background-color: #f9f9f9;
      padding: 10px;
      border: 1px solid #ddd;
      border-radius: 5px;
    }

    .contribution {
      margin-top: 20px;
      font-size: 14px;
      color: #888;
    }

    .contribution a {
      color: #888;
      text-decoration: none;
    }

    .license {
      margin-top: 20px;
      font-size: 14px;
      color: #888;
    }

    .license a {
      color: #888;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <h1>Menu de Controle de Conta Bancária</h1>
  <p>Este repositório contém um código Python para controlar operações básicas de uma conta bancária, como depósito, saque e exibição do extrato.</p>

  <h2>Opções Disponíveis:</h2>
  <ul>
    <li><strong>Depositar (d):</strong> Permite realizar um depósito na conta. O valor informado deve ser positivo e será adicionado ao saldo da conta. O valor do depósito será armazenado no extrato da conta.</li>
    <li><strong>Sacar (s):</strong> Permite realizar um saque da conta. O valor informado deve ser positivo e não pode exceder o saldo disponível na conta nem o limite de saques diários. O valor do saque será subtraído do saldo da conta. O valor do saque será armazenado no extrato da conta.</li>
    <li><strong>Extrato (e):</strong> Exibe o extrato da conta, que contém a lista de todas as movimentações (depósitos e saques) realizadas. Também exibe o saldo atual da conta.</li>
    <li><strong>Sair (q):</strong> Encerra o programa.</li>
  </ul>

  <h2>Execução:</h2>
  <p>Para executar o código, basta rodar o script Python em um ambiente compatível com a versão 3.x do Python. Certifique-se de ter o interpretador Python instalado em sua máquina.</p>
  <p>Ao iniciar o programa, será exibido um menu com as opções disponíveis. Digite a letra correspondente à operação desejada e siga as instruções fornecidas.</p>
  <</body>
</html>

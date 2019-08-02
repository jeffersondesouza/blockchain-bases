# Estudo de Blockchain
  - Em uma transferênica bancária por exemplo, garantimos que uma Conta A pode transferir para uma Conta B avaliando o seu HISTÓRICO de transações, e com isso garantindo se ele possui ou nao fundos;
  - Essa havaliação é feita pelo Banco;
  - Podemos com o Blockchain retirar o banco da jogada e ainda sim garantir a validade da informação;
  - Por garantir a validade da informação podemos usar o Blockchain para garantir que uma número é meu (bitcoin resumido), uma música é minha, um documento é meu etc   

### Double Spending
  - A possibilidade de se "gastar" um mesmo valor duas vezes. Por exemplor mandar o mesmo crédito de dinheiro para duas pessoas;
  - A ideia é impedir tal Conflito de Interesses;

### Entidade Mediadora
  - Banco por exemplo;
  - Garantir a validade da informação;
  - Garantir que informações uma vez criadas nao sejam alteradas;
  - Podemos retirar essa entidade mediadora

### Consenso distribuído
  Imaginando a seguite situação: "A" transfere 100 para "B" que transfere esses 100 para "C". em seguida "B" (que n tem mais nada) transfere 100 para "D", como garantir esse histórico?

  - Um participante A ao transferir uma informação para B deve notifica os demais (número consuderável) de participantes e estes avaliarem se essa transação é possível.  
  - Se a rede de participantes aprovam uma transação, então há o Concenso da Rede (assim a rede diria que B nao pode trnasferir para D);
  - Informações nunca são alteradas ou removidas do histórico, apenas adicionadas;
  - O histórico de operações é algo estilo "append only". Você só adiciona informações, nunca remove nem altera.
# IntegracaoPagseguro

Esta página HTML possui um script que fará uma chamada a API de testes do Pagseguro. 

O script fará um POST na api passando os parametros de autenticação e informações de pagamento. 

A chamada à API é feita pelo botão Pagar! (aguardar alguns segundos após clicar).

O preço do pagamento deve estar na página HTML, neste exemplo o valor é de 100.00 e deve estar em um elemento de id="booking-price".

IMPORTANTE: se a chamada falhar, este script não faz nada. (sem validação)

Após fazer a chamada uma janela do Pagseguro abrirá solicitando os dados de pagamento da reserva. 

Estes dados já existem e se encontram no arquivo ./paymentInputs.txt neste repositório.

Após o pagamento, um log é printado no console do Browser. 

TODO: Informar o sistema 2 que este pagamento foi concluido, alterando o estado para 'pago'. 


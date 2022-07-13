# BigDataCorp_Assessment

## Ideia para a solução

Minha resposta para esse desafio é colocar os clientes em filas por ordem de chegada e garantir que quando iniciado o processo de compra o cliente não perderá o ingresso
para outro cliente mais rápido.

Quando em processamento o ingresso está reservado e não será vendido para outro cliente até o término do processo de compra. Caso o processo de compra deja cancelado
o ingresso volta a ser disponível para compra para outros clientes.

Foi adicionado também um sistema de filas: quando um ingresso se tornar disponível, o primeiro da fila ganha acesso a ele e tem sua chance de realizar a compra.

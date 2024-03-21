# Contrato do Token DIO

Este é um contrato inteligente para o Token DIO (DIOToken) implementado em Solidity. O Token DIO segue o padrão ERC-20 e fornece funcionalidades básicas de transferência de tokens, aprovação de gastos e transferências seguras.

## Detalhes do Contrato

- **Nome do Token**: DIO Coin
- **Símbolo do Token**: DIO
- **Decimais**: 2
- **Total Supply Inicial**: 1000000

## Funcionalidades Implementadas

- **totalSupply()**: Retorna o total de tokens em circulação.
- **balanceOf(address tokenOwner)**: Retorna o saldo de tokens de um determinado endereço.
- **allowance(address tokenOwner, address spender)**: Retorna a quantidade de tokens que o endereço `spender` está autorizado a gastar em nome do endereço `tokenOwner`.
- **transfer(address to, uint tokens)**: Transfere `tokens` para o endereço `to` se o saldo do remetente for suficiente.
- **approve(address spender, uint tokens)**: Permite que o endereço `spender` gaste `tokens` em nome do remetente.
- **transferFrom(address from, address to, uint tokens)**: Transfere `tokens` do endereço `from` para o endereço `to`, desde que o endereço `from` tenha autorizado o endereço `msg.sender` a gastar esses tokens.

## Implantação

O contrato pode ser implantado em qualquer ambiente compatível com a Ethereum. Certifique-se de fornecer o suprimento inicial desejado ao implantar o contrato.

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir problemas ou enviar solicitações pull para melhorias.

## Autor

Este contrato foi desenvolvido por Nayum Teixeira.

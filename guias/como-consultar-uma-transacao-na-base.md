# Como consultar uma transação na Base

Você pode consultar uma transação pública pelo [BaseScan](https://basescan.org/) sem conectar uma carteira.

## Encontre a transação

1. Na atividade da sua carteira, abra os detalhes da operação e copie o **hash da transação**. É o identificador que costuma aparecer como `Tx Hash` ou `Transaction ID`.
2. Abra o BaseScan, cole o hash na busca e selecione o resultado. Este guia usa a Base Mainnet. Para operações na rede de teste, use o [explorador da Base Sepolia](https://sepolia.basescan.org/).

## Leia os campos principais

| Campo | O que conferir |
| --- | --- |
| **Status** | `Success` indica que a execução foi bem-sucedida. `Pending` indica que a transação ainda aguarda inclusão em um bloco. `Failed` indica falha na execução, que ainda pode ter consumido taxa. |
| **From** | Endereço que enviou a transação. |
| **To** | Endereço que recebeu a chamada. Pode ser uma carteira ou um contrato. |
| **Value** | Valor em ETH enviado diretamente na transação. Em uma transferência de token, esse campo pode mostrar zero. Confira a seção de transferências de tokens para ver o ativo, o valor e o destinatário. |
| **Transaction Fee** | Taxa paga pela transação, exibida em ETH. |

Por exemplo, em uma transferência de USDC, o campo **To** pode apontar para o contrato do token. Para identificar quem recebeu o USDC, confira a transferência listada na seção de tokens.

Se a busca não encontrar a transação, confira se copiou o hash completo e se abriu o explorador da mesma rede usada pela carteira.

[Voltar ao diário da CartilhaCripto](../README.md)

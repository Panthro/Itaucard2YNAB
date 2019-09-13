Itaucard2YNAB
=============

Motivação
=============
https://www.facebook.com/itau/posts/769948679701112

Se você como eu sofre tentando importar seus dados do cartão de crédio Itau Card no YNAB (ou em qualquer outro software de gerenciamento de finanças), então agora você tem uma página pra te ajudar.

Como funciona?
=============
1. Basta fazer login no site do itau, navegar até a fatura do cartão que deseja importar.
2. Selecionar Todo o bloco de texto, como no exemplo abaixo:
```
Lançamentos nacionais
<SEU NOME> (0000)
DATA	MOVIMENTAÇÃO	VALOR EM R$
22/04	COMERCIO 1 09/12	13,50
Crédito do cartão final (0000)	0,00
Débito do cartão final (0000)	xx,xx

Lançamentos internacionais
RAFAEL ROMAN (0000)
DATA	MOVIMENTAÇÃO	VALOR EM R$
03/04	Loja 1	22,31
 	UNITED STATES	xx,xx (U.S.DOLLAR)
04/04	IOF COMPRA INTERNACIONA	3,89
 	 	x,xx (U. S. DOLLAR)
Crédito cartão final (0000) em R$	0,00
Total retiradas exterior em R$	0,00
Total transações inter. em R$	xx,xx
Repasse de IOF em R$	xx,xx
Total dos lançamentos inter. em R$	xx,xx
Dólar de conversão	x,xx
```

3. Acessar a ferramenta [___aqui___](https://rawgit.com/Panthro/Itaucard2YNAB/master/convert.html)

4. Colar o texto da fatura copiado no passo 2 na textarea da __Esquerda__
5. Clicar na textarea da ___Direita___
6. Salvar o conteúdo da caixa da ___Direita___ em um arquivo com a extensão ___.csv___
7. Importar no YNAB (ou em qualquer outro software que aceite CSV como formato de importação)

Compras parceladas
=================
No momento as compras parceladas são tratadas como entradas na sua fatura, fica a seu critério apagá-las ou não de acordo com a forma que você usa o YNAB.

___Happy Ynabing___

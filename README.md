# mrMLM
Realizando análises de alguns métodos GWAS multilocus para identificar SNPs, incluindo alguns método mrMLM que tem alta velocidade computacional, alta potência e precisão, e baixa taxa de falsos positivos.

Disciplina: Genômica Aplicada ao Melhoramento de Plantas, ministrada pela Profa. Dra. Maria Celeste e Dra. Sthephanie Alves. 

Para melhor aprendizado foi feito um estudo de associação genômica multilocus sob a estrutura do modelo linear misto multilocus aleatório-SNP-efeito (mrMLM). Primeiramente, cada marcador no genoma é escaneado para os seis primeiros métodos, enquanto testes de Wald vetorizados, juntamente com a seleção ótima de variáveis, são conduzidos para identificar marcadores potencialmente associados para BLUPmrMLM. A correção de Bonferroni é substituída por um critério de seleção menos rigoroso para o teste de significância. Em seguida, todos os marcadores potencialmente associados à característica são incluídos em um modelo genético multilocus, seus efeitos são estimados por Bayes empírico e todos os efeitos diferentes de zero são posteriormente identificados pelo teste da razão de verossimilhança para QTL significativo. 

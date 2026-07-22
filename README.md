# Otimização da Compressão Wavelet de Sinais como Problema da Mochila Binária

Este repositório contém o código e o artigo desenvolvidos para a disciplina "Projeto de Algoritmos" do curso de Engenharia de Computação da UTFPR campus Pato Branco.

## Motivação e resumo do trabalho

A compressão de sinais por Transformada Wavelet Discreta constitui uma alternativa eficiente para reduzir a quantidade de dados armazenados, 
preservando as
principais características do sinal original. Entretanto, a seleção dos coeficientes Wavelet mais relevantes sob restrições de armazenamento pode ser modelada como um problema de
otimização combinatória do tipo mochila binária, pertencente à classe NP-difícil. Neste trabalho, são avaliados três métodos para a seleção de coeficientes wavelet: um algoritmo guloso, 
uma heurística de refinamento por Descida em Vizinhança Variável (DVV) e a meta-heurística Simulated Annealing. Os experimentos foram realizados com a utilização de sinais sintéticos com 
1000 amostras e diferentes níveis de compressão, correspondentes ao armazenamento de 50, 250 e 500 coeficientes Wavelet. O desempenho dos algoritmos foi avaliado por meio da Raiz do 
Erro Quadrático Médio (RMSE) entre o sinal original e o sinal reconstruído, bem como pelo tempo de execução. Os resultados obtidos evidenciam as vantagens e limitações de cada abordagem ao 
comparar a qualidade das soluções e o custo computacional associado à compressão.

## Arquivos
- [Artigo](./Otimizacao_da_Compressao_Wavelet_de_Sinais_como_Problema_da_Mochila_Binaria.pdf)
- [Código](./Main.ipynb)

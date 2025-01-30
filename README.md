# Laboratório de Estúdio de Fala no Azure IA - Análise de sentimentos em textos

Nesse projeto foram utilizados como inputs textos de opiniões sobre estabelecimentos/locais. Procurei variar entre sentimentos e idiomas, a fim de testar se o programa é bem adaptativo e eficiente. 

### Inputs:

1. O primeiro texto é uma análise negativa de uma hospedagem em um hotel no Guarujá (em português);
2. O segundo trata de uma opinião positiva sobre um restaurante visitado na Itália (em inglês);
3. O terceiro texto é sobre uma opinião neutra de um parque de diversões, ou seja, apontando pontos bons e ruins (em espanhol);

### Resultados e Conclusões

1. 7% POSITIVO / 0% NEUTRO / 93% NEGATIVO : resultados satisfatórios;
2. 99% POSITIVO / 1% NEUTRO / 0% NEGATIVO : resultados satisfatórios;
3. 95% POSITIVO / 1% NEUTRO / 4% NEGATIVO : resultados insatisfatórios, era esperada uma certa igualdade entre positivo e negativo, ou 90-100% neutro;

As conclusões são de que o programa traduz bem e trabalha bem quando se trata de textos claramente positivos ou negativos, mas que apresenta erros de interpretação ao analisar textos neutros, pois foca nos pontos bons e ignora os ruins.

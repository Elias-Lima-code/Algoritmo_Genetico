# Algoritmo-Genetico

Criado por [Elias Lima](https://github.com/Elias-Lima-code) 
e [Pedro Barros](https://github.com/Pedro-Barros77)
para fins de prática e estudos em Inteligência Artificial.
> (UNA - 'Sistemas de Informação' e 'Gestão de Tecnologia da Informação')


Primeira versão em 24-09-2022


## Como funciona?

O algorítmo utiliza do modelo evolutivo de Charles Darwin, onde os melhores/mais fortes prevalecem e os mais fracos desaparecem do ecossistema.
Através de cruzamento genético e mutações, a IA consegue aprimorar os genes de cada cromossomo até que alcance o valor desejado.

Os parâmetros são customizáveis:

TOTAL_POPULATION = 50
TOTAL_GENES = 5
TARGET_PERCENTAGE = 0.98
CHOSEN_PERCENTAGE = 0.3
MUTATION_PERCENTAGE = 0.01
MIN_SUCCEEDED = 1

Resultado:

![Resultado obtido no console](https://user-images.githubusercontent.com/85514585/192126530-0ee34ed2-aaad-4e4d-bf4e-e43a11e440a3.png)


A Heurística utilizada foi simplesmente somar todos os valores dos genes, sendo assim quanto maior o valor mais perto do ideal está.
Dentre os nossos planos estão:
- [x] Adicionar personalização do intervalo de valores possíveis para os genes
- [ ] Adicionar personalização da Eurística (soma, subtração, multiplicação, numeros primos, numeros ímpares, números pares, divisíveis por X
- [x] Criar interface gráfica amigável para o usuário e para acompanhamento do processo e de estatísticas

:green_circle: Uso e implementação livre, favor incluir os devidos créditos

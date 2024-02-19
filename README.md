# Otimizacao-algoritmo-genetico

## Inicialização:

- Define o número de gerações (numGeracoes) como 50.
- Inicializa a população com uma população inicial (populacaoInicial).

## Loop de Gerações:

- Para cada geração (iteração do loop for i in range(numGeracoes)):
- Calcula o fitness da população atual (fitnessPopulacaoAtual) usando a função calculaFitness.
- Seleciona os pais para reprodução com base no fitness.
- Realiza o cruzamento dos pais para gerar filhos.
- Avalia se os filhos sofrerão mutação.
- Identifica a posição do cromossomo com menor aptidão (fitness) na população atual.
- Se o fitness do filho for maior que o fitness do cromossomo com menor aptidão, substitui o cromossomo pelo filho.
- Repete o processo para o cromossomo com a segunda menor aptidão.
- Recalcula o fitness da população após as substituições.

## Resultado Final:

### O resultado final é o cromossomo da primeira posição da população (populacao[0]), que representa a solução otimizada encontrada pelo algoritmo.
Esse código é uma implementação básica de um algoritmo genético e pode ser adaptado para resolver diferentes problemas de otimização. A estratégia de elitismo (substituir os cromossomos menos aptos pelos filhos) é comum para melhorar a convergência do algoritmo.

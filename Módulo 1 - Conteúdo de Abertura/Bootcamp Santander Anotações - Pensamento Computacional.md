# Bootcamp Santander Anotações:

**Habilidades Complementares.**

**Habilidades:**

- **Raciocínio Lógico**
Classificação:
*indução* -> vem a partir de um fenomeno observado -> Leis e Teorias
*Dedução* -> Trabalho inverso de indução 
*Abdução* -> a partir de uma conclusão você tira uma premissa, observado supõe outra coisa, ex: A grama esta molhada, logo deve ter chovido. 

- **Aperfeiçoamento**

**Melhoramento** 
Ato de aperfeiçoar -> Melhor uso de recursos: Encontrar solução eficiente e Otimizar processos.
Melhorar códigos e algoritmos: simplificar linhas de códigos e ter funções bem definidas.

**Aprimoramento**

A partir de uma solução, determinar pontos de melhora e refinamento.

**(Treinar Raciocínio Lógico)** 



## Pilares: Decomposição:

**Primeiro passo da resolução de problemas dentro do conceito de pensamento computacional**

**"Dado um problema complexo, devemos quebra-lo em problemas menores. Portanto, problemas mais fáceis e gerenciáveis."**

**Estratégia ->** Quebrar em partes menores e gerenciáveis -> Analisar: Estudar e explorar, realizar exame detalhado e decompor em elementos constituintes.

**Outra estratégia ->** Combinar os elementos recompondo o problema original -> Síntese: processo de reconstrução, fundir os elementos de maneira coerente e consistir em reunir elementos distintos em um único elemento.

**Execuções dependem do contexto: Sequencial ou Paralelo.** 

**Como decompor?** 
**Identificar ou coletar dados > Agregar os dados > Funcionalidade**





## Pilares: Padrões 

**Reconhecimento de Padrões**

*Modelo Base*
*Estrutura Invariante*
*Repetição*

**Como reconhecer padrões no contexto computacional:**

Através de similaridades e diferenças entre os contextos e objetos. 

exemplo são as fotos comprimidas nas redes sociais.

**Compressão de dados:**

3 campos em azul e são representados com um campo em azul numerado como 3. depois um campo representado com o numero 2 em verde e etc.

**Por que determinar padrões?**

Generalizar, com objetivo de obter resolução para problemas diferentes. 

Através de Classes e Categorias

Categorias vão depender do domínio e tipo de mídia

**Como o computador reconhece padrões?**

Por Comparação 

Representação de atributos >
Aprendizado - conceito associado ao objeto > Armazenar dados > Regras de decisão

A Detecção de padrão ela vem da ideia de você extrair características afim de classificar seus dados, esse é o tipo de abordagem.

diferentes métodos de reconhecimentos de padrão e aplicar em varios contextos. 

aplicações em varias áreas de conhecimentos:

Classificação de dados
Reconhecimento de imagem
Reconhecimento de fala
Análise de cenas
Classificação de documentos

Dentro da computação:

Rede Neural
Inteligência Artificial 
Machine Learning
Ciência de dados.

## Pilares: Abstração

**O que é abstrair?:** Observar, um ou mais elementos, avaliando características e propriedades em separado

dado um elemento, analisar suas características.

**O que é abstração?:** Processo intelectual de isolamento de um objeto da realidade 

extrapolar um objeto do mundo concreto para o mundo decibéis.

**O que é generalizar?:** Torna-se geral, mais amplo, extensão.

pegar elementos principais de um determinado objeto, extrapolar pro mundo abstrato e torna-lo geral.

**Generalizar na logica:** 

é a operação intelectual que consiste em reunir numa classe geral, um conjunto de seres ou fenômenos similares.

**Como classificar os dados?**

Características
Pontos Essenciais
Generalizar x Detalhar

**Representação de dados:**

exemplo: 

Características de Estudantes:

Nome completo, Matrícula, Endereço, campus e etc -> =  **Pontos Essenciais** 

Trabalho, tem filhos, programa preferido e etc -> **= Detalhes (deixado de lado)**

**Dentro da computação:** 
Conceitos baseados em abstrações:
Merge sort, Clusteting e Busca binária.

**Estrutura de dados:**
Arvore, Lista e Grafos

Máquinas de estado finito e Linguagens de programação.

**Estrutura de paralelismo:**

Dados > Distribuído pelos Core/Clusters > Reconstituídos > Processado

**Arquiteturas:**

Estrutura em camadas. (TCP IP e etc)



## Pilares: Algoritmos

**Computador não resolve problemas sozinho.**

**Precisa de Instruções detalhadas** 
são usadas no processamento dos dados através dos programas.

Programas constituídos por instruções por passo a passo.

**"step by step" - passo a passo**

para determinar as instruções:

O que precisa ser feito? > qual a ordem de execução?

Algoritmo entendido por humano e maquina

**Desenvolvimento de programa:**

Análise e estudar e definir quais são as 
entradas e saidas.

**Algoritmo**
Descreve o problema por meio de ferramentas narrativas, fluxograma ou pseudocodigo.

**Codificação**
O algoritmo é codificado de acordo com a linguagem de programação escolhida.

Sequencia de passos com objetivo definido > Execução de tarefas específicas > Conjunto de operações que resultam em uma sucessão finita de ações.

**Como construir um algoritmo?**

Compreensão do problema
Definição dados de entrada
Definir processamento
Definir dados de saída
Utilizar um método de construção
Teste e diagnóstico. 

**Construção de algoritmos**

**Narrativa:** Utilização de linguagem natural > sem conceitos novos e diversas interpretações possíveis.

**Fluxograma:** Utilização de símbolos pré-definidos > simples entendimentos > Conhecimento prévio da estrutura e símbolos

**Pseudocódigo**> Portugol > Regras definidas > Passos a serem seguidos (mais próximo de codificação) 



### Estudo de caso conceitual: perdido

**como resolver o problema utilizando o pensamento computacional?**

*Identificar mecanismos*
*Recursos comuns* 
*Detalhes mais importantes*

**"Para sobreviver numa floresta necessita-se de água > comida e abrigo."** 

O problema "sobrevivência" está decomposto em problemas menores > decomposição original do problema

Se decompondo ainda mais, o fogo vai se repetir nos subproblemas. (Padrão)

Decomposição
Reconhecimento de padrões
Abstração

Próximo passo é determinar instruções (exemplo: preparar a comida)

Encontrar água 
Construir Abrigo 
Maximizar chances de resgate 

**Todos os pilares de computação foram usados no exemplo.** 





### Estudo de caso aplicado: Soma de um intervalo

*dado o maior numero e o menor numero: decrementar o maior e incrementar o menor e somar.*

**exemplo:** 
200 + 1 |
199 + 2 | **Decomposição**
198 + 3 |
197 + 4 |

**e se torna padrão:**
200 + 1 = 201
199 + 2 = 201
198 + 3 = 201
197 + 4 = 201

se tornando uma constante, um valor que se repete em todas as operações.

**Como expressar de forma generalista?**
utilizando abstração

Exemplo: quantas vezes o valor 201 vai se repetir?

já que esta sendo usado dois números a cada soma (200 + ..) 200 vai ser divido por dois:

200/2 = 100 
201 vai ser multiplicado por 100 (que é o numero de repetições)

resultando em 20.100

Expressar em variáveis:
Exemplo: soma de nº entre x e y.

[x, y] -> intervalo (1 e 200)


resultado parcial vai ser resultado de x + y (x+y = resultado_parcial)

e a cada nova interação, decrementar y (y-1)
e encrementar x (x+1)

(y-1) + (x+1) = resultado_parcial 

equivalente a 200 +1 = 201
199 + 2

(poderia ser usado "FOR" como estrutura de repetição) 

então o total x resultado parcial = resultado

100 x 201 = 20.100

y/2 = total (200/2 = 100)

utilizamos decomposição, reconhecimento de padrão e abstração.

**ultimo passo é ser transformado em algoritmo:**

passo 1 - recebe os valores (x e y)
passo 2 - resolva: y/2 = total
passo 3 - resolva: y+x = resultado_parcial
passo 4 - ache o total final = total x resultado_parcial
passo 5 - imprima o resultado

 
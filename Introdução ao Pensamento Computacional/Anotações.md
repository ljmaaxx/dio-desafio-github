# Introdução ao Pensamento Computacional

### Aula 1

**Conceito:** processo de pensamento envolvido na expressão de soluções em passos computacionais, ou algoritmos que podem ser implementados pelo computador. Humanos e máquinas deverão ser capazes de resolver.

- Dividir um problema complexo em subproblemas: 4 pilares

- Decomposição -> reconhecimento de padrões -> abstração -> design de algoritmos

- Quebra-cabeças: subgrupos de pecinhas parecidas é mais rápido do que comparar 1 a 1.

- Quando estiver programando um algoritmo sempre lembrar da importância da eficiência, ou seja, pensar no melhor e no pior caso

- Um algoritmo deve sempre passar pelo ciclo de refinamento teste e análise até o infinito - > sempre podemos melhorar

- Raciocínio lógico é uma questão de prática

## Pilar 1: Decomposição

_"Se você não consegue resolver um problema provavelmente a um problema menor que você consegue resolver"_

- Quebrar e recompor 
- computação paralela -> mais eficiência e menos tempo 
- maneiras distintas de decompor o mesmo problema

### Processo de Decomposição 

1. Identificar ou coletar dados 
2. Agregar os dados
3. Funcionalidade, ou seja resultado

- Pensar no funcionamento de uma bike

**- Vantagens da decomposição:** como você quebra o código em vários segmentos que juntos resolvem o problema, se você alterar uma parte, reflete em todas, além de que se for necessário fazer alguma mudança será pontual.

- Por que determinar padrões? Generalizar com o objetivo de obter resolução para problemas diferentes

- Padrões serve para a extração de características para classificação de dados

**- Aplicações:** classificação de dados reconhecimento de imagem, reconhecimento de fala, análise de cenas, classificação de documentos

**Áreas:** _machine learning_, redes neurais, IA, ciência de dados

## Pilar 2: Abstração

- Abstrair:  observar um ou mais elementos avaliando características e propriedades em separado

**Abstração:** processo intelectual de isolamento de objeto da realidade. Abstrair significa generalizar -> generalizar na lógica: operação intelectual que consiste em reunir numa classe geral, um conjunto de seres ou fenômenos similares

- Generalizar ao invés de detalhar -> verificar semelhanças gerais

**- Focando em tornar a solução do problema reutilizável**

## Pilar 3: Algoritmos

**- Passo a passo**

**Como construir um algoritmo:**

1. Compreensão do problema
2. Definição dos dados de entrada
3. Definir processamento
4. Definir dados de saída
5. Utilizar método de construção
6. Teste e diagnóstico

_Narrativa -> fluxograma -> pseudocódigo_

# Estudo de caso conceitual: Perdido

_Imagine que você está perdido em uma floresta como utilizar a sua chances de sobreviver utilizando algoritmos o 1º problema seria sobrevivência se você de compor sobrevivência ela será transformada em tres novos problemas água comida e abrigo se você continuar a de composição será uma 3ª camada de problemas água pode vir da Chuva ou da nascente A comida pode ser completada ou caçada ao abrigo pode ser localizado de perder diante de um mapa abrigo significa proteção e abriu tem que ser quente e seco._

- O mapa pode ser também criado por abstração olhando de um ponto alto da floresta e o fernando detalhes cruciais

- Preparar a comida também pode ser um algoritmo

- Estudo de caso aplicado soma de um intervalo

### Problema 1: soma de números entre 1 e 200:

_Uma das opções que não é tão eficiente e a 1ª que você pode pensar sem muito refletir é somar cada número individualmente:

1 + 2 
1 + 3
1 + 4
.
.
.

_Porém, é possível chegar numa solução muito mais eficiente pelo seguinte raciocínio: pegar o maior número e o número mais baixo e somar. Neste caso o resultado será 201, ou seja: 

200 + 1 = 201
199 + 2 = 201
198 + 3 = 201
.
.
.

- Quantas vezes esse padrão vai se repetir? A resposta é 100 vezes, pois uma vez que 200 chegar no 100 o número 1 também chegará no 100.

**_O resultado é composto pela soma do maior número e do menor número multiplicado pelas vezes que a soma dos números se repetirá, ou seja o resultado é 201 x 100 = 20.100_**

### Algoritmo soma de intervalo

Passo 1. Receber x e y;

Passo 2. Resolva y/2 = total (número de repetições);

Passo 3. Resolva y + x = resultado_parcial;

Passo 4. Ache o total: FINAL = total + resultado_parcial;

Passo 5 Imprima o resultado;

_Mesmo vale para o Estudo de Caso Aplicado: Adivinha Número:_

_ao invés de ir de intervalo de 1 a 100 procurando cada número e perguntando se é 1,2 ou 3 deve se sempre perguntar um número maior que 50? Menor que 20? desta forma é reduzido consideravelmente o processamento_

* Uma dica para aprimorar o seu algoritmo é sempre permitir se conhecer resoluções diferentes da sua, tentar entendê-las e otimizar seu código com base nesse novo conhecimento.

# Módulo 2

* O que é lógica:  resolução de um problema (problema: questão que foi à regra desvio do percurso impossibilidade de atingir um objetivo com eficiência e eficácia.) A lógica é uma forma de pensamento estruturada -> resolve problemas -> verdadeiro ou não.

Votado à computação: organização e planejamento das instruções assertivas em um algoritmo, a fim de viabilizar a implantação de um programa


**- Programar te ensina a pensar**

## Aula 2: técnicas de lógica de programação

- Técnica linear execução sequenciado única de missão e recursos limitados dependência entre si

Acordar -> descer escada -> café -> ler jornal

- Técnica estruturada: mais de uma opção/não linear/entendimento validação e manutenção

Acordar -> descer escada -> fazer café OU fazer suco -> ler jornal

- Técnica modular: partes independentes e controladas por um conjunto de regras

## Módulo 3 tipologia e variáveis

- Função é uma forma de modularização do programa dessa forma você consegue reutilizar código

## Módulo 4: linguagens de programação

- Evolução tecnológica: hardware -> software

- Charles Babbage

- Ada Lovelace

- De Morgan

- Alan Turing

- Von Neuman

- Claude Shannon

- Válvula
- Ibm
- Relé
- Eniac
- Colossus
- Edvac
- Intel 1975
- Microsoft: linguagem basic
- Assembly
- Apple
- Cobol
- Fortran

## Aula 4: Análise de código

### Léxico + Sintático + Semântico

## Aula 5: Paradigmas da programação

- Definição formal: forma de solução de problemas com diretriz e limitações específicas de cada paradigma, utilizando linguagem de programação

- Exemplos de paradigmas: orientado ao objeto, procedural, funcional, estruturado, compilação distribuída e lógico.

**Programação orientada ao objeto:** o objeto é descrito Por características específicas, comportamentos (estados, atributos, métodos)

- Herança 
- Encapsulamento 
- Polimorfismo 
- Abstração

## -> Portugol web studio

## -> Fundamentos da programação de computadores person



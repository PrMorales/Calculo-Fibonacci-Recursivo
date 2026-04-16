# Calculo-Fibonacci-Recursivo


🚀 Recursão, Otimização e Arte Generativa com Python

Este projeto é um estudo sobre o conceito de Recursão apresentado em aula, fui um pouco além e explorei desde fundamentos lógicos e matemáticos até otimização do código e criação de imagens.


📌 Visão Geral

O projeto foi estruturado em três pilares que conectam a teoria acadêmica com as necessidades do mundo real:
- Fundamentos e Visualização: Resolução da Sequência de Fibonacci e análise de gráfico.
- Engenharia de Performance: Otimização de algoritmos através de Memoização (Cache).
- Computação Gráfica: Criação de fractais orgânicos utilizando lógica recursiva.


________________________________________________________________________________________________________________________________________________


1. 📈 Fibonacci & Análise de Dados

Nesta etapa, implementamos a sequência de Fibonacci seguindo as regras clássicas da recursão: Caso Base e Passo Recursivo.
-> Diferencial: Adicionei uma camada de visualização de dados com matplotlib.
-> Insight: O gráfico gerado demonstra o Crescimento Exponencial, permitindo prever o comportamento do algoritmo antes mesmo de executá-lo com grandes volumes de dados.


<img width="626" height="504" alt="image" src="https://github.com/user-attachments/assets/31590a09-f48a-4cfc-a0d8-09f71c18209b" />


________________________________________________________________________________________________________________________________________________


  
2. ⚡ A diferença de performance (memoização)

Aqui, exploramos o impacto da recursão na infraestrutura.
-> O Problema: A recursão simples possui complexidade $O(2^n)$, o que causa travamento do sistema (CPU Bound) ao tentar calcular valores altos como n=100.
-> A Solução: Implementamos Memoização (um dicionário para cache de resultados).
-> Resultado Prático: Reduzimos o tempo de execução para frações de segundo, demonstrando como o "Clean Code" e a escolha correta de algoritmos economizam recursos de nuvem e tempo de processamento.


<img width="400" height="67" alt="image" src="https://github.com/user-attachments/assets/ddcd7357-38ae-40e5-8dc4-f585b812ebb9" />

________________________________________________________________________________________________________________________________________________


3. 🌳 Arte Generativa: Árvore Fractal
Utilizando a biblioteca turtle (adaptada para ambientes Cloud via ColabTurtlePlus), aplicamos a recursão para desenhar uma estrutura fractal.
-> Lógica: Cada galho é uma nova chamada da função, reduzindo o tamanho e alterando ângulos, mimetizando os padrões de crescimento da natureza.
-> Desafio de Infra: Resolvemos a limitação de ambientes headless (sem tela) configurando a renderização diretamente no navegador.
   

<img width="549" height="455" alt="image" src="https://github.com/user-attachments/assets/b19e8a6d-1d79-4752-a692-4dd6b2389004" />

________________________________________________________________________________________________________________________________________________

   
🛠️ Tecnologias UtilizadasLinguagem: Python
Bibliotecas: matplotlib, ColabTurtlePlus, time.

Ambiente: Google Colab

Resolução de Problemas de Ambiente: Identifiquei por que códigos gráficos falham em servidores e aprendi a adaptar a infraestrutura para cada necessidade.
Visão de Produto: Conectei a matemática com a estética visual, entendendo como proporções áureas influenciam o design moderno.

# Faça parte!
Faça parte você também de nosso time de elite!

Temos vagas para desenvolvedores!
Estamos em uma região nobre (ao lado do Morumbi Shopping e Marketplace), repleta de bons restaurantes, pertinho do consulado americano. 
Nosso escritório ocupa o 5ºandar de um prédio novíssimo, temos um ótimo hardware (aqui todo dev tem seu laptop) e injetamos agilidade na veia (cada dia mais).

Nosso trabalho é atender com excelência. Todo desenvolvedor é convidado a incorporar o espírito Bematize: ser reconhecido por atender com qualidade máxima.
Estamos de olho no que há de melhor no futuro da tecnologia. Nosso DNA hojé é escrito em C# e SQL e nossos servidores rodam Windows - mas o que nos importa é sempre a melhor e mais inteligente solução.

Temos desafios em codar o novo e manter o legado. Nada em sistemas é arbitrário, todo mundo participa!


# Nosso desafio

Quando realizando backups de arquivos de mídia como imagens, filmes e música, um problema comum é saber quais arquivos já estão salvos e quais não estão. 
A solução simples para este problema é salvar novamente, simplesmente salve tudo sempre (backup nunca é demais). 
Esta é uma solução “OK” se você tem uma quantidade infinita de espaço para backup, mas não é uma solução tão boa se você tem espaço limitado – uma vez que você vai acabar com as mesmas velhas fotos do natal espalhadas em cinco lugares diferentes em seu abarrotado dispositivo de armazenamento.

Uma solução para acabar com todos estes arquivos duplicados, é encontrar as duplicatas e deletá-las. Claro que eu **REALMENTE** preciso confiar neste software que encontra e *deleta* os arquivos duplicados.


Em **C#**, escreva então um algoritmo para encontrar arquivos duplicados usando TDD (Test Driven Development) e um aplicativo que utilize este algoritmo.

Faça seu melhor código. Limpo, objetivo e organizado.

O aplicativo deve:
1.	Realizar a varredura nos arquivos pré-existentes, apontando duplicatas
2.	Aceitar inputs de novos arquivos, validando duplicação
3.	Fornecer opção de limpeza - “deletar” automaticamente os arquivos duplicados

Você deve:
1.  Fornecer um guia básico de uso do aplicativo (só pra gente não se perder na hora de validar)
2.  Nos contar o tempo que levou para fazer o desafio (ex: escrever no último  commit que levou um total de  3 horas e 30 minutos)


Coisas a se pensar:

- O que significa ter um arquivo idêntico ao outro? (Nome, tamanho, conteúdo, data de criação, hash?)
- Como será gerada a lista de arquivos salvos e qual armazenamento você utilizará (se é que utilizará)? (Tudo em memória, armazenará os arquivos fisicamente, um TXT ou CSV, criará uma base de dados?)
- O que você vai criar como entrada para o algoritmo? (Um simples mock ou algo do tipo, uma lista de arquivos via TXT, digitação para cada arquivo, uma tela para upload, etc)
- Como será a saída do algoritmo? (Uma lista de caminhos com arquivos duplicados ou algo diferente?)



**Para nos submeter o código, é simples: fork, code, commit, push e pull-request!**


Você pode escrever sua aplicação em .NET Core, Angular, Node.Js, Vue.Js, WebApi, NancyFX ou o que achar melhor - dentro do mundo de um desenvolvedor web .NET (C#).

Avaliaremos TODOS os PR's com todo carinho e cuidado ;)


Ps: aqui usamos *TFS* e não *Github*, mas não temos preconceitos tecnológicos!

Desafio livremente inspirado em: https://sites.google.com/site/tddproblems/all-problems-1/finding-duplicate-files

# Roteiro para elaboração do Trabalho para as avaliações A1 e A2

## Orientações Gerais

Os projetos deverão ser elaborados em grupos de dois alunos. Alunos fazendo o trabalho sozinho terão bonus de +1 ponto na nota de cada avaliação.

As entregas consistirão na entrega de um relatório escrito (em $\latex$, com template `article`) acompanhado da implementação da modelagem em repositório github referenciado no relatório. 

Os repositórios de implementação poderão ser mantidos privados no Github porém compartilhados com o Professor(@fccoelho)  e a Monitora da disciplina (@beatrizmcoimbra).

## Tema

Os trabalhos versarão sobre a modelagem da epidemia da COVID-19 em um determinado país do mundo, à escolha do(s) aluno(s). O País escolhido deverá ser indicado no `README.md` do repositório do trabalho, desde o início. Os grupos não poderão eleger países já escolhidos por outros grupos. O critério de prioridade será a data/hora do commit anunciando a escolha de país no README. Os dados sobre  epidemia do país escolhido deverão ser obtidos a partir do projeto ["Our World in data"](https://ourworldindata.org/coronavirus).

## Da Entrega

A entrega será considerada como o último commit no repositório do trabalho, antes das 17h da sexta-feira da respectiva semana de avaliação. Tanto o código fonte do trabalho em $\latex$ como o PDF com o documento compilado devem ser "pushed" para o repositório para evitar problemas de compilação do documento, resultantes de diferenças no ambiente $\latex$ do Professor e dos alunos.

## Critérios de Avaliação para a A1

Os trabalhos serão avaliados como um artigo científico. Para a A1 estes serão os elementos que deverão esta obrigatoriamente presentes no artigo de cada grupo.

* (4 pontos) Seção de ***Introdução*** descrevendo a situação da epidemia da COVID-19 no país escolhido até o momento, com a citação de pelo menos dois artigos.
* Breve resumo de pelo menos 3 trabalhos de modelagem matemática da epidemia no país, encontrados na literatura (busca no google acadêmico). Caso não existam trabalhos de modelagem matemática, usar trabalhos descrevendo o processo de espalhamento da doença no país que considerem úteis para a confecção do seu modelo matemático.
* (4 pontos) Seção de ***Metodologia*** propondo um modelo matemático para a situação epidemiológica do país escolhido justificando a sua adequação para a situação epidemiológica observada até o momento no país. Esta seção deve descrever completamente o modelo e seus compartimentos, todas as suas equações acompadas de análise dimensional e descrição e interpretação de todos os parâmetros utilizados. Esta seção deverá ainda descrever o processo de captura dos dados epidemiológicos do país de interesse.
* (2 pontos) Seção de ***Bibliografia*** com todas as referências citadas.

## Critérios de Avaliação para a A2

Para a A2 a entrega consistirá de versão estendida (completa) do artigo que envolverá adicionar os seguintes componentes:

* (1 ponto) ***Resumo*** do artigo refletindo de forma sucinta os objetivos, metodologia, resultados e conclusão do trabalho.
* (5 pontos) Seção de ***Resultados*** contendo resultados analíticos e de simulação numérica do modelo proposto no artigo. O modelo deverá ser comparado aos dados existentes como forma de validação acompanhado de metodologia de escolha de valores para os parâmetros. Figuras e tabelas deverão ser incluídas nesta seção
* (4 pontos) Seção de ***Discussão e Conclusão*** contendo uma explicação mais detalhada dos resultados obtidos e suas implicações epidemiológicas e conclusões gerais do exercicio de modelagem e sua aplicabilidade para o entendimento do espalhamento da doença no país.

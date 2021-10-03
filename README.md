# tag_p2_unb
Projeto 2 de Teoria e Aplicação de Grafos, disciplina ofertada na Universidade de Brasília (UnB) no semestre 2021.1.

## Algoritmo adaptado

O algoritmo Gale-Shapley desenvolvido se baseou em duas versões: a de X, focada em emparelhamento de casais, com formação de pares; e a de Y, de onde foi analisado o algoritmo que dava prioridade a aulas, ao invés de estudantes.

Essas duas adaptações que foram usadas como base para este projeto partem do princípio de que há listas de preferências de ambos os conjuntos dados já feitas. O arquivo entradaProj2TAG.txt, que contém os dados sobre alunos e projetos, dá apenas as listas de preferências dos alunos.

Por isso, foi desenvolvido também um algoritmo para criação das listas de preferência dos projetos, levando em consideração: se o estudante tinha interesse pelo projeto; sua nota; e, por fim, sua preferência. O primeiro critério era eliminatório (se um aluno não tinha interesse em um projeto, não entrava na lista desse projeto), enquanto o segundo e o terceiro foram usados em ordenamento.

O pseudocódigo abaixo mostra a criação dessas listas:

<p align="center"><img src="media/algoritmo_list_preferencias_projetos.PNG" alt="pseudocode_algorithm" style="width:60%;"/></p>

Já para o algoritmo Gale-Shapley adaptado para o emparelhamento estável máximo de projetos e estudantes pode ser visto abaixo. Note que a preferência é dada para os projetos na escolha, e não para os estudantes.

<p align="center"><img src="media/pseudocode_algoritmo_adaptado.PNG" alt="pseudocode_algorithm" style="width:60%;"/></p>

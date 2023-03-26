> # Semana 06 - Aula PL

## turno:  PL 05

## grupo

| Número | Nome |
| ------- | ---- |
| A97569    | Afonso Amorim  |
| A88220    | Xavier Mota    |
| A95191    | João Alvim    |
| A96386    | João Cunha   |

## Resolução dos Exercícios (ficha 04):

### Exercício 1

O protótipo de uma interface para prescrição de medicamentos que será considerado neste exercício:

Recebemos o protótipo em pdf que está publicado neste mesmo repositório.

#### (a)
Na Facilidade de Aprendizagem da interface:

Principio a ser respeitado: Consistência, dado que só existe uma tarefa, a de atribuir uma receita, e preenche-se sempre da mesma forma.

Principio a ser quebrado: Não Aplicável.

/*---------------------------------------------------------------*/

Na Flexibilidade:

Principio a ser respeitado: Personalização, pois existe a possibilidade de alterar os campos na interface.

Principio a ser quebrado: Multithreading, pois a interface não está equipada para fazer mais do que uma tarefa ao mesmo tempo.

/*---------------------------------------------------------------*/

Na Robustez:

Principio a ser respeitado: Observabilidade, visto que ao olhar para a interface, é possível situarmo-nos no estado interno.

Principio a ser quebrado: Recuperabilidade, visto que não existe maneira do utilizador corrigir qualquer erro que possa ter cometido.


#### (b)

A interface anterior apresenta os princípios "básicos de vida", ou seja, aquilo que é estritamente necessário, porém pode melhorar noutros aspectos importantes.

#### (c)

O que se poderia alterar nesta interface, seria respeitar o principio da Recuperabilidade, de modo a que utilizador fosse capaz de corrigir/anular algo que fez por engano.

### Exercício 2*




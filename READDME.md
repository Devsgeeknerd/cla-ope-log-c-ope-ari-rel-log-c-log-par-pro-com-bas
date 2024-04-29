<!-- Título -->
# Operadores Lógicos — Teoria em C

***Conteúdo da Aula:***

O **C** também conta com operadores lógicos, que também são utilizados em conjunto com os operadores relacionais.

Estes operadores no **C** estão descritos na tabela abaixo:

| Operador | Descrição |
| :------: | :-------: |
| `&&` | Operador de conjunção |
| `\|\|`  | Operador de disjunção |
| `!` | Operador de negação |

## Operador Lógico `&&` (E)

O operador `&&`, assim como vimos no *Scratch*, também avalia duas ou mais condições relacionais e retornará **VERDADEIRO** (ou `true`) somente se todas as operações relacionais forem **verdadeiras**.

Veja o exemplo abaixo:

```c
int a = 3;
int b = 4;
// TRUE ou VERDADEIRO.
a < b;
// FALSE ou FALSO.
a < b && b < a
```

## Operador Lógico `||` (OU)

O operador `||`, assim como também vimos no *Scratch*, também avalia duas ou mais condições relacionais e retornará **VERDADEIRO** (ou `true`) somente se pelo menos uma das operações relacionais forem **verdadeiras**.

Veja o exemplo abaixo:

```c
int a = 3;
int b = 4;
// TRUE ou VERDADEIRO.
a < b;
// TRUE ou VERDADEIRO, já que a < b.
a < b || b > a
```

## Operador Lógico `!` (NÃO)

O operador `!`, assim como vimos no *Scratch*, inverte o resultado de uma expressão relacional.

Veja o exemplo:

```c
int a = 3;
int b = 4;
// TRUE ou VERDADEIRO.
a < b;
// FALSE ou FALSO.
!(a < b);
```

<!-- Informações -->
## &#8505; Informações

![Visitors](https://api.visitorbadge.io/api/visitors?path=Devsgeeknerd%2Fcla-ope-log-c-ope-ari-rel-log-c-log-par-pro-com-bas&label=Visitantes&labelColor=%23700070&labelStyle=none&countColor=%23000fff&style=plastic&color=%23ffffff "Total de Visitantes")
&nbsp;
![Followers](https://img.shields.io/github/followers/Devsgeeknerd?style=p&label=Seguidores&labelColor=800080&color=000fff "Total de Seguidores")
&nbsp;
![Watchers](https://img.shields.io/github/watchers/Devsgeeknerd/cla-ope-log-c-ope-ari-rel-log-c-log-par-pro-com-bas?style=p&label=Observadores&labelColor=800080&color=000fff "Total de Observadores")
&nbsp;
![Stars](https://img.shields.io/github/stars/Devsgeeknerd/cla-ope-log-c-ope-ari-rel-log-c-log-par-pro-com-bas?style=p&label=Estrelas&labelColor=800080&color=000fff "Total de Estrelas")
&nbsp;
![Forks](https://img.shields.io/github/forks/Devsgeeknerd/cla-ope-log-c-ope-ari-rel-log-c-log-par-pro-com-bas?style=p&label=Bifurcações&labelColor=800080&color=000fff "Total de Bifurcações")
&nbsp;
![Repo Size](https://img.shields.io/github/repo-size/Devsgeeknerd/cla-ope-log-c-ope-ari-rel-log-c-log-par-pro-com-bas?style=p&label=Tamanho&labelColor=800080&color=000fff "Tamanho do Repositório")
&nbsp;
![License](https://img.shields.io/github/license/Devsgeeknerd/cla-ope-log-c-ope-ari-rel-log-c-log-par-pro-com-bas?style=p&label=Licença&labelColor=800080&color=000fff "Licença do Repositório")

---
layout: post
title: Turing Machine and a Little about complexity
date:  2022-04-20  18:43:16
description: march & april, looking forward to summer
tags: formatting links
categories: complexity
---


Proposta por Alan Turing em um artigo publicado em 1936, as máquinas de Turing é um modelo abstrato de um computador que se restringe apenas aos aspectos lógicos do seu funcionamento (memória, estado e transições), e não
sua implementação própriamente dita. Éla é uma ferramenta muito poderosa para teóricos comprovarem teoremas por indução com provas formais. é possivel fazer a definição de uma máquina de turing sa seguinte forma:

Uma máquina de Turing é um tuplo dado por: $$\mathcal{T}$$ = ($$\mathcal{Q}$$,$$\mathcal{A}$$,$$\Gamma$$,$$\gamma$$,$$i$$, $$F$$), onde:

* $$\mathcal{Q}$$ é um conjunto finido de `estados`.
* $$\mathcal{A}$$ é o `alfabeto de entrada`.
* $$\mathcal{\Gamma}$$ é o `alfabeto da fita`.
* $$i \in \mathcal{Q} $$ é o `estado incial`.
* $$F\subseteq\mathcal{Q} $$ é o conjunto de `estados finais`.
* $$\delta : \mathcal{Q}$$ x $$\mathcal{\Gamma} \hookrightarrow \mathcal{Q}$$ x $$\mathcal{\Gamma}$$ x $$\{<,=,>\}$$ é a `função de transição` .

Tais que:

* $$\mathcal{A} \subseteq F$$ o alfabeto esta contido é igual aos estados finais.
* Os simbolos especiais contidos em $$\Gamma$$ de forma que $$\Gamma \backslash A$$ são `B` -> simbolo branco (denota o espaço vazio na célula), e $$\triangleright$$ denota o inicio da fita

* Para qualquer $$ q \in F$$, e qualquer $$\gamma \in \Gamma$$, $$\delta(q, \gamma)\uparrow$$ Denota que a transição não esta definida.
* Para qualquer $$q, q` \in \mathcal{Q}$$, se $$\delta(q,\triangleright)=(q`,\gamma,m)$$ então $$\gamma=\triangleright$$ e  $$ m \neq$$ <, $$ m \in \{<,=,>\}$$


Hoodie Thundercats retro, tote bag 8-bit Godard craft beer gastropub. Truffaut Tumblr taxidermy, raw denim Kickstarter sartorial dreamcatcher. Quinoa chambray slow-carb salvia readymade, bicycle rights 90's yr typewriter selfies letterpress cardigan vegan.

<hr>

Pug heirloom High Life vinyl swag, single-origin coffee four dollar toast taxidermy reprehenderit fap distillery master cleanse locavore. Est anim sapiente leggings Brooklyn ea. Thundercats locavore excepteur veniam eiusmod. Raw denim Truffaut Schlitz, migas sapiente Portland VHS twee Bushwick Marfa typewriter retro id keytar.

<blockquote>
    We do not grow absolutely, chronologically. We grow sometimes in one dimension, and not in another, unevenly. We grow partially. We are relative. We are mature in one realm, childish in another.
    —Anais Nin
</blockquote>

Fap aliqua qui, scenester pug Echo Park polaroid irony shabby chic ex cardigan church-key Odd Future accusamus. Blog stumptown sartorial squid, gastropub duis aesthetic Truffaut vero. Pinterest tilde twee, odio mumblecore jean shorts lumbersexual.

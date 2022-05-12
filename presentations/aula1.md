---
theme: unicorn
logoHeader: https://kindelia.org/static/media/kindelia_logo.d41e75d38f4e76bf6eb0b5e63721b8ca.svg
website: 'kindelia.org'
handle: 'kindelia'
class: text-center
title: Kindelia University
---

# Kindelia University

Como Será

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Pressione Espaço para passar
     <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/Kindelia/slides" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>


---

# O [Kindelia](http://kindelia.org/)
 
 É uma máquina virtual descentralizada equipada com tecnologia blockchain.

 Seu objetivo é resolver o [trilema do triângulo de Zooko](https://en.wikipedia.org/wiki/Zooko%27s_triangle): 

- Decentralizado → [Kindelia](https://github.com/Kindelia/Kindelia): Computador funcional descentralizado.
- Eficiente (Barato e Rápido)  → [HVM](https://github.com/kindelia/hvm): Máquina virtual funcional, paralela e ótima.
- Segurança  → [Kind](https://github.com/Kindelia/Kind): Linguagens de programação com provas formais.


---
layout: image-center
image: 'https://raw.githubusercontent.com/Kindelia/slides/main/img/zooko.png'
imageWidth: '900'

---

---


# O que o Kindelia precisa para prevalecer

- Kindelia: Sob controle nas mãos do Taelin
- HVM: Newcomers e Turma
- Kind: Newcomers e Turma
- Marketing: Grupo primo e comunidade.

Criação de ecossistema:
* Defi: KindCoin, Carteiras, NFTS, Corretoras etc. 
* Jogos diversos.

---

# Objetivo  das aulas

* Treinar a turma e interessados para a construção do Kind, HVM e do ecossistema.

As aulas serão inicialmente direcionadas para a turma, contudo o objetivo é que sirva para qualquer um interessado aprender por conta própria.

#### Objetivos específicos para a turma

* Contribuir com o repositório [prelude](https://github.com/Kindelia/prelude).
* Desenvolver documentações para o [Kind](https://github.com/Kindelia/Kind), [Kind2](https://github.com/Kindelia/Kind2) e [HVM](https://github.com/kindelia/hvm).
* Desenvolver a [Wiki](https://app.gitbook.com/o/f5pmVKXE0zdcMOu6WXHf/home).
* Dar feedbacks sobre as aulas para que possamos fazer o melhor conteúdo possível.
* Resolver todas as listas de exercícios.


---

# O desafio

Aprender linguagens funcionais do zero, ao mesmo tempo em que são criadas.

O esperado é que em 6 meses, todos possam estar programando na HVM com propriedade, e desenvolvendo os mais variados sistemas.

---

# Abordagem das aulas

Cada assunto será dividido em duas partes:


#### Aula teórica pré-gravada com o conteúdo

Onde vocês poderão acelerar, pausar, voltar e assistir no momento que preferirem. 

Ao final da aula será passado exercícios.

#### Aula síncrona

Onde os alunos darão feedbacks sobre a aula teórica, tirarão dúvidas, discutirão os exercícios, compararão os resultados, compartilharão materiais e resolverão problemas em tempo real.


---

# A equipe

A equipe é formada por: 

* Gabriel
* Humberto
* Jogario
* Corgan

Estaremos nos organizando para entrar em contato com a turma, acompanharmos o desenvolvimento e tirarmos as dúvidas de todos.

--- 

# Objetivo dos Monitores 

* Facilitar o aprendizado da turma (reuniões, links)
* Validar o aprendizado da turma (testes, projetos)
* Criação de conteúdo que facilite o aprendizado de qualquer um interessado (Wiki, youtube)
* Estruturação das informações sobre o Kindelia (Github, redes sociais, site)

---

# Habilidades e conhecimentos pressupostos

* Lógica de programação e Matemática básica
* Uso de terminal e editor de texto
* Instalação de pacotes
* Git
* O que é e como funciona o bitcoin e o ethereum

---

# Cronograma de Aulas (1/3)

## Módulo: Programação Funcional
* Semana 1: Bool, Pair, Maybe, Nat.
* Semana 2: Int, Bits.
* Semana 3: List, Char, string.
* Semana 4: ListMap, BitsMap, PriorityQueue, function.
* Semana 5: Recursion.
* Semana 6: Parsing, TypeClass.
* Semana 7: Monad.
* Semana 8 Io. -> projeto final: app.

---

# Cronograma de Aulas (2/3)

## Módulo: Verificação Formal
* Semana 9: Análise de Casos (Bool, Maybe, Pair, Equal)
* Semana 10: Indução Nat
* Semana 11: Indução Int
* Semana 12: Indução Bits
* Semana 13: Tipos dependents
* Semana 14: Tipos indexados
* Semana 15: Sigma
* Semana 16: Prova -> projeto final (1 teorema difícil)

---

# Cronograma de Aulas (3/3)

## Módulo: Lambda Encoding (HVM)
* Semana 17: Lambda Hacks
* Semana 18: Scott Encoding
* Semana 19: Church Encoding
* Semana 20: Self Encoding

[Lista com mais detalhes](https://gist.githubusercontent.com/VictorTaelin/9470ee286280e5638107fbcfaf7cdc26/raw/4138a5e504e06a557ce212ce29a5491f56640e3a/gistfile1.txt)

---

# Materiais

as aulas ficarão gravadas no [youtube](https://www.youtube.com/c/Kindelia).

os slides estão disponíveis no repositório [slides](https://github.com/Kindelia/slides).

Os exercícios no repositório [class](https://github.com/Kindelia/class).

Onde é possível acessar o slide online para revisão, e acessar o código fonte dos slides.

Para quem quiser se aprofundar, no repositório do [prelude](https://github.com/Kindelia/prelude) há uma lista com link para referências, incluindo o livro o okasaki. 

---
layout: center
---

# Primeiro Exercício

Dar um olhada na [Wiki](https://app.gitbook.com/o/f5pmVKXE0zdcMOu6WXHf/home),
no [class](https://github.com/Kindelia/class) e
no [youtube](https://www.youtube.com/c/Kindelia).

Se inscrever no canal, curtir o vídeo e comentar:

o que achou da abordagem e dar sugestões.


<!--
This file defines the contents of each slide.
The reveal.js configuration can be found in index.html
-->

<!-- .slide: class="slide-title" data-background-image="assets/title-slide.svg" data-background-color="#000000" data-background-size="contain" -->

<!-- Place the content at the bottom of the slide -->
<div class="r-stretch">
</div>

<!-- Main title page -->
<div class="lefted">

<h1 id="talk-title">
<strong>Academia e software livre:</strong>
<br>
Desafios e oportunidades
<br>
no Brasil e no exterior
</h1>

<p id="talk-authors">
    Leonardo Uieda
    <span style="margin: 0 30px">•</span>
    <i class="fab fa-twitter fa-fw"></i>
    <a href="https://twitter.com/leouieda">@leouieda</a>
</p>

<!-- Place location and date side-by-side with affiliation logos -->
<div class="container talk-info">
<div class="col-large">

National Observatory Greenstone Belt (SEG-EAGE Student Chapter)
<span style="margin: 0 20px">•</span>
22 Julho 2021

<!-- Permission to reuse and CC-BY license logo -->
<p><a href="https://creativecommons.org/licenses/by/4.0/">
<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by" style="margin: 0 10px 0 2px"></i>
CC-BY 4.0 License
</a></p>

<i class="fa fa-camera" style="margin: 0 10px 0 0"></i>
Feel free to screenshot/share/reuse/remix this presentation

</div>
<div class="col-small">

<!-- Add logos here. Need these wrappers to align them to the bottom right -->
<div class="talk-logos-container">
<div class="talk-logos">
    <img src="assets/university-of-liverpool-white.png">
    <img src="assets/compgeolab-banner-light.svg">
</div>
</div>

</div>
</div>

</div>

---

<!-- .slide: class="slide-transition" data-background-color="#0044aa" -->

<div class="centered">
<div class="huge">

1. Quem eu sou
1. O que eu faço
1. Como eu cheguei até aqui
1. Software livre na ciência
1. Dicas

</div>
</div>

---

<!-- .slide: data-background-video="assets/brasil-sao-paulo-rio.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch bottom-right">

Sou do interior de São Paulo, região com o melhor sotaque do Brasil

</div>

---

<!-- .slide: data-background-image="assets/sao-paulo.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-right">

Trivia: [Botucatu](https://pt.wikipedia.org/wiki/Botucatu) é a sede da
Associação Nacional de Criadores de Saci

</div>

---

<!-- .slide: data-background-image="assets/iag.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-left">

Mesma turma que o Vanderlei.

</div>

---

<!-- .slide: data-background-image="assets/first-contact-with-c.jpg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-left">

Descobri a programação e continuei indo atrás (matérias, IC, hobby).

</div>

---

<!-- .slide: data-background-image="assets/york.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-right">

Amigos até hoje, culturas diferentes, geodésia (ainda tenho contato com meu
professor).

</div>

---

<!-- .slide: data-background-image="assets/on.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-left">

Valéria me deixou livre pra programar.
<br>
Interesse em ciência aberta, reprodutibilidade e divulgação
<br>
Comecei a investir nas ferramentas open-source.

</div>

---

<!-- .slide: data-background-image="assets/uerj.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-left">

Experiência excelente de dar aula e interagir com os outros professores.
<br>
Aprendi muito: pedagogia, assunto (sísmica e geologia), relações humanas
<br>
Hora para pensar a longo prazo e colocar minhas ideias em contexto
<br>
(fonte: [Renato Mariz](https://commons.wikimedia.org/wiki/File:UERJ_2.jpg) | CC-BY-SA)

</div>

---

<!-- .slide: data-background-image="assets/uh-manoa.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-right">

Abriu meus olhos para como a ciência funciona no resto do mundo.
<br>
Ressaltou as vantagens do Brasil.
<br>
Acesso à rede de pesquisadores renomados (Paul é muito popular).
<br>
Pensar sobre financiamento, impacto da pesquisa na sociedade, aplicações,
colaborações, etc.

</div>

---

<!-- .slide: data-background-image="assets/liverpool.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-left">

Saí da UERJ e Professor (lecturer) em Liverpool.

</div>

---

<!-- .slide: data-background-image="assets/baking-evolution.svg" data-background-size="contain" data-background-repeat="no-repeat" data-background-color="#000000" -->

<div class="r-stretch bottom-left">

Minhas habilidades de padeiro evoluíram mais que qualquer outra coisa

</div>

---

<!-- .slide: class="slide-transition" data-background-color="#0044aa" -->

<div class="centered">
<div>

# O que eu faço

</div>
</div>

---

<div class="container centered">
<div class="col-left">

# Modelagem direta

Campos gravitacionais

Elementos esféricos (tesseroides)

Integração numérica

Lançamento do satélite GOCE em 2009

Graduação até o Doutorado

</div>
<div class="col-right tiny">

<img src="assets/tesseroid.jpg">

Tesseroide após discretização adaptativa
([Uieda et al., 2016](https://doi.org/10.1190/geo2015-0204.1))

</div>
</div>

---

<div class="container centered">
<div class="col-left tiny">

<video style="width: 100%" muted data-autoplay loop>
<source data-src="assets/planting-inversion.mp4" type="video/mp4"/>
</video>

Algoritmo de plantação para inversão de dados gravimétricos
<br>
([Uieda & Barbosa, 2012](https://doi.org/10.1190/geo2011-0388.1))

</div>
<div class="col-right">

# Inversão 3D

Desenvolvimento de métodos

Métodos potenciais (grav + mag)

Escala local a global

Intrusões, recursos minerais, Moho

</div>
</div>

---

# Software livre

<div class="container">
<div class="col-software">

<img src="assets/tesseroids-logo.svg">

## Tesseroids

(2008)

</div>
<div class="col-software">

<img src="assets/fatiando-logo.svg">

## Fatiando a Terra

(2010)

</div>
<div class="col-software">

<img src="assets/gmt.png">

## GMT

(2017)

</div>
</div>

---

<!-- .slide: data-background-video="assets/seismic-waves-demo.mp4" data-background-size="contain" data-background-color="#000000" -->

<div class="r-stretch bottom-right bottom-dark">

Várias matérias: programação, grav, sensoriamento remoto, campo, etc.
<br>
Usa programação em tudo.

</div>

---

<!-- .slide: class="slide-transition" data-background-color="#0044aa" -->

<div class="centered">
<div>

# Como eu cheguei até aqui

</div>
</div>

---

# Privilégio

Pais acadêmicos

Classe média

Interior de São Paulo

Suporte familiar

Escola privada

Inglês

Homem

Branco + asiático

Brasil tem bolsas e ensino público gratuito

---

# Sorte

Prestei geofísica

Entrar na USP em 2004 foi crucial. Turma foda. Professores foda.

Período de crescimento econômico do país

Valéria me aceitou mesmo com más recomendações

Mentores excepcionais: Manoel, Naomi, Carla, Valéria, Paul

Vaga na UERJ na hora certa

Vaga do GMT na hora certa

Vaga em Liverpool na hora certa

Gostei de programação na hora certa

---

# Oportunidades

Privilégio e sorte foram fatores importantes para essas oportunidades serem
acessíveis.

Sempre busquei, pesquisei, perguntei, apliquei

USP e ON forneceram muitas (financiamento e incentivo)

Fui em todos os congressos que consegui

Estabeleci contatos

Aproveitei e me expus: não neguei apresentações, divulgo meu trabalho, converso
com picudos.

---

# Rede de apoio

Turma do IAG

Turma do ON

---

# Disclaimer

Essa é a minha experiência.

Minha experiência não é aplicável a todos

Não são prerequisitos

Outros caminhos são possíveis

---

<!-- .slide: class="slide-transition" data-background-color="#0044aa" -->

<div class="centered">
<div>

# Software livre na ciência

</div>
</div>

---

# Software na ciência

Por que é importante, etc.

---

# Software livre

Interesse por software livre na faculdade (PCs era linux)

Reprodutibilidade, "stand on the shoulders of giants"

---

# Oportunidades

O que se tem a ganhar investindo em software

Reputação, publicações, agilidade na pesquisa, ensino de qualidade, currículo
competitivo fora da academia, rede de contatos.

---

# Desafios

Cuidados para se tomar.

Carreira acadêmica ainda precisa de papers + projetos. Pelo menos o mínimo para
ser competitivo. Financiamento de software. Burnout. Trabalho voluntário
depende de privilégio.

---

<!-- .slide: class="slide-transition" data-background-color="#0044aa" -->

<div class="centered">
<div>

# Dicas

</div>
</div>

---

# Exterior (EUA e Europa)

Tudo custa dinheiro.

Alunos independentes são valorizados

Visto, mudança, etc são caros e difícil de financiar

Tem que passar um tempo fora para conseguir um emprego

Rede é tudo (recomendações e nomeações)

Projetos > papers (dinheiro é muito importante)

Bolsas nos EUA são mais fáceis pois podem ser pagas por projeto de professor.

Precisa de certificado de inglês (TOEFL e IELTS)

Ir com dinheiro próprio (do Brasil) é muito mais fácil mas tem restrições

The Professor Is In é obrigatório

---

# Programação

Aprendizagem contínua (mesmo depois de 17 anos)

Estude tudo que tem no Software Carpentry

Progresso iterativo

Leia o código dos outros

Simples é melhor que rápido

Se envolva em projetos

Entre no Software Underground

---

# Geral

Reconheça seus privilégios.

Busque oportunidades e tome proveito.

Pense e se comporte como um profissional, não como aluno.

Ser independente, ativo, entusiasmado, não ser passivo, mostrar interesse, tome
as rédias, a vida é sua.

Vocês não são mais estudantes. São profissionais. Sua carreira depende de vocês
também, não só fatores externos.

---

<!-- .slide: class="slide-contact" data-background-image="assets/contact-slide.svg" data-background-position="top" data-background-color="#000000" -->

<div class="centered">
<div>

# Contato

<ul class="fa-ul" style="">
<li><i class="fa-li fa fa-envelope"></i>

**email:** [Leonardo.Uieda@liverpool.ac.uk](mailto:Leonardo.Uieda@liverpool.ac.uk)

</li>
<li><i class="fa-li fa fa-home"></i>

**website:** [leouieda.com](https://www.leouieda.com)

</li>
<li><i class="fa-li fa fa-flask"></i>

**groupo:** [compgeolab.org](https://www.compgeolab.org)

</li>
<li><i class="fa-li fa fa-desktop"></i>

**slides:** [leouieda.com/2021-07-22-on](https://www.leouieda.com/2021-07-22-on)

</li>
</ul>
</div>
</div>

---

<!-- .slide: class="slide-license" -->

<div class="centered">
<div>

<p class="license-icons">
<i class="fab fa-github"></i>
</p>

Source code:
[github.com/leouieda/2021-07-22-on](https://github.com/leouieda/2021-07-22-on)

<p class="license-icons" style="margin-top: 5%;">
<i class="fab fa-creative-commons"></i><i class="fab fa-creative-commons-by"></i>
</p>

Unless otherwise noted,
the contents of this presentation are
licensed under the
<br>
[Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

</div>
</div>

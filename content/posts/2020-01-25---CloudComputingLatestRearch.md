---
title: Cloud Computing e últimas pesquisas
date: "2020-01-23T14:19:36+00:00"
template: "post"
draft: true
slug: "cloud-computing-latest-research"
category: "Cloud Computing"
tags:
  - "Cloud Computing"
description: "Cloud Computing e últimas pesquisas"
socialImage: "/media/image-2.jpg"
---

Quando eu comecei a entender o que era a programação para a Web, minha visão
era limitada a apenas enxergar uma framework PHP com um servidor Web. Eu via 
um bando de arquivos agrupados que parecia intencionar a exposição ao mundo 
de uma página Web e alguma API, como REST. Há algum tempo meu pensamento
de desenvolvimento era exatamente na forma de silos: um silo de backend
que habitava um servidor e um silo frontend que lidava com algum tipo de geração
de HTML, CSS, Javascript e mobile app.

Com o passar do tempo e um contato com tecnologias da AWS e Google Cloud, pude
sentir a pressão de uma nova atmosfera, rica em interações entre serviços de
backend e operações de implantação muito diversificada. Também existia um desafio
que permeava em poder integrar de alguma maneira a soluções que chamo de "clássicas",
onde tenho meu pequeno silo de backend monolítico que consumiria serviços de terceiros.

Surgia assim uma ideia inicial de que a **integração** era, em si, um **desafio
mal especificado** e que eu teria que recorrer a muitas tecnologias para automatizar
tarefas para tornar a configuração de ambiente replicável com reduzidas etapas, valendo-se
dos princípios do [**The Twelve Factors**](https://12factor.net/).

# A Integração....

A evolução de um projeto de software altamente centralizado e coeso para um 
descentralizado com muitos recursos externos consumidos traz alguns questionamentos 
sobre aspectos a serem considerados. Uma enorme gama, que varia do gerenciamento
das contas e artefatos vindos de serviços de terceiros a monitoramento da saúde
das aplicações - aspectos que necessitam serem esclarecidos e documentados
de forma a atender as necessidades de negócio e manutenção das aplicações.

Agora, no entanto, explicar a um stakeholder sobre todos os aspectos que
permeiam o gerenciamento do ciclo de vida das aplicações e suas integrações
é de fato um desafio que, para mim, podemos comparar como um problema de tradução
linguística.

Numa organização, existe, em cada time, um linguajar técnico próprio do domínio
da área exercida pelos colaboradores. Esse linguajar é também uma linguagem e que
tem um escopo em que os termos fazem sentido, ou seja, possuem semântica aplicável. 
Existirá um escopo mais técnico em áreas de execução, como no desenvolvimento de 
software, e um escopo mais voltado ao negócio, como no planejamento e direção da 
organização.

O progresso de todo trabalho numa organização depende em parte da qualidade da tradução 
dessas linguagens e suas dinamizações para que possuam atuar efetivamente em favor
do atendimentos das transformações dos requisitos de negócio. Por exemplo, se a equipe
de desenvolvimento recebe as descrições das tarefas com termos dúbios ou mal compreendidos
então é de se esperar uma certa habilidade interpretativa da liderança do desenvolvimento
em traduzir mais satisfatoriamente a fim de evitar frustrações. A área de análise de requisitos
é totalmente orientada em poder lidar com isso.

Mas, em essência, da análise de requisitos temos diagramações (textos, gráficos, e etc)
que são documentos estáticos que, por sua vez, é uma linguagem técnica com uma semântica
mais flexível: ao mesmo tempo que para um diretor de operações é possível visualizar
a interação entre as aplicações e os artefatos, também é possível para um programador
experiente interpretá-la e implementar os códigos que a promovem. Entretanto,
observe a necessidade em ter que se traduzir as descrições das demandas e identificar
requisitos não-funcionais, como ocorre na utilização de serviços externos.

A tradução envolve a criação de uma ponte que ligue o escopo de negócio ao escopo técnico.
E quando lidamos com a Web atual, a demanda por integrações de serviços de dentro da própria
organização com externos nos faz ser pressionamos a estabelecer rapidamente essa ponte sem
qualquer questionamento das metodologias envolvidas. Acrescenta-se ainda que as integrações
irão envolver mais requisitos não-funcionais ocultos, pois precisaremos de mais profissionais
para tarefas especializadas, como em DevOps - olha que em DevOps já existe uma linguagem
própria, por vezes complexa para equipes generalistas.

....algum texto sobre EIP....

# Cloud Computing

Em se tratanto do processo de desenvolvimento e modelagem de processos e software, é de real
importância compreender que isso implica na definição, com alguma formalidade, de SDL
(Service Description Language) e sua articulação com aspectos da adoção de serviços e publicação
na Cloud.

## Real Benefício da Cloud Computing

Qualquer coisa é um serviço potencial, desde hardware a software. A adoção de um modelo 
de pagamento pay-to-use torna a Cloud atraente, com a vantagem competitiva por permitir
acelerar a entrega e terceirizar responsabilidades a fim de tornar mais viável iniciativas
na implantação de soluções integradoras, provando-se, o mais cedo possível, as hipóteses
comerciais.

Mas precisa ficar claro: a Cloud é alimentada por hardware e software com um background
pragmático com o objetivo de se vender e captar clientes. O provedor precisa
constantemente provar suas próprias hipóteses comerciais e causar impacto na oferta
de soluções. Não há um apelo metodológico apoiado em conceitos científicos: a visão
de "fazer acontecer" é quase sempre a estrela-guia no que é chamado de **go-to-the-market**.

Assim, tem-se uma base onde existem garantias fragilizadas devido a volatilidade
da oferta de produtos/serviços e sua rentabilidade variável ao provedor.

Quem tem espaço na oferta de hardware/software na Cloud? Quem conquistou uma base de clientes,
grandes investidores e regionalidade.

## Fisiologismo dos Provedores Distanciamento acadêmico

A intensa necessidade de concretizar e assegurar alguma lucratividade é, de certo modo,
a geradora de desinteresse no incentivo a práticas ou formalismos conceituais que permitam
a aproximação de algum ideal cultivado no meio acadêmico.

Apesar do distanciamento e dificuldades aparentes devido a alguma cortina que impede a
acessibilidade tecnológica ao meio científico a respeito da Cloud Computing como
modelo de computação, é possível promover algum link com:

- SOA (Arquitetura Orientada a Serviço)
- Computação em Grid
- Computação Distribuída e Concorrente
- EIP (Pladrões de Integração Empresarial)
- BPMN (Modelagem de Processos de Negócio)

Seria viável construir uma solução de propósito geral objetivando uma descrição formal...

As tentativas de elaboração de uma linguagem de especificação formal ubíqua tornam-se
dispendiosas tendo em vista os silos de especificação e descrição promovidos
intencionalmente entre os provedores. Mesmo assim, estabeleecndo alguma ontologia
e verificação das similaridades das descrições e propósito dos serviços, é possível
levantar algum questionamento que gere indicações para criação de iniciativas metodológicas
no estabelecimento de alguma linguagem técnica.

> Os textos acima são ideias para inserir ou serem considerados. O Nawaz começa discorrendo
sobre SDLs e eu gostaria de explicar a razão de começar por SDL e a relação existente entre
SDL e os cenários da area de desenvolvimento de software na Web.
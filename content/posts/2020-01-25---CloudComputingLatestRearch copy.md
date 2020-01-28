---
title: Cloud Computing e últimas pesquisas
date: "2020-01-25T14:19:36+00:00"
template: "post"
draft: false
slug: "cloud-computing-latest-research"
category: "Cloud Computing"
tags:
  - "Cloud Computing"
description: "Cloud Computing e últimas pesquisas"
socialImage: "/media/image-2.jpg"
---

## Introdução

O crescimento do ambiente Cloud é permitido pela automação de implantação dos 
serviços na Internet. Conhecer as particularidades necessárias para realizar
essa automação envolve compreender, principalmente, algum tipo de linguagem
que descreva as características do serviço cloud.

A chamada SDL (Service Description Language) é a linguagem que descreve
modelos e padrões utilizados pelos provedores de Cloud. Ela tem um propósito
bem estabelecido: atender as demandas técnicas de seus clientes seguindo
seus próprios objetivos comerciais.

Em geral, cada provedor admite quatro objetivos comerciais, que também
podem ser encaradas como **operações de serviço cloud**:

- **Implantação e Provisionamento** (Deployment and Provisioning)
- **Modelagem e Composição** (Modeling and Composition)
- **Descoberta e Seleção** (Discovery and Selection)
- **Service Level Agreement** (muitas vezes referida como SLA)

Qualquer SDL tem como seu principal propósito o detalhamento de cada
operação. Ou seja, é de suma importância entender algum tipo de SDL
para melhor entender cada operação, bem como seu relacionamento
com o ciclo de vida das aplicações em Cloud.

Uma SDL pode ser construída através de inúmeras formas e cada
provedor estabelece certas normas de como proceder com o seu uso.
Embora existam vários formatos de SDL, todas elas compartilham alguns
princípios de usabilidade ou interface de interação. A imensa maioria 
das SDLs exportam interfaces como APIs HTTP, seja REST, SOAP e etc. Elas 
seguem formatos de entrada/saída estabelecidos por algum tipo de acordo
entre o consumidor das APIs e o provedor, utilizando-se como formatos de dados
o JSON ou XML.

Acrescento que, além das APIs HTTP comumente expostas na Internet pelos
provedores de Cloud, existem alguns meios de "envelopamento" ou *wrappers*
que os próprios provedores fornecem. A AWS, por exemplo, fornece SDKs,
isto é, kits de desenvolvimento numa variedade de linguagens de programação.
Estes SDKs tentam abstrair algumas especificidades da comunicação HTTP,
além de servir como um facilitador à produtividade do programador,
que precisa de alguma orientação como a tipagem dos dados de 
requisição/resposta.

Agora, a gente compreendendo que cada provedor de Cloud fornece de alguma
maneira alguns SDLs para seus serviços, seria natural pensar numa
unificação dessas linguagens de descrição, certo? Bem, a gente
já viveu a guerra dos browsers no seu lado mais tenebroso nos últimos anos
e o que se tem visto notoriamente é um conflito dos provedores de Cloud seguindo 
uma linha semelhante.

A respeito da guerra dos browsers, um enorme litígio criado pelas batalhas 
das organizações por trás da Web originou debates acalorados pela W3C na 
tentativa de dar uniformidade aos padrões e comportamentos para 
tornar garantida uma interoperabilidade mínima entre browsers em meio
a diversidade de padrões proprietários das desenvolvedoras.

A resposta natural da W3C em meio ao caos dos padrões proprietários foi
o estabelecimento de padrões para HTML e CSS. Aceitar as normas da W3C
foi considerada a atitude correta a fim de se promover um menor esforço das
equipes de desenvolvimento para que pudessem possuir uma mesma base (ou quase)
de código sem necessitar de algum processo custoso de suporte a alguma
tecnologia proprietária.

Voltando a questão da unificação de padrões de SDLs entre provedores de Cloud,
existe alguma organização, quase dogmática, que de certo modo os obrigue 
a seguir padrões nas definições, bem como os comportamentos esperados
das operações dos serviços? A resposta para essa pergunta é a compilação das
pesquisas internacionais de equipes de estudiosos em Cloud Computing. Existem
muitas iniciativas para se criar um comitê padronizador, até mesmo
financiado pela União Europeia (OASIS), mas nenhuma delas tem o alcance 
equiparável a W3C.

Muitas iniciativas de padronização são rejeitadas pelas provedoras. 
Simplesmente fazem de conta que elas mesmas precisam definir a Cloud
Computing em seus termos, ainda muito na onda de se diferenciar
da concorrência, seja por meio de uma terminologia particular ou por
definições de serviços estrategicamente posicionados para fazer
frente em comparações técnicas para adoção em massa. As rejeições, omissões
e negligência a alguma iniciativa de padronização contribui ao chamado
**problema do vendor lock-in**.

Então, o que nos resta abordar para se tentar compreender essa barreira
criada pela guerra das provedoras de Cloud é a análise de estudos mais
recentes que possam iluminar a jornada da adoção dos serviços de Cloud
Computing. Em meados de 2019, o artigo [Service description languages in cloud computing: state-of-the-art
and research issues](https://doi.org/10.1007/s11761-019-00263-z) 
publicado pela Springer na área de Service Oriented Computing and Applications
trouxe um compilado de estudos, trazendo critérios comparativos, bem como
avanços feitos por cada pesquisa. Nawaz, um dos autores, complementa as
análises das investigações anteriores feitas por outras equipes, 
lançando a identificação das falhas das literaturas a respeito da 
caracterização das SDLs em diferentes operações de serviços.
# Section 2 - Conceitos Básicos

## Sumário

* [2.1 DDD: Negócio ao Código](#21-ddd-domain-driven-design-negócio-ao-código)
* [2.2 Linguagem Onipresente](#22-linguagem-onipresente)
* [2.3 Princípio SRP](#23-princípio-srp-simple-responsibility-principle)
* [2.4 Princípio DRY](#24-princípio-dry-dont-repeat-yourself)
* [2.5 Indireção /  Delegação](#25-indireção--delegação)
* [2.6 Lei de Demeter](#26-lei-de-demeter)
* [2.7 Acomplamento de Coesão](#27-acomplamento-de-coesão)
* [2.8 Imutabilidade](#28-imutabilidade)
* [2.9 OO + Funções Puras](#29-oo--funções-puras)
* [2.10 Testes Tempretivos](#210-testes-tempretivos)
* [2.11 Refatoração Tempestiva](#211-refatoração-tempestiva)
* [2.12 Regras da Simplividade](#212-regras-da-simplividade)

## 2.1 DDD (Domain Driven Design): Negócio ao Código

Domain-driven design ( DDD ) é uma importante abordagem de design de software, com foco na modelagem de software para corresponder a um domínio de acordo com a entrada dos especialistas desse domínio.

Sob o design dirigido por domínio, a estrutura e a linguagem do código do software (nomes de classe, métodos de classe , variáveis ​​de classe) devem corresponder ao domínio de negócios.

O design orientado por domínio é baseado nos seguintes objetivos:

    -> Colocar o foco principal do projeto no domínio principal e na lógica do domínio;
    -> Basear projetos complexos em um modelo do domínio;
    -> Iniciar uma colaboração criativa entre especialistas técnicos e de domínio para refinar iterativamente um modelo conceitual que aborda problemas de domínio específicos.

* *Obs.1* O requisito está muito no código, mas muito código não vem do requisito.
* *Obs.2* Foco no Negócio (Pacote com entidade e relacionadas ao negócio)
* *Obs.3* Isolamento do Domínio (Código de domínimo é idiossincrático e particular)
* *Obs.4* Infraestrutura à Parte (Tecnologias vem e vão, mas o negócio permanece)
* *Obs.5* Separar responsabilidades (User Interfasce, Application, Domain, Infrastruct)

## 2.2 Linguagem Onipresente

* *Obs.1* Linguagem Onipresente (Ubíqua)
* *Obs.2* Contexto Delimitado
* *Obs.3* Tijolos de Construção (Entidades, Objetos de Valor, Agregadores, Eventos de Domínio, Serviços, Repositórios)

## 2.3 Princípio SRP (Simple Responsibility Principle)

A ideia por trás do SRP é que cada classe, módulo ou função em um programa deve ter uma responsabilidade/propósito em um programa. Como uma definição comumente usada, "cada classe deve ter apenas um motivo para mudar".

## 2.4 Princípio DRY (Don't Repeat Yourself)

Don't repeat yourself " (DRY) é um princípio de desenvolvimento de software que visa reduzir a repetição de padrões de software, substituindo-a por abstrações ou usando a normalização de dados para evitar redundância.

* *Obs.1* Repetições no código nas partes de requisitos de negócios são ruins para o negócio
* *Obs.2* Problema de comunicação

## 2.5 Indireção /  Delegação

## 2.6 Lei de Demeter

## 2.7 Acomplamento de Coesão

## 2.8 Imutabilidade

## 2.9 OO + Funções Puras

## 2.10 Testes Tempretivos

## 2.11 Refatoração Tempestiva

## 2.12 Regras da Simplividade

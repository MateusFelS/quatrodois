# QuatroDois — QA Testing Case

Este repositório apresenta um estudo prático de QA realizado no ambiente público do site da **QuatroDois**, com o objetivo de exercitar atividades de testes manuais, identificação de comportamentos inesperados e documentação de defeitos.

O teste foi realizado de forma independente, utilizando exclusivamente as funcionalidades e páginas disponíveis publicamente no momento da análise.

## Objetivo

O objetivo deste case é praticar e demonstrar conhecimentos relacionados a:

* Testes exploratórios;
* Validação de navegação;
* Validação de links e CTAs;
* Identificação e documentação de defeitos;
* Análise de impacto;
* Criação de evidências;
* Elaboração de reports de bugs.

## Escopo

A análise foi concentrada na navegação e nos principais links disponíveis na landing page, incluindo:

* Cases;
* Contato;
* "Fale com um especialista";
* Política de Privacidade;
* Termos de Serviço;
* Blog e acesso aos artigos.

## Ambiente

| Item                | Informação                             |
| ------------------- | -------------------------------------- |
| Ambiente            | Ambiente público disponível ao usuário |
| Navegador           | Brave                                  |
| Sistema Operacional | Windows 11                             |
| Tipo de teste       | Teste manual / exploratório            |

## Resultados

Durante a análise, foram identificados comportamentos nos quais determinados links e páginas direcionam para uma página informando que o conteúdo não existe.

Os problemas encontrados foram documentados individualmente, com passos para reprodução, resultado esperado, resultado obtido, impacto e evidências.

### Bugs documentados

* [BUG-001 — Links e CTAs da landing page direcionam para páginas inexistentes](reporte-de-bugs/BUG-001-links-e-ctas-landing-page-paginas-inexistentes.md)
* [BUG-002 — Artigos do Blog direcionam para páginas inexistentes](reporte-de-bugs/BUG-002-artigos-do-blog-direcionam-para-paginas-inexistentes.md)

## Observação

Este trabalho foi realizado exclusivamente como exercício prático de QA, utilizando o ambiente público disponível ao usuário.

Não foram realizados testes invasivos, tentativas de acesso a áreas restritas ou qualquer alteração de dados.

O objetivo é demonstrar o processo de identificação, análise e documentação de possíveis problemas de usabilidade e navegação, além de compartilhar o feedback de maneira construtiva.

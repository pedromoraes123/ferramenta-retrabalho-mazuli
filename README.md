# Ferramenta de análise de retrabalho – Mazuli Smart Projects

Trabalho da disciplina **Programação para Engenharia de Produção** (Engenharia de Produção – Univille).

**Autores:** Pedro Henrique de Moraes Cunha e Derick Roberto Kühn

## Sobre o projeto

Ferramenta web para apoiar a análise de retrabalho no processo de desenvolvimento de projetos de moldes de injeção plástica da Mazuli Smart Projects. Dá continuidade ao trabalho "Pesquisa de melhoria de processo no ambiente empresarial".

## O que a ferramenta faz

- **Registro de dados:** projetos concluídos (tempo de cada etapa) e retrabalhos (etapa onde foi identificado, causa, etapa para correção e tempo de correção).
- **Resumo:** retrabalhos por causa, por etapa de identificação e por etapa de retorno.
- **Simulação:** fluxo do processo com a decisão "Projeto aprovado?", em que a reprovação leva a uma correção e ao retorno a uma etapa anterior (método de Monte Carlo, com distribuição triangular para os tempos).

## Tecnologia

HTML, CSS e JavaScript em um único arquivo (`index.html`), executado no navegador, sem instalação. Os dados ficam salvos no navegador de quem usa e podem ser exportados e importados em texto. A programação foi desenvolvida com apoio de IA (Claude, da Anthropic).

## Como usar

1. Abra o `index.html` em qualquer navegador (ou acesse a página publicada pelo GitHub Pages).
2. Na aba **Registro de dados**, cadastre os projetos e os retrabalhos.
3. Na aba **Simulação**, clique em **Estimar a partir dos registros**, ajuste os parâmetros se necessário e clique em **Simular**.

## Aviso sobre os dados

Os dados reais da empresa ainda não foram coletados. O botão de demonstração carrega dados **fictícios**, apenas para testar o funcionamento, e os resultados obtidos com eles não representam a Mazuli Smart Projects.

## Situação

Versão inicial, em desenvolvimento. Pendentes: coleta de dados reais e validação do modelo com projetos reais.

# Geoengenharia IA: site (geoengenharia-ia.com.br)

Site de geoengenharia para data centers. Criado por Guilherme Morais Nascimento (guilhermenascimento867@gmail.com).

## Arquivos
- `index.html`: site completo (HTML, CSS e JavaScript em um só arquivo, sem build).
- `normas-data-center.pdf`: guia de referência das normas técnicas. Mantenha-o na mesma pasta do `index.html`.

## Abas
Serviços, pré-avaliação do terreno, aprenda (Tiers, PUE, tipos de resfriamento), resfriamento (simulador), normas, método, referências e contato.

## Publicar no GitHub Pages
1. Crie um repositório público e envie `index.html`, `normas-data-center.pdf` e um arquivo `CNAME` com o conteúdo `geoengenharia-ia.com.br`.
2. Em Settings > Pages, escolha a branch `main`, pasta `/ (root)`.
3. Aponte o DNS no Registro.br com os registros A do GitHub Pages (185.199.108.153 a 185.199.111.153) e um CNAME de `www`.

## Ajustes
- E-mail de contato: procure `CONTATO` em `index.html`.
- Simulador de resfriamento: fórmulas em `resf()`. Vazão de ar = P / (1,2 × 1,006 × ΔT); água = P × 3,6 / (4,18 × ΔT); unidades pela redundância escolhida.

Conteúdo técnico educativo. Projetos exigem estudos de campo e responsabilidade técnica (ART) de profissional habilitado no CREA.

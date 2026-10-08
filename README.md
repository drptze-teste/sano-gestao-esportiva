# Do Right — Landing BRASIL (doright-br)

> ⚠️ Projeto SEPARADO. Não confundir com o `doright-fit` (landing dos expatriados).

Segunda landing page do **Do Right**, voltada ao público **do Brasil** (preços em R$, realidade local).

## O que é
- Site estático (HTML único) hospedado no **GitHub Pages**.
- Repo: `drptze-teste/doright-br`
- Preview: https://drptze-teste.github.io/doright-br/
- **`noindex`** (não aparece em buscas — evita que cliente ache esta versão com preços diferentes).
- Apelo principal: **aulas online e AO VIVO com professores**, contratáveis pelo plano **ou avulso**.

## Diferenças vs. a landing principal (doright-fit / doright.fit)
- Copy adaptada: sem ângulo de expatriado (sem fuso/exterior/cidades estrangeiras); cidades BR, moeda R$.
- Sem seletor PT/EN (público é Brasil).
- Preços e links de cadastro são **em reais** (próprios, diferentes dos da versão internacional).

## Domínio (planejado)
`sanogestaoesportiva.com.br` — DNS no **Registro.br**. Apontar A records de Firebase (199.36.158.100) → GitHub Pages (185.199.108/109/110/111.153) e setar o custom domain no repo.
(O app Quick Massage sai desse domínio mas continua em `agenda-quick-benesse.web.app`.)

## PENDENTE
- [ ] Preencher os **3 preços em R$** (hoje `R$ •••`)
- [ ] Preencher os **3 links de cadastro BR** (hoje `#LINK_BASIC/PREMIUM/VIP_BR`)
- [ ] Trocar os **depoimentos ilustrativos** (marcados "(exemplo)") por reais
- [ ] Apontar o domínio no Registro.br

## Deploy
Editar `index.html` → commit → push `main`. O GitHub Pages publica sozinho em 1-2 min.

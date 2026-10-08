# Sano Gestão Esportiva — Site

> ⚠️ Projeto SEPARADO. Marca própria, NÃO é o Do Right (que fica em `doright-fit` / doright.fit).
> Nasceu como a versão BR do Do Right e virou **marca independente**: Sano Gestão Esportiva.

Personal training **online com aulas ao vivo** (professores de verdade), público **Brasil**, preços em R$.

## O que é
- Site estático (HTML único) no **GitHub Pages**.
- Repo: `drptze-teste/sano-gestao-esportiva`
- Preview: https://drptze-teste.github.io/sano-gestao-esportiva/
- **Indexável** (SEO próprio — tem identidade/nome próprios, não concorre com "Do Right").
- Apelo principal: **aulas online e AO VIVO com professores**, contratáveis pelo plano **ou avulso**.

## Identidade visual ("esportivo e forte")
- Paleta: grafite `#0C0E0D` + **verde-limão elétrico `#B4FF00`** + off-white `#F3F6F1`.
- Fontes: **Anton** (títulos/logo, pesado atlético) + **Inter** (corpo).
- Logo: wordmark **SANO** (O em lime) + tagline **GESTÃO ESPORTIVA**.
- Distinta do Do Right (azul escuro) e do Sano Pilates (terroso/creme).

## PENDENTE (tudo personalizado da Sano)
- [ ] **WhatsApp próprio** (placeholder `#WHATSAPP_SANO`)
- [ ] **3 preços em R$** (placeholder `R$ •••`)
- [ ] **3 links de cadastro** (placeholder `#LINK_BASIC/PREMIUM/VIP_BR`)
- [ ] **Instagram** (`#INSTAGRAM_SANO`) e **Área do Aluno** (`#AREA_ALUNO_SANO`) — definir se usa app próprio ou o mesmo
- [x] **Animação do hero** (mockup do app + pulso/batimento = SANO) — feita (CSS/SVG, classes `.hp-*`)
- [x] **Cena "Aula ao vivo"** (seção `#aula-ao-vivo`, classes `.lv-*`): professora no escritório explica → cena inverte → aluno na academia, ela corrige pelo vídeo (loop 14s, SVG+SMIL, respeita prefers-reduced-motion). Ilustração em código, não é filmagem — dá pra trocar por vídeo real depois.
- [ ] **Blog próprio** (repo + automação, etapa futura)
- [ ] **Domínio** `sanogestaoesportiva.com.br` — DNS no Registro.br (Firebase → GitHub Pages). O Quick Massage continua em agenda-quick-benesse.web.app.
- [ ] Trocar os **depoimentos "(exemplo)"** por reais

## Deploy
Editar `index.html` → commit → push `main`. GitHub Pages publica em 1-2 min.

# tm creative lab — quiz de pacotes

Site estático em HTML/CSS/JS puro, sem build, da "tm creative lab". O contexto de marca abaixo é regra fixa do projeto.
- `index.html`: home (landing de uma coluna; os CTAs levam a `quiz/index.html#comecar`; links apontam para o arquivo, não para a pasta, para funcionar também via file://).
- `quiz/index.html`: quiz que recomenda pacotes de social media. O hash `#comecar` pula a capa. Caminhos de assets começam com `../`.

## Fonte da verdade
- Manual: `./_Manual_ID_Visual_TMLab.pdf` (PDF de imagens, sem texto extraível; os valores abaixo foram transcritos dele).
- Logos originais: `./_Arquivos_Logo/` (somente leitura). Versões para web em `./assets/brand/` (ver `assets/brand/README.md`).

## Conceito
"Alquimia criativa": a borboleta representa transformação, reinvenção e liberdade. O estilo trabalha contrastes: força e delicadeza, estrutura e organicidade, racionalidade e atmosfera, precisão e fluidez. Estética editorial e cinematográfica, com texturas táteis e detalhes delicados. Assinatura verbal: "alquimia do afeto em *estratégia*" (com "estratégia" em serifa itálica).

## Paleta oficial
Base escura:
- `--vinho` #582035 (poder, profundidade) — Pantone 7421 C
- `--terra` #662D33 (força, base) — Pantone 188 C
- `--argila` #6B3A38 (criação, matéria) — Pantone 491 C
- `--bronze` #7B3E3B (aconchego, conforto) — Pantone 492 C (hex lido em baixa resolução; confirmar no PDF)

Neutros:
- `--perola` #E0D6D6 (calma, suavidade) — Pantone 7604 C
- `--nuvem` #CAC4C7 (imaginação, sonho) — Pantone 434 C

Vibrantes:
- `--rubi` #8F1533 (vida, paixão) — Pantone 187 C
- `--red` #AF0731 (amor, vibração) — Pantone 186 C → cor do logotipo
- `--pink` #C75973 (energia) — Pantone 191 C
- `--rosa-silvestre` #D07D9B (clareza, luz) — Pantone 190 C
- `--linho-rose` #C98B98 (afeto, cuidado) — Pantone 493 C → cor da borboleta
- `--algodao-doce` #D8A4B0 (conexão, acolhimento) — Pantone 494 C

Nenhuma cor fora dessa lista, exceto branco #FFFFFF e `--perola-50` #F7F2F2 (tinta clara da Pérola, para fundos amplos). Proibido: #F1EEEA, #B23A5E, #5C1030, #A0656B, preto puro.

## Contraste
- Texto principal: Vinho sobre branco/Pérola, ou branco/Pérola/Algodão doce sobre Vinho.
- Destaques e CTAs: Red (#AF0731) com texto branco.
- Linho Rosé (2,75:1) e Nuvem (1,72:1) **nunca** como cor de texto sobre fundo claro. Só símbolo, bordas, divisórias e formas decorativas.
- Fundos fora da paleta: logo monocromático (branco ou cor da paleta), o de melhor leitura.

## Tipografia
- Texto, interface, labels: **Host Grotesk** (Google Fonts), 300/400/500/700 + itálicos. Na web, nunca abaixo de 14px.
- Títulos, frases curtas e palavras de destaque: **Albra Display** Medium Italic (comercial, fora do Google Fonts). Enquanto não houver arquivo licenciado em `./fonts/`, usar **Fraunces** italic (opsz alto, 400–500, SOFT 50) como fallback.
- Padrão editorial: frase em Host Grotesk Regular com UMA palavra-chave em serifa itálica (ex.: "conectada com *alquimia criativa*").
- Labels/eyebrows: Host Grotesk 500, caixa alta, letter-spacing 0.3em, Red ou Pink.
- Títulos de seção: pequeno quadrado chapado (■) em Nuvem antes do título.

## Logo
- Nunca recriar o logo em texto ou CSS; usar os arquivos de `assets/brand/`.
- Preferencial: `logo-principal.svg` / `logo-horizontal.svg` (borboleta Linho Rosé + texto Red) sobre fundo claro.
- O logotipo é escrito em minúsculas: "tm creative lab".
- Área de proteção mínima igual à altura do "t"; nunca distorcer, girar, aplicar sombra ou mudar as cores.
- Ilustrações do manual (pássaros, flores, fotos) não entram no site.

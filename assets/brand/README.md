# assets/brand

Gerado a partir de `../../_Arquivos_Logo/` (originais intocados). Os SVGs foram extraídos dos PDFs vetoriais com PyMuPDF: fundo chapado removido, viewBox ajustado ao desenho e cores normalizadas para os hex oficiais (o PDF traz conversões de CMYK, por exemplo #D21F39 → #AF0731, #DC8695 → #C98B98, #631434 → #582035). Cada SVG foi renderizado e comparado com o PNG original; a forma coincide em mais de 98% dos pixels (a diferença fica no anti-aliasing das bordas).

Para cada SVG com PNG de origem também há rasters recortados em `-320`, `-640` e `-1280` px de largura, em `.png` e `.webp`.

| Arquivo | Origem (PDF, página = PNG) | Quando usar |
|---|---|---|
| `logo-principal.svg` | TM_Creative_Lab.pdf p1 = TM_Creative_Lab-01 | Logo preferencial sobre fundo claro |
| `logo-principal-negativo.svg` | TM_Creative_Lab.pdf p3 = TM_Creative_Lab-03 | Sobre Vinho (texto branco + borboleta rosé) |
| `logo-horizontal.svg` | TM_Creative_Lab_horizontal.pdf p1 = horizontal-01 | Header do site |
| `logo-horizontal-negativo.svg` | TM_Creative_Lab_horizontal.pdf p3 = horizontal-03 | Header sobre fundo escuro |
| `logo-linha.svg` | TM_Creative_Lab_Simbolo/TM_Creative_Lab_assinatura_horizontal.pdf p1 = assinatura_horizontal-01 | Linha única Red: rodapé, espaços estreitos |
| `logo-linha-branco.svg` | idem p3 = assinatura_horizontal-03 | Linha única branca sobre Vinho/Red/foto |
| `logo-reduzido.svg` | TM_Creative_Lab_reduzido.pdf p1 = reduzido-01 | "tm lab" Red, espaços pequenos |
| `logo-reduzido-branco.svg` | TM_Creative_Lab_reduzido.pdf p2, sem o fundo Red | "tm lab" branco sobre Vinho (card de resultado). Sem PNG equivalente |
| `simbolo-rose.svg` | TM_Creative_Lab_simbolo.pdf p1 = simbolo-01 | Marca d'água, elemento gráfico |
| `simbolo-branco.svg` | idem p4 = simbolo-04 | Sobre formas coloridas / Vinho |
| `simbolo-vinho.svg` | idem p5 = simbolo-05 | Ícone sobre fundo claro |
| `simbolo-red.svg` | idem p6 = simbolo-06 | Ícone, favicon |
| `favicon.svg` | cópia de simbolo-red.svg | `<link rel="icon">` |
| `favicon-32.png` | simbolo-06 recortado | Fallback do favicon |
| `apple-touch-icon.png` | simbolo-01 sobre Vinho, 18% de respiro, 180×180 | iOS |
| `icon-512.png` | idem, 512×512 | Manifest / ícone de app |
| `og-image.png` | composição 1200×630 | Open Graph / Twitter |

Observação: o PDF `_Arquivos_Logo/TM_Creative_Lab_Simbolo/TM_Creative_Lab_assinatura_horizontal.pdf` está na pasta errada (é a assinatura horizontal); o símbolo vem de `_Arquivos_Logo/TM_Creative_Lab_simbolo.pdf`.

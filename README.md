# email-assets

Imagens hospedadas para as campanhas de e-mail do Grupo AJ.
Servidas via CDN jsDelivr.

## 20-anos (sequencia de storytelling, 5 capitulos)

| arquivo | uso | arquivo | exibe em |
|---|---|---|---|
| `20-anos/cap1-header-desktop-v2.png` | Cap. 1 - topo, desktop | 1200 x 300 (4:1) | 600 px |
| `20-anos/cap1-header-mobile-v2.png`  | Cap. 1 - topo, mobile  | 600 x 200 (3:1)  | largura da tela |
| `20-anos/cap1-meio-desktop-v2.png`   | Cap. 1 - meio, desktop | 1200 x 300 (4:1) | 600 px |
| `20-anos/cap1-meio-mobile-v2.png`    | Cap. 1 - meio, mobile  | 600 x 200 (3:1)  | largura da tela |

Base da URL:
`https://cdn.jsdelivr.net/gh/GrupoAJBIM/email-assets@main/`

O swap desktop/mobile e feito por media query no proprio HTML do e-mail
(breakpoint 620 px). O Outlook desktop ignora media query e sempre recebe
a versao desktop, que e o comportamento desejado.

## Cache

O jsDelivr mantem `@main` em cache por ate 12h. Nunca sobrescreva uma arte
que ja foi publicada: suba com sufixo novo (`-v3`) e atualize o `src` no HTML.

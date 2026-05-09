# Studio Ju Castro — Landing Page

Página de agendamentos para o estúdio de estética da Ju Castro.

## Estrutura
- `index.html` — landing page (single file)
- `photos/` — fotos da Ju (jpg) + placeholders SVG de fallback
- `vercel.json` — config de deploy

## Fotos
A landing usa 5 fotos. Coloque-as em `photos/` com os nomes abaixo:

| Slot | Arquivo | Onde aparece |
|------|---------|--------------|
| 1 | `photos/foto1.jpg` | Hero (lado direito, foto principal) |
| 2 | `photos/foto2.jpg` | Card "Pelotas" |
| 3 | `photos/foto3.jpg` | Seção Instagram (lateral direita) |
| 4 | `photos/foto4.jpg` | Card "Campinas" |
| 5 | `photos/foto5.jpg` | Seção "Sobre o studio" (closeup) |

Enquanto os JPGs não estão lá, o site usa SVGs de placeholder com cores nude/rose.

## Deploy
```bash
vercel --prod
```

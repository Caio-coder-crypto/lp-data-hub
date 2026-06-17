# DataHub — Landing Page

Página de vendas (estática) do DataHub · Revenue Intelligence Platform.

## Conteúdo
- `index.html` — página única (HTML + CSS + JS vanilla, sem build).
- `assets/` — logo oficial e favicons.

## Deploy no Vercel
É um site **estático** — não precisa de build.

**Opção 1 — arrastar:** vercel.com → *Add New → Project* → arraste esta pasta.

**Opção 2 — CLI:**
```bash
npm i -g vercel
vercel          # preview
vercel --prod   # produção
```

**Opção 3 — GitHub:** suba este repositório e conecte no Vercel (deploy a cada push).

## Personalização rápida
- Número de WhatsApp: variável `WA` no `<script>` (rodapé do `index.html`).
- Link do app: botões "Acessar plataforma" → `https://datahub-delta.vercel.app/`.
- Planos/preços: seção `#planos`.

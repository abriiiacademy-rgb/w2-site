# W2 Engenharia & Arquitetura — Landing Page

Landing page de alta conversão para a **W2 Engenharia & Arquitetura** (Indaial/SC), focada em
projeto arquitetônico + gerenciamento de obra de alto padrão.

Atende o Vale Europeu e o litoral norte de Santa Catarina — Balneário Camboriú, Itajaí e Itapema.

## Estrutura

```
.
├── index.html          # Página única (HTML + CSS + JS inline)
└── assets/
    ├── logo-w2.png     # Marca W2 (arco + traço)
    └── engenheira.jpg  # Foto da engenheira-arquiteta
```

Site estático, sem build. Basta abrir o `index.html` ou servir a pasta.

## Publicação no GitHub Pages

1. Crie um repositório no GitHub (ex.: `w2-landing`).
2. Faça o push deste diretório (instruções abaixo).
3. No GitHub: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main** / pasta **/ (root)** → **Save**
4. Em ~1 min o site fica no ar em `https://<usuario>.github.io/<repo>/`.

> Domínio próprio: quando contratarem, adicione um arquivo `CNAME` com o domínio
> e configure o DNS (registro CNAME apontando para `<usuario>.github.io`).

## Pendências (configurar depois)

- [ ] **Meta Pixel** — colar o código no bloco comentado do `<head>` do `index.html`.
- [ ] **Google Tag (gtag/GTM)** — colar no bloco comentado do `<head>`.
- [ ] Hospedagem definitiva + domínio próprio.

## Contato (dados em produção)

- WhatsApp: **(47) 99771-1332**
- Instagram: **@w2.engenharia**
- Endereço: Rua Marechal Deodoro da Fonseca, 545 — Sala 1, Tapajós, Indaial/SC, 89130-000

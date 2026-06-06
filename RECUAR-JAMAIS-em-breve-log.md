# Recuar Jamais Motors — Página "Em Breve"
**Sessão:** 05 de junho de 2026  
**Agência:** Web72 | **Cliente:** Recuar Jamais Motors  

---

## ✅ O que foi feito

### 1. Página "Em Breve" (`index.html`)
- HTML/CSS/JS puro, standalone, sem dependências externas
- Vídeo de fundo embedado em base64
- Logo vertical (Full) centralizada
- Countdown regressivo para **08/06/2026 às 08h00**
- Animações: mouse gradient, ripple, floating dots, grid SVG, word-appear, underline-grow
- Botões de redes sociais abaixo do contador:
  - Instagram: https://www.instagram.com/recuarjamaismotors/
  - Facebook: https://www.facebook.com/profile.php?id=61590315941830
  - WhatsApp: https://wa.me/5545991458812
- Créditos no rodapé: Recuar Jamais Motors · Cascavel — PR · © 2026
- Favicon: `FAVICON.svg`
- Open Graph configurado com `breve-Open-Graph.png`

---

### 2. Deploy

| Item | Valor |
|---|---|
| Repositório GitHub | https://github.com/rogerioweb72/recuar-jamais-em-breve |
| URL Netlify | https://wondrous-pithivier-b905ca.netlify.app |
| Domínio produção | https://recuarjamaismotors.com.br |
| Pasta local | `/Users/rogeriolima/Documents/projetos lovable/RECUAR JAMAIS/em breve` |

---

### 3. DNS — Hostinger (Opção B)

| Tipo | Nome | Valor | TTL |
|---|---|---|---|
| `A` | `@` | `75.2.60.5` | 3600 |
| `CNAME` | `www` | `wondrous-pithivier-b905ca.netlify.app` | 3600 |

---

### 4. Open Graph

```html
<meta property="og:image" content="https://recuarjamaismotors.com.br/breve-Open-Graph.png">
<meta property="og:image:width" content="1200">
<meta property="og:image:height" content="630">
```

Imagem: `breve-Open-Graph.png` (1200×630px) — já no repositório.  
> ⚠️ WhatsApp faz cache — testar com `?v=2` no final da URL se não carregar.

---

### 5. Fluxo de atualização

```bash
cd "/Users/rogeriolima/Documents/projetos lovable/RECUAR JAMAIS/em breve"
git add .
git commit -m "descrição da mudança"
git push origin main
# Netlify redeploya automaticamente em ~30s
```

---

## 📋 Pendências

- [ ] Confirmar exibição da imagem Open Graph no WhatsApp (cache pode demorar)
- [ ] Substituir data do countdown quando definida data real de lançamento
- [ ] Após lançamento: substituir página por site vitrine (Item 02 do escopo)

---

## 🎨 Design System

| Token | Valor |
|---|---|
| Background | `#070708` |
| Gold principal | `#c39043` |
| Gold claro | `#e9cf95` |
| Fontes | Rajdhani, Saira Condensed, Montserrat |

---

*Gerado por Claude (Web72) — Projeto Recuar Jamais Motors*

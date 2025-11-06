# Portfólio — Jaime Guilherme

Site profissional de **Jaime Guilherme Caceda**, técnico em eletrônica com 15 anos de experiência e formação em informática. Oferece serviços de manutenção eletrônica, automotiva, energia, alarmes, redes e desenvolvimento de sites.

---

## Funcionalidades Incluídas (Atualizado — Novembro 2025)

- **Design moderno e responsivo** com layout fluido em todos os dispositivos  
- **Hero section impactante** com CTA direto para contato  
- **Logotipo animado com parallax suave** ao rolar a página  
- **Cards de projetos com efeito glow neon** ao passar o mouse  
- **Botão flutuante do WhatsApp com animação de pulso**  
- **Títulos com sublinhado animado** ao entrar na tela  
- **Modo escuro (dark mode)** com alternância e persistência (localStorage)  
- **Fundo com gradiente + textura de circuito sutil** (efeito tech)  
- **Lightbox responsivo** para ampliar imagens dos projetos  
- **Formulário de contato com validação e envio via Formspree** (com fallback)  
- **Acessibilidade completa**: `skip-link`, `aria-labels`, foco visível, contraste  
- **Animações suaves e performance otimizada** com `clamp()`, `transition` e `scroll-behavior`

---

## Como Usar

1. **Abra `index.html`** no navegador para testar localmente.
2. **Edite o conteúdo** diretamente no `index.html`:
   - Seção "Sobre mim"
   - Lista de serviços
   - Projetos (imagens, títulos, descrições)
   - Links do LinkedIn e currículo
3. **Substitua as imagens** na pasta (mantenha os nomes ou atualize os `src`):
   - `JGC-bytesolutions.png` → logotipo no cabeçalho
   - `jaime-medindo-quadro.jpeg`
   - `painel-no-break.jpeg`
   - `print-site-skiva.png`
   - `Jaime-Curriculo-2025.pdf` → currículo para download

---

## Arquivos Importantes

| Arquivo | Descrição |
|-------|---------|
| `index.html` | Estrutura completa do site (header, seções, scripts) |
| `estilo.css` | Todos os estilos modernos, animações, dark mode e responsividade |
| `JGC-bytesolutions.png` | Logotipo oficial (canto superior esquerdo) |
| `jaime-medindo-quadro.jpeg` | Imagem do projeto 1 |
| `painel-no-break.jpeg` | Imagem do projeto 2 |
| `print-site-skiva.png` | Imagem do projeto 3 |
| `Jaime-Curriculo-2025.pdf` | Currículo em PDF (link de download) |

---

## Melhorias Recomendadas (Próximos Passos)

- [ ] **Otimizar imagens para WebP** (reduzir tamanho sem perda de qualidade)
- [ ] **Adicionar página de projeto individual** (ex: `/projetos/diagnostico-eletrico.html`)
- [ ] **Integrar Google Analytics** ou **Plausible** para acompanhar visitas
- [ ] **Adicionar seção de depoimentos** com carousel
- [ ] **Criar versão em inglês** (`index-en.html`)
- [ ] **Hospedar com HTTPS via GitHub Pages, Netlify ou Vercel**

---

## Deploy Rápido (GitHub Pages)

```bash
git init
git add .
git commit -m "Deploy: site profissional com design moderno"
git branch -M main
git remote add origin https://github.com/seu-usuario/seu-repositorio.git
git push -u origin main
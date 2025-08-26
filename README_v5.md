# Scanner de Mídias Ativas – eRetail (v5)

Protótipo em **HTML/CSS/JS** para varredura de mídias ativas nos sites de clientes do portfólio Heineken Brasil.

## 🚀 Recursos
- **Tabela de ocorrências**: cada linha mostra a marca, preview da mídia (thumb) e URL.
- **Pré-visualização expandida**: clique em “Pré-visualizar maior” para ver a imagem em destaque.
- **Filtro por marca**: selecione apenas uma marca ou visualize todas.
- **Download**: opção de baixar a mídia ou abrir em nova aba.
- **Refazer / Ver resultado**: botões rápidos para reiniciar a varredura ou rolar até a tabela.
- **Fallback de HTML bruto**: se a leitura via proxy falhar (CORS, sites dinâmicos), copie o código-fonte (Ctrl+U) e cole para análise.

## 📦 Estrutura
- `index.html` – arquivo único que contém todo o protótipo (HTML, CSS e JS).
- `README.md` – este guia de uso.

## 🔧 Como usar
1. Abra `index.html` no navegador ou publique em um host estático (Netlify, GitHub Pages, Vercel).
2. Insira a **URL do cliente** e clique em **Verificar (via proxy)**.  
   - Se o site bloquear, abra a página → **Ctrl+U** → copie o HTML bruto → cole no campo → clique **Executar com HTML**.
3. Use o **filtro de marca** para refinar resultados.
4. Baixe as mídias ou exporte CSV.

## 🌐 Hospedagem rápida (Netlify)
- Entre em [Netlify Drop](https://app.netlify.com/drop).
- Arraste o `index.html` ou o `.zip` com o arquivo dentro.
- O Netlify gera um link público (ex.: `https://scanner-midias.netlify.app`).

## 🖥️ Compatibilidade
- Funciona em navegadores modernos (Chrome, Edge, Firefox).
- Para visualização de imagens bloqueadas por hotlink, foi adicionado um proxy (`images.weserv.nl`).

## ⚠️ Limitações
- Sites que carregam banners apenas via JavaScript podem não aparecer no proxy.
- A precisão da data é apenas tentativa (baseada em nome do arquivo).

---
👩‍💻 Desenvolvido como protótipo para apoiar o time de eRetail Heineken Brasil.

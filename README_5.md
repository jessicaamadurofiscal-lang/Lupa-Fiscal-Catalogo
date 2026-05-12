# Catálogo Comercial — Lupa Fiscal · Grupo Sousa & Couto

Site estático com o catálogo comercial de produtos da Lupa Fiscal (Reforma Tributária + Planejamento Tributário + Recuperação de Créditos + Revisão Cadastral), para uso interno do time de consultores comerciais.

## Conteúdo

- `index.html` — catálogo (HTML + CSS + JS, tudo em um único arquivo)
- `render.yaml` — configuração do Render

## Como publicar no Render

### Passo 1 — Subir os arquivos para o GitHub

1. Entre em https://github.com e clique em **New repository** (canto superior direito → "+").
2. Nome sugerido: `catalogo-comercial-lupa-fiscal`.
3. Marque **Private** (recomendado).
4. Marque **Add a README file** e clique em **Create repository**.
5. Dentro do repositório, clique em **Add file → Upload files**.
6. Arraste `index.html` e `render.yaml` desta pasta para a área de upload.
7. Clique em **Commit changes**.

### Passo 2 — Criar o site no Render

1. Entre em https://dashboard.render.com.
2. Clique em **+ New → Static Site**.
3. Selecione o repositório `catalogo-comercial-lupa-fiscal`.
4. Preencha:
   - **Name:** `catalogo-comercial-lupa-fiscal`
   - **Branch:** `main`
   - **Build Command:** *(deixe em branco)*
   - **Publish Directory:** `.` (apenas um ponto)
5. **Instance Type:** Free.
6. Clique em **Create Static Site**.

### Passo 3 — Aguardar o deploy (~1–2 minutos)

URL final: `https://catalogo-comercial-lupa-fiscal.onrender.com`

### Passo 4 — Compartilhar com o time

Mande a URL para os consultores. Pronto.

## Atualizar o catálogo

1. Gere o `index.html` atualizado.
2. No GitHub: abra o repositório → `index.html` → ícone de lápis → cole o novo conteúdo → **Commit changes**.
3. O Render detecta o commit e refaz o deploy em ~1 minuto.

## Custom domain (opcional)

Sugestões: `catalogo.lupafiscal.com.br` ou `catalogo.reformatributariainteligente.com`.
No painel do Render → **Settings → Custom Domains** → siga as instruções de CNAME.

## Observações

- **URL pública:** sem proteção de acesso. Compartilhe apenas com o time comercial.
- **Plano Free:** Static Sites no Render não hibernam e são gratuitos até 100 GB/mês de banda.

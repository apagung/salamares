cd /Users/a.pagung/projetos/salamares
git init
git remote add origin https://github.com/apagung/salamares.git

cp 08-entregaveis/brand-book.html index.html
cp 08-entregaveis/aplicacoes-visuais.html .
cp 08-entregaveis/prompts-canva.html .
git add index.html aplicacoes-visuais.html prompts-canva.html
git commit -m "Brand book completo — Botequim Salamares"
git push -u origin main

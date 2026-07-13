# Robson Ramos — Site (versão publicável)

## O que tem aqui
- index.html  -> o site completo, convertido para HTML/CSS/JS puro (funciona em qualquer hospedagem)
- assets/     -> todas as imagens (otimizadas para carregar rápido)
- vercel.json -> configuração que garante o deploy correto na Vercel

## Como subir (passo a passo)
1. No GitHub, abra seu repositório e APAGUE os arquivos antigos.
2. Suba TUDO que está dentro desta pasta: index.html, vercel.json e a pasta assets inteira.
   IMPORTANTE: a pasta assets precisa ir junto, com esse mesmo nome, na raiz do repositório.
3. Na Vercel: Deployments -> três pontinhos -> Redeploy.

Se ainda der erro: Settings -> General -> Framework Preset = "Other",
Output Directory em branco, salvar e Redeploy.

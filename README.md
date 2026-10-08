# Finan+ — site oficial

Landing page do [Finan+](https://github.com/finanplus-web), app de finanças pessoais gratuito, de código aberto (GPL-3.0) e offline, para Android, web e Linux.

Site estático (HTML + imagens), hospedado no GitHub Pages em **https://finanplus-web.github.io/**.

## Estrutura

```
index.html          página principal
404.html            página de erro (volta para o início)
favicon.ico         ícone da aba
assets/             ícones, foto, imagem de prévia (og-image.png)
assets/telas/       capturas de tela do Android, da web e do Linux
.nojekyll           faz o GitHub Pages servir os arquivos sem processamento
```

## Como publicar

1. Na conta **finanplus-web**, crie um repositório público chamado exatamente `finanplus-web.github.io`.
2. Envie todo o conteúdo desta pasta para a raiz do repositório (incluindo o arquivo oculto `.nojekyll`).
3. Em **Settings › Pages**, em *Build and deployment*, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)`, e salve.
4. Aguarde 1 a 2 minutos e abra https://finanplus-web.github.io/

A versão web do app continua em https://finanplus-web.github.io/finan_plus/.

## Como atualizar

Edite os arquivos, faça commit e push na branch `main`. O GitHub Pages republica sozinho.

## Licença

GPL-3.0 · © 2026 Juscelino Be

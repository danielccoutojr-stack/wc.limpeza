[README.md](https://github.com/user-attachments/files/32586533/README.md)
# WC Limpezas — Landing Page

Landing page da **WC Limpezas** (higienização e impermeabilização de estofados), em Brasília-DF.

Página única em HTML/CSS/JS puro, sem dependências externas de build — é só abrir o `index.html` no navegador ou publicar em qualquer host estático.

## Estrutura

```
index.html   → página completa (estrutura, estilo e scripts em um único arquivo)
```

As imagens (logo e fotos de antes/depois) já estão embutidas no HTML como base64, então não há pasta `assets` — o arquivo funciona sozinho.

## Como publicar no GitHub Pages

1. Suba este `index.html` para a raiz do repositório.
2. Vá em **Settings → Pages**.
3. Em **Branch**, escolha `main` e a pasta `/ (root)`.
4. Salve. Em alguns minutos o link fica disponível em `seuusuario.github.io/nome-do-repo`.

## Personalização rápida

Abra o `index.html` num editor de texto e procure por:

| O que mudar | Onde procurar |
|---|---|
| Telefone / WhatsApp | busque por `5561984141057` (aparece nos links `wa.me`) |
| Endereço | busque por `Quadra QSA 15` |
| Instagram | busque por `instagram.com/wclimpezas` |
| Cores da marca | topo do arquivo, dentro de `:root { --navy: ...; --blue: ...; }` |
| Textos das seções | cada seção tem um `<h2>` e um parágrafo logo abaixo, fáceis de localizar pelo texto atual |

## Domínio próprio (opcional)

Depois de ativar o GitHub Pages, em **Settings → Pages → Custom domain** dá para apontar um domínio próprio (ex: `wclimpezas.com.br`), configurando o DNS conforme a documentação do GitHub.

---
Site desenvolvido com apoio do Claude (Anthropic).

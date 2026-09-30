# Prancheta — repositório de teste e build

Este repositório guarda o build atual do Prancheta e materiais de desenvolvimento/histórico. O site público usa a cópia publicada no repositório `site`.

## Downloads ativos

- **Android 1.1:** https://reboclbrank-max.github.io/site/prancheta/baixar.htmlbaixar.html
- **Jogo web:** https://reboclbrank-max.github.io/site/prancheta/baixar.html
- APK no `main`: `Prancheta.apk` — `pacote-anterior`, versionName `1.1`, versionCode `2`, arm64-v8a, Android 7/API 24+.

A versão Android 1.1 publicada no site fica em `site/prancheta/baixar.htmlPrancheta-1.1.apk`. Ela usa identificador Android diferente do APK antigo 1.0, então instala separadamente; não sobrescreve nem migra dados da versão anterior.

## Arquivos do build web

Os arquivos `index.html`, `index.js`, `index.wasm` e `index.pck` na raiz formam a exportação web. O site preserva sua própria página PWA e service worker e sincroniza o PCK com esse build.

## Mapa do repositório

- `projetos/02-prancheta/`: projeto e documentação do Prancheta.
- `Prancheta.apk` e `index.*`: build Android/web na raiz.
- `projetos/01-ceifalume/`, `empresa/` e documentos gerais: materiais preservados de outros trabalhos/histórico; não são necessários para gerar o Prancheta. Ficam aqui até eventual organização aprovada; não apagar por suposição.
- Tags e releases antigas: histórico de builds, mantido para consulta/rollback.

## Integridade do APK 1.1 publicado

- Tamanho: 32.090.354 bytes.
- SHA-256: `3a1a1dfca67fbdf4a5077e127aacdb96d87e6548cf09525535812fed71076f5a`.
- Pacote `pacote-anterior`; sem permissões declaradas; assinatura Android V2/V3 conferida.
- O APK foi validado estruturalmente, mas não foi instalado em aparelho Android físico nesta sessão.

# Guia do próximo chat — Prancheta e organização dos repositórios

Atualizado em 30/09/2026. Falar em português do Brasil.

## Identidade definitiva

- **Prancheta é o único jogo e a única marca do produto.** O nome visível do app permanece **Prancheta 0.1**.
- Não apresentar versões antigas, protótipos ou publicações retiradas como jogos separados.
- Não criar rótulo visível 0.2. Correções Android avançam somente o `versionCode` oculto.
- Pacote ativo: `com.reboclbrank.prancheta`; assinatura, keystore e `.idsig` devem ser preservados.

## Estado confirmado

- Projeto Godot ativo local: `projetos/02-prancheta/godot/`.
- APK ativo: `godot/apk/prancheta-0.1.apk`, `versionCode 4`, 26.640.674 bytes.
- SHA-256: `d3878842a9ddc859149329382cd0ffc7669829734a7408c6b7446bdf739ec610`.
- Suíte automatizada: 98/98. Importação e inicialização headless verificadas.
- Falta instalar e testar em aparelho Android físico; ADB não estava conectado.
- Página pública: https://reboclbrank-max.github.io/site/prancheta/baixar.html.
- Deploy conferido: home e página retornam HTTP 200; o download confere com o arquivo local.
- A home lista Ceifalume 0.1, Prancheta 0.1 e Projeto 03 — Em breve.

## Repositórios

- `site/main`: histórico reescrito; head `39fd559ffa409417233b9b00aff54ab7721a0fb4`. Árvore, tags, deploy e APK ativo conferidos.
- Repositório neutro `projetos-arquivados`: renomeado e com histórico reescrito; head `5c94008087efdf6f4edf3a0c537cde67ee414611`. Ceifalume, empresa, outros projetos e credenciais de marketing preservados.
- `base/main`: migração concluída e verificada no commit `baa1bd7b8b636b414789c4a3527824e3ea06fbe9`; árvore ativa sem referências à marca anterior. APK, `.idsig`, keystores e credenciais preservados.

## Cuidados obrigatórios

- Não exibir, copiar, apagar ou rotacionar chaves e tokens. Não alterar valores de credenciais.
- Preservar o APK, o `.idsig`, o keystore ativo e quaisquer outras chaves de assinatura.
- Antes de qualquer atualização, conferir pacote e certificado; manter o mesmo pacote/assinatura do build ativo.
- Verificar links públicos após publicar. Comunicar falhas e limites; não prometer ausência total de bugs.
- Não apagar arquivos de Ceifalume, da empresa ou de outros projetos durante a reorganização de Prancheta.

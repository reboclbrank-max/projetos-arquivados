# Pendências ativas — 30/09/2026

## Prancheta 0.1

- [x] Nome definitivo e identidade única: Prancheta.
- [x] Versão visível mantida em 0.1; APK ativo `versionCode 4`.
- [x] Testes automatizados: 98/98; importação e inicialização headless verificadas.
- [x] Publicação atual conferida: https://reboclbrank-max.github.io/site/prancheta/baixar.html — home, página e APK responderam corretamente; SHA-256 conferido.
- [ ] Instalar e testar em aparelho Android físico; nenhum dispositivo ADB estava conectado durante a última verificação.
- [x] Migração para `projetos/02-prancheta/godot/` enviada em `base/main` (`baa1bd7`); auditoria da árvore atual sem caminhos ou textos com a marca anterior.

## Organização dos repositórios

- [x] Site público limpo e deploy conferido. A home lista Ceifalume 0.1, Prancheta 0.1 e Projeto 03 — Em breve.
- [x] Repositório de arquivo renomeado para `projetos-arquivados`; materiais não relacionados e credenciais de marketing preservados; builds substituídos e respectivas releases/tags removidos da árvore ativa.
- [x] Árvore e tags de `base/main` conferidas após a reescrita; APK, `.idsig`, keystores e credenciais preservados.
- [ ] Manter a documentação de Prancheta alinhada com a publicação e registrar qualquer nova correção.

## Outros projetos

- Ceifalume e documentos da empresa permanecem preservados. Antes de alterar qualquer conteúdo deles, conferir os respectivos documentos de progresso e decisões.
- Não apagar, exibir nem rotacionar credenciais, keystores, APKs ativos ou sidecars `.idsig`.

## Regra de publicação

Publicar somente após verificar o conteúdo e os links públicos. Manter o rótulo visível 0.1; qualquer correção Android futura incrementa apenas o `versionCode`. Registrar falhas e limites de teste com clareza.

# Pepsi Doidão Workspace

Todos os meus apps num lugar só: https://joaogabrielmontinirossi-sys.github.io/workspace/

- **Lista automática.** Todo repositório desta conta com site publicado (GitHub Pages) vira uma ficha. A lista vem direto da API do GitHub a cada visita.
- **Apps abrem aqui dentro.** Cada app abre numa aba do próprio Workspace; dá para deixar vários abertos e alternar. Ctrl+clique ou “Outra aba” abre fora.
- **Uma conta Google para todos.** Conectando a conta Google no Workspace, a mesma conexão é entregue a todos os apps, que passam a sincronizar com o Drive sem configurar um por um. O Alvorada recebe o ID do cliente pronto e conecta dentro dele, porque também pede a Agenda.
- **Favoritos sincronizados.** Favoritos e histórico de uso do Workspace vão para o arquivo `workspace-sync.json` na área privada do app no Google Drive.

Órbita, Capynote, Prisma, Lousa, Folhear e Ishikawa usam o módulo `gsync.js` (guardado aqui e copiado em cada app) para sincronizar pela conta Google no site e no celular. No programa de Windows eles continuam sincronizando pela pasta do Google Drive, que é uma cópia separada.

É um único arquivo, `index.html`, sem etapa de build.

# WEB-VERSION — Forma / HYVE beta

Fontes separadas do MVP para revisão da beta, sem credenciais ou dados reais.
Consulte o repositório HYVE-ORG/DOCS para o relatório e os limites de publicação.

Node 22.12+ (Node 24 recomendado). Execute `npm ci`, `npm run typecheck`, `npm test` e `npm run build`. O lockfile preserva o grafo completo já testado.

Frontend Vite. Build `dist`, raiz do projeto `.`. Vite serve `apps/web`. O aplicativo usa `/api` e `/socket.io` da mesma origem; o proxy de desenvolvimento não existe na Vercel. Leia `DEPLOYMENT.md` antes de publicar.

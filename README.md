# A Crônica dos 10 Dias — deploy na Vercel

1. Suba esta pasta para um repositório no GitHub (ou use `npx vercel` na pasta).
2. Na Vercel: Add New > Project > importe o repositório > Deploy.
3. No projeto, aba Storage > Marketplace > Upstash Redis (plano grátis) > Connect Project.
   (Isso cria as variáveis KV_REST_API_URL e KV_REST_API_TOKEN automaticamente.)
4. Settings > Environment Variables: crie ADMIN_PASSWORD (sua senha de admin) e, opcional, SECRET (texto aleatório).
5. Deployments > Redeploy.
6. Abra o site > aba Admin > cadastre os 10 Mestres e as regras > Salvar.
7. Cada Mestre usa a aba Mestre (ID + chave) e projeta o QR na sala.

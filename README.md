# VALORANT SKINS

Vitrine visual de skins de VALORANT criada para um trabalho acadêmico. A experiência foi pensada como um catálogo editorial, com destaque inicial, busca, filtros por arma e raridade, faixa de preço, ordenação, favoritos e modal de detalhes.

> Projeto conceitual para fins acadêmicos. Não é afiliado à Riot Games.

## Rodar localmente

Requer Node.js 18+ e pnpm 11+.

```bash
pnpm install
pnpm dev
```

Depois, abra o endereço mostrado pelo Vite no terminal.

Para gerar a versão de produção:

```bash
pnpm build
pnpm preview
```

## Subir para o GitHub

1. Crie um repositório novo no GitHub.
2. Envie todos os arquivos deste projeto, mantendo `package.json`, `pnpm-lock.yaml`, `pnpm-workspace.yaml`, `vercel.json`, `index.html`, `src/` e `public/`.
3. Não envie `node_modules/` ou `dist/`; eles já estão no `.gitignore`.

Pelo terminal, também é possível usar:

```bash
git init
git add .
git commit -m "feat: criar vitrine de skins de valorant"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git
git push -u origin main
```

## Publicar na Vercel

No painel da Vercel, escolha **Add New → Project**, importe o repositório do GitHub e mantenha as configurações do `vercel.json`. Se a Vercel pedir os campos manualmente, use:

- Framework Preset: **Vite**
- Install Command: `pnpm install --frozen-lockfile`
- Build Command: `pnpm build`
- Output Directory: `dist`

Não há variáveis de ambiente obrigatórias.

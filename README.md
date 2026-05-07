# FlowScore

App de produtividade, hábitos e metas pessoais.

## Deploy no GitHub Pages

1. Crie um repositório público no GitHub chamado `flowscore`
2. Faça upload de todos os arquivos desta pasta
3. Vá em Settings → Pages → Source: **Deploy from branch** → branch `main` → pasta `/`(root)
4. O app ficará disponível em `https://SEU_USUARIO.github.io/flowscore`

## Atualizar o app

Basta substituir o `index.html` pelo novo arquivo e fazer commit.

## Estrutura

```
flowscore/
├── index.html    ← App principal
├── sw.js         ← Service worker (PWA offline)
└── README.md
```

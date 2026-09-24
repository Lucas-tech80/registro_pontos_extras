# Políticas Corporativas

O site publicado é o `index.html` da raiz do repositório.

## Publicação
No GitHub:
`Settings → Pages → Build and deployment → Source → GitHub Actions`

## Supabase
Antes de publicar, abra `index.html` e configure:

```javascript
const SUPABASE_URL = 'SUA_PROJECT_URL';
const SUPABASE_ANON_KEY = 'SUA_CHAVE_PUBLICA';
```

Use apenas a chave pública `publishable/anon`.

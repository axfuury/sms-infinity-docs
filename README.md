# SMS Infinity — API Documentation

Documentação oficial da API do SMS Infinity, publicada via [Mintlify](https://mintlify.com).

## Estrutura

```
├── mint.json                  # Configuração do Mintlify
├── introduction.mdx           # Página inicial
├── guides/
│   ├── authentication.mdx     # Autenticação via Bearer Token
│   ├── quickstart.mdx         # Guia de início rápido (5 min)
│   ├── rate-limits.mdx        # Limites de requisição
│   └── errors.mdx             # Códigos de erro
└── api-reference/
    ├── balance.mdx            # GET /api/v1/balance
    ├── services.mdx           # GET /api/v1/services
    ├── create-activation.mdx  # POST /api/v1/activations
    ├── get-activation.mdx     # GET /api/v1/activations/:id
    └── cancel-activation.mdx  # POST /api/v1/activations/:id/cancel
```

## Desenvolvimento local

```bash
npm i -g mintlify
mintlify dev
```

## Deploy

O deploy é automático via GitHub. Qualquer `git push` na branch `main` atualiza a documentação.

---

© SMS Infinity. Todos os direitos reservados.

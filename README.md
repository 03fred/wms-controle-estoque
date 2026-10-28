# Armazém WMS

MVP estático para controle de estoque de pequeno porte. Abra `index.html` no navegador ou publique a raiz deste repositório no GitHub Pages.

## Demonstração

- Administrador: `admin@armazem.local` / `admin123`
- Operador: `operador@armazem.local` / `operador123`

O perfil de operador acessa o dashboard e as movimentações. O administrador também acessa o cadastro de produtos e os relatórios.

## Recursos

- Cadastro e alerta de estoque mínimo.
- Entradas simuladas com referência de NF-e e saídas com bloqueio de saldo insuficiente.
- Relatórios mensais com gráficos, resumo financeiro estimado e produtos expedidos.
- Dados de demonstração e alterações persistidos no `localStorage` do navegador.

## Publicação

No GitHub, habilite **Settings > Pages**, selecione a branch principal e a pasta `/ (root)`. O site será publicado como uma página estática.

> Login, perfis e dados são apenas demonstrativos e ficam no navegador. Não use credenciais ou informações reais: autenticação e autorização de produção exigem um backend.

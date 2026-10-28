# Controle de Estoque

Aplicação estática para operação de estoque, equipe e inventário. Abra `index.html` em um navegador ou publique a raiz do repositório no GitHub Pages.

## Demonstração

- Administrador: `admin@armazem.local` / `admin123`
- Operador: `operador@armazem.local` / `operador123`
- Funcionário: `funcionario@armazem.local` / `ponto123`

O administrador gerencia produtos, funcionários e relatórios. O operador registra movimentos e inventário. O funcionário acessa seu próprio registro demonstrativo de ponto.

## Recursos

- Cadastro de produtos com código de barras, saldo, estoque mínimo, peso e valor de referência.
- Entradas e saídas manuais ou pela tela de bipagem. Scanners USB que digitam o código e enviam Enter podem ser usados como entrada de texto.
- Cadastro de funcionários com acesso por e-mail e PIN.
- Registro alternado de entrada e saída do expediente, com histórico local.
- Contagem de inventário, registro da diferença e ajuste do saldo do produto.
- Dashboard, alertas, movimentações e relatórios mensais com gráficos.
- Valores financeiros estimados a partir da quantidade movimentada vezes o valor unitário; não representam transações de caixa reais.
- Dados persistidos no `localStorage` do navegador.

## Limitações

Login, PIN, autorização e dados são demonstrativos e ficam no navegador; não há sincronização entre dispositivos. Não use informações reais de funcionários ou operação. Autenticação, folha de ponto e armazenamento de produção exigem backend, controles de acesso e infraestrutura adequados.

## GitHub Pages

Configure **Settings > Pages** para publicar a branch `main` a partir da pasta `/ (root)`.

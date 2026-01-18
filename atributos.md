## :bookmark_tabs: Requisitos Funcionais

| :card_index:ID | :new: Requisito | :page_facing_up:Descrição |
|:-------------: | :------------- | :------------- |
| RF01  | [Cadastro de Usuário](diagrams/userSchema_RF01_CRUD_endpoint.md) | Permitir que novos usuários criem uma conta com nome, email e senha. |
| RF02  | [Login e Autenticação](diagrams/login_RF02_endpoint.md) | Autenticar usuários usando email e senha via JWT. |
| RF03  | [Cadastro de Receita](diagrams/incomeSchema_RF03_CRUD_endpoint.md) | Registrar receitas com data, valor, categoria e descrição. |
| RF04  | [Cadastro de Despesa](diagrams/expenseSchema_RF04_CRUD_endpoint.md) | Registrar despesas com data, valor, categoria e descrição. |
| RF05  | [Categorias Personalizadas](diagrams/categorias_RF05_endpoint.md) | Permitir categorias de receitas/despesas customizadas por usuário. |
| RF06  | [Metas Financeiras Mensais](diagrams/metas_RF06_endpoint.md) | Permitir definir e editar metas mensais de economia. |
| RF07  | [Relatórios por Período](diagrams/relatorios_RF07_endpoint.md) | Gerar relatórios mensais/anuais com receitas, despesas e saldo. |
| RF08  | [Gráficos e Visuais](diagrams/graficos_RF08_endpoint.md) | Mostrar gráficos (pizza, linha) com dados financeiros por período. |
| RF09  | [Exportar PDF](diagrams/exportarPDF_RF09_endpoint.md) | Exportar relatórios mensais para PDF. |
| RF10  | [Dashboard Responsivo](diagrams/dashboard_RF10_endpoint.md) | Exibir resumo financeiro em dashboard adaptado a dispositivos móveis. |
| RF11  | [Multiusuário](diagrams/multiusuario_RF11_endpoint.md) | Cada usuário só pode acessar seus próprios dados. |
| RF12  | [Logout](diagrams/logout_RF12_endpoint.md) | Encerrar sessão de forma segura. |


----------

## 📐 Regras de Negócio Associadas

| Status  | Regra |
| :-------------: | :------------- | 
| :white_check_mark:  | O saldo mensal será calculado como: saldo = receitas - despesas  |
| [	]  | Despesas não podem ter valor negativo.  |
| [	]  | Categorias essenciais não podem ser removidas, apenas ocultadas.  |
| [	]  | Relatórios exportados devem conter nome do usuário, mês/ano e saldo total.  |

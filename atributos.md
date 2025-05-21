## :bookmark_tabs: Requisitos Funcionais

|:card_index:ID | :new: Requisito |:page_facing_up:Descrição |
|:-------------: | :------------- | :------------- |
| RF01  | Cadastro de Usuário  | Permitir que novos usuários criem uma conta com nome, email e senha.  |
| RF02  | Login e Autenticação  | Autenticar usuários usando email e senha via JWT.  |
| RF03  | Cadastro de Receita  | Registrar receitas com data, valor, categoria e descrição.  |
| RF04  | Cadastro de Despesa  | Registrar despesas com data, valor, categoria e descrição.  |
| RF05  | Categorias Personalizadas  | Permitir categorias de receitas/despesas customizadas por usuário.  |
| RF06  | Metas Financeiras Mensais  | Permitir definir e editar metas mensais de economia.  |
| RF07  | Relatórios por Período  | Gerar relatórios mensais/anuais com receitas, despesas e saldo.  |
| RF08  | Gráficos e Visuais  | Mostrar gráficos (pizza, linha) com dados financeiros por período.  |
| RF09  | Exportar PDF  | Exportar relatórios mensais para PDF.  |
| RF10  | Dashboard Responsivo  | Exibir resumo financeiro em dashboard adaptado a dispositivos móveis.  |
| RF11  | Multiusuário  | Cada usuário só pode acessar seus próprios dados.  |
| RF12  | Logout  | Encerrar sessão de forma segura.  |

----------

## 📐 Regras de Negócio Associadas

| Status  | Regra |
| :-------------: | :------------- | 
| :white_check_mark:  | O saldo mensal será calculado como: saldo = receitas - despesas  |
| [	]  | Despesas não podem ter valor negativo.  |
| [	]  | Categorias essenciais não podem ser removidas, apenas ocultadas.  |
| [	]  | Relatórios exportados devem conter nome do usuário, mês/ano e saldo total.  |
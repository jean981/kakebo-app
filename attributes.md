## :bookmark_tabs: Functional Requirements

|:card_index:ID | :new: Requirement |:page_facing_up:Description |
|:-------------: | :------------- | :------------- |
| RF01  | [User Registration](diagrams/userSchema_RF01_CRUD_endpoint.md) | Allow new users to create an account with name, email and password. |
| RF02  | [Login and Authentication](diagrams/login_RF02_endpoint.md)  | Authenticate users using email and password via JWT. |
| RF03  | [Income Registration](diagrams/incomeSchema_RF03_CRUD_endpoint.md)  | Record income with date, amount, category and description.  |
| RF04  | [Expense Registration](diagrams/expenseSchema_RF04_CRUD_endpoint.md) | Record expenses with date, amount, category and description.  |
| RF05  | [Custom Categories](diagrams/categorias_RF05_endpoint.md) | Allow user-customized income/expense categories.  |
| RF06  | [Monthly Financial Goals](diagrams/metas_RF06_endpoint.md) | Allow setting and editing monthly savings goals.  |
| RF07  | [Period Reports](diagrams/relatorios_RF07_endpoint.md) | Generate monthly/annual reports with income, expenses and balance.  |
| RF08  | [Charts and Visuals](diagrams/graficos_RF08_endpoint.md)  | Display charts (pie, line) with financial data by period. |
| RF09  | [PDF Export](diagrams/exportarPDF_RF09_endpoint.md) | Export monthly reports to PDF.  |
| RF10  | [Responsive Dashboard](diagrams/dashboard_RF10_endpoint.md) | Display financial summary in a mobile-adapted dashboard. |
| RF11  | [Multi-user](diagrams/multiusuario_RF11_endpoint.md) | Each user can only access their own data.  |
| RF12  | [Logout](diagrams/logout_RF12_endpoint.md) | Securely end the session.  |
| RF13  | [Parser](diagrams/parserSchema_RF13_us_endpoint.md) | Endpoint import financial data .CSV  |
| RF14  | [Visualizing Financial Data](diagrams/dataVisualizationThymeleaf.md)|Web interface with filters, pagination, and visualization of financial data. |

##  📐  Associated Business Rules

| Status  | Rule |
| :-------------: | :------------- | 
| :white_check_mark:  | Monthly balance will be calculated as: balance = income - expenses |
| :white_check_mark:  | Expenses cannot have negative values.  |
| [	]  | Essential categories cannot be deleted, only hidden.  |
| [	]  | Exported reports must contain user name, month/year and total balance.  |

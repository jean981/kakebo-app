## :bookmark_tabs: Functional Requirements

|:card_index:ID | :new: Requirement |:page_facing_up:Description |
|:-------------: | :------------- | :------------- |
| RF01  | User Registration  | Allow new users to create an account with name, email and password. |
| RF02  | Login and Authentication  | Authenticate users using email and password via JWT. |
| RF03  | Income Registration  | Record income with date, amount, category and description.  |
| RF04  | Expense Registration | Record expenses with date, amount, category and description.  |
| RF05  | Custom Categories | Allow user-customized income/expense categories.  |
| RF06  | Monthly Financial Goals  | Allow setting and editing monthly savings goals.  |
| RF07  | Period Reports  | Generate monthly/annual reports with income, expenses and balance.  |
| RF08  | Charts and Visuals  | Display charts (pie, line) with financial data by period. |
| RF09  | PDF Export  | Export monthly reports to PDF.  |
| RF10  | Responsive Dashboard  | Display financial summary in a mobile-adapted dashboard. |
| RF11  | Multi-user  | Each user can only access their own data.  |
| RF12  | Logout  | Securely end the session.  |

##  📐  Associated Business Rules

| Status  | Rule |
| :-------------: | :------------- | 
| :white_check_mark:  | Monthly balance will be calculated as: balance = income - expenses |
| [	]  | Expenses cannot have negative values.  |
| [	]  | Essential categories cannot be deleted, only hidden.  |
| [	]  | Exported reports must contain user name, month/year and total balance.  |
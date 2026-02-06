# RF14 – Visualização e Filtros de Dados Financeiros

## 📋 Descrição
Este requisito funcional define a visualização dos dados financeiros importados,
permitindo filtros dinâmicos, paginação e navegação através de interface web baseada em Thymeleaf.

## 🎯 Objetivo
Oferecer ao usuário uma experiência clara e eficiente para análise dos dados financeiros.

## 🔽 Filtros Disponíveis
- Setor
- Tipo
- Situação
- Emitente
- Período (data inicial e final)

## 🔁 Diagrama de Interação
```mermaid
sequenceDiagram
    participant U as Usuário
    participant V as View (Thymeleaf)
    participant C as Controller
    participant S as Service
    participant R as Repository

    U->>V: Submete filtros
    V->>C: GET /efaturas
    C->>S: listarComFiltros()
    S->>R: Query dinâmica
    R-->>S: Resultado paginado
    S-->>C: Page<EFaturaView>
    C-->>V: Model + Dados
```

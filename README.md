Existing Power BI model built directly in the report layer with all transformations and business logic mixed into flat tables. Rebuilt from scratch using star schema best practices with SQL views handling all business logic.

Two flat source tables decomposed into 2 fact tables and 5 dimension tables — FactTransaction, FactPayment, DimClient, DimVendor, DimEmployee, DimCategory, DimPaymentMethod

All business rules moved into SQL views at the data layer — report layer stays clean and performant

Tabular model built and deployed in Visual Studio with named DAX measures and proper relationships

Power BI
SQL Server
Visual Studio
Tabular Model
Star Schema
DAX
SQL Views

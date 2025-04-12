# SmartElectronics_DB
# Electronics Store Database

## Disclaimer

This database is a fictional project created solely for educational and demonstration purposes. It is not associated with any real company or actual data.

## Overview

This repository contains the SQL database for an electronics store. The database is built on Microsoft SQL Server using T-SQL and is structured into several schemas that represent different functional areas. Each schema contains a set of tables that manage specific aspects of the business operations.

## Technologies

- **Database System**: Microsoft SQL Server
- **Version**: Compatible with MSSQL 2019+ (AdventureWorks2022 compatible)
- **Language**: T-SQL (Transact-SQL)

## Schemas and Tables

### HumanResources Schema
- **HumanResources.AddContact**: Stores contact information for employees.
- **HumanResources.Department**: Contains data on various departments.
- **HumanResources.Employee**: Holds employee details.
- **HumanResources.EmployeeHistory**: Records the employment history of each employee.
- **HumanResources.EmployeeSalary**: Manages salary information for employees.
- **HumanResources.JobTitles**: Lists job titles and positions.

### Customer Schema
- **Customer.Customer**: Contains primary details of customers.
- **Customer.CustomerDelivery**: Stores delivery addresses for customers.
- **Customer.CustomerPayment**: Manages customer payment information.
- **Customer.CustomerTerritory**: Defines the geographical territories for customers.

### Branch Schema
- **Branch.Branch**: Contains branch or store location details.
- **Branch.BranchLocation**: Provides detailed location data for each branch.
- **Branch.Sales**: Records sales data associated with branches.

### Finance Schema
- **Finance.BankAccount**: Stores bank account details.
- **Finance.BankCard**: Contains bank card information.
- **Finance.Currency**: Holds information about different currencies.
- **Finance.CurrencyRates**: Maintains exchange rate details for currencies.

### Inventory Schema
- **Inventory.Product**: Stores product information.
- **Inventory.ProductCategory**: Categorizes products into broader groups.
- **Inventory.ProductSubCategory**: Further categorizes products into subgroups.
- **Inventory.Warehouse**: Contains data about warehouses.

### Supplier Schema
- **Supplier.PurchesOrder**: Records purchase orders from suppliers.
- **Supplier.PurchesOrderDetail**: Contains details for each purchase order.
- **Supplier.Supplier**: Stores supplier information.
- **Supplier.SupplierDelivery**: Manages delivery details from suppliers.
- **Supplier.SupplierPayment**: Records payments made to suppliers.

### Transport Schema
- **Transport.Transport**: Contains data related to transportation and logistics.

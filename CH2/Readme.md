SQL Views

USE [AdventureWorksDW2019]
GO

SET ANSI_NULLS ON
GO

SET QUOTED_IDENTIFIER ON
GO


CREATE VIEW [BI].[vFact_ResellerSales]
AS
SELECT * FROM dbo.FactResellerSales
GO

CREATE VIEW [BI].[vFact_InternetSales]
AS
SELECT * FROM dbo.FactInternetSales
GO

CREATE VIEW [BI].[vDim_Scenario]
AS
SELECT * FROM dbo.DimScenario
GO

CREATE VIEW [BI].[vDim_SalesTerritory]
AS
SELECT * FROM dbo.DimSalesTerritory
GO

CREATE VIEW [BI].[vDim_SalesReason]
AS
SELECT * FROM dbo.DimSalesReason
GO

CREATE VIEW [BI].[vDim_Reseller]
AS
SELECT * FROM dbo.DimReseller
GO

CREATE VIEW [BI].[vDim_Promotion]
AS
SELECT * FROM dbo.DimPromotion
GO

CREATE VIEW [BI].[vDim_ProductSubcategory]
AS
SELECT * FROM dbo.DimProductSubcategory
GO

CREATE VIEW [BI].[vDim_ProductCategory]
AS
SELECT * FROM dbo.DimProductCategory
GO

CREATE VIEW [BI].[vDim_Product]
AS
SELECT * FROM dbo.DimProduct
GO

CREATE VIEW [BI].[vDim_Organization]
AS
SELECT * FROM dbo.DimOrganization
GO

CREATE VIEW [BI].[vDim_Geography]
AS
SELECT * FROM dbo.DimGeography
GO

CREATE VIEW [BI].[vDim_Employee]
AS
SELECT * FROM dbo.DimEmployee
GO

CREATE VIEW [BI].[vDim_Department]
AS
SELECT * FROM dbo.DimDepartmentGroup
GO

CREATE VIEW [BI].[vDim_Date]
AS
SELECT * FROM dbo.DimDate
GO

CREATE VIEW [BI].[vDim_Customer]
AS
SELECT * FROM dbo.DimCustomer
GO

CREATE VIEW [BI].[vDim_Currency]
AS
SELECT * FROM dbo.DimCurrency
GO

CREATE VIEW [BI].[vDim_Account]
AS
SELECT * FROM dbo.DimAccount
GO

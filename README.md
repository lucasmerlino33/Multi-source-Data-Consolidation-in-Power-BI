# Multi-source-Data-Consolidation-in-Power-BI
Engineered a multi-source data consolidation workflow in Power BI. Implemented product-specific transformations and standardized metrics to support cross-system comparative reporting. The model follows a star schema with several fact tables and multiple dimension tables.

## Problem Context

Multiple operational systems with inconsistent schemas, naming conventions, and business rules needed to be consolidated into a unified analytical model to enable cross-product performance comparison.

## Technical Challenges

- Inconsistent column structures across systems
- Different metric definitions by product line
- Missing fields in certain sources
- Varying levels of granularity
- Need for standardized reporting structure

## Modeling Strategy

- Source-level normalization using Power Query
- Product-specific transformation logic
- Standardized column mapping using SELECTCOLUMNS
- Consolidation via UNION
- Implementation of a star schema
- Centralized calendar dimension

### Star Schema Model

![Star Model](Model/01_Star_Model.png)


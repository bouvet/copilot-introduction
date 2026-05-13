# Data Model - Sales Analytics (Power BI)

This model mirrors a common star schema.

## Fact Table: Sales

| Column | Type | Description |
|---|---|---|
| OrderId | Text | Unique order line id |
| Date | Date | Order date |
| CustomerId | Text | FK to Customers |
| ProductId | Text | FK to Products |
| Quantity | Whole Number | Units sold |
| UnitPrice | Decimal | Unit sales price |
| UnitCost | Decimal | Unit cost |
| Region | Text | Sales region |

## Dimension Table: Customers

| Column | Type | Description |
|---|---|---|
| CustomerId | Text | Unique customer id |
| CustomerName | Text | Name |
| Segment | Text | Enterprise / SMB / Public |

## Dimension Table: Products

| Column | Type | Description |
|---|---|---|
| ProductId | Text | Unique product id |
| ProductName | Text | Product name |
| Category | Text | Product category |

## Relationships

- Customers[CustomerId] -> Sales[CustomerId] (1:* active)
- Products[ProductId] -> Sales[ProductId] (1:* active)

## Date assumptions

Use Sales[Date] directly for time intelligence in this exercise.

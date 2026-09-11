# Data Modeling

This section focuses on organizing data so analytical models remain understandable, scalable and reliable.

## Topics

- Fact and dimension tables
- Primary and foreign keys
- Table relationships
- Cardinality
- Star schema
- Filter direction
- Date dimensions
- Model organization

## Analytical perspective

A dashboard can look good and still produce misleading results when the model behind it is poorly designed. Data modeling defines how business entities relate and how calculations behave across the report.

```text
Dimensions → Fact Table ← Dimensions
                 ↓
             Measures
                 ↓
              Insights
```

Practical models and examples will be added progressively.

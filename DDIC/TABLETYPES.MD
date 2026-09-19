# DDIC Table Types

Custom DDIC table types used for handling internal tables in the SAP Sales Order Analytics & Exception Management project.

| Table Type         | Purpose                                                |
| ------------------ | ------------------------------------------------------ |
| `ZSO_TT`           | Handles general sales-order data.                      |
| `ZSO_VALUE_TT`     | Handles sales-order data used for high-value analysis. |
| `ZSO_OLD_TT`       | Handles data used for old-order analysis.              |
| `ZSO_TYPE_TT`      | Handles data used for sales-order type analysis.       |
| `ZSO_EXCEPTION_TT` | Handles exception data generated during the analysis.  |

These table types provide reusable internal-table definitions for processing sales-order and exception data.

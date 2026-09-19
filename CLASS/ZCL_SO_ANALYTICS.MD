# Global Class: ZCL_SO_ANALYTICS

`ZCL_SO_ANALYTICS` is the main global class used for sales-order data retrieval, analysis, and exception management.

## Methods

| Method                | Purpose                                                        |
| --------------------- | -------------------------------------------------------------- |
| `GET_SO`              | Retrieves sales-order data based on the selected criteria.     |
| `ANALYZE_HIGH_VALUE`  | Identifies sales orders exceeding the defined value threshold. |
| `ANALYZE_OLD_ORDERS`  | Identifies sales orders that meet the defined age criteria.    |
| `ANALYZE_ORDER_TYPES` | Analyzes sales orders based on their order types.              |
| `BUILD_EXCEPTIONS`    | Builds exception information from the analysis results.        |
| `DISPLAY_ALV`         | Displays the final analysis and exception results using ALV.   |

## Role in the Project

The class separates the business logic from the main program and provides reusable methods for sales-order retrieval, analysis, exception processing, and output generation.

**Main technologies:** Object-Oriented ABAP, Open SQL, Internal Tables, DDIC, and ALV (`CL_SALV_TABLE`).

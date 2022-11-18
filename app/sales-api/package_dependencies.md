# Dependency Table For: github.com/ardanlabs/service/app/sales-api

|                            | a p p / s a l e s - a p i / h a n d l e r s - G | b u s i n e s s / a u t h - G | b u s i n e s s / d a t a / p r o d u c t - G | b u s i n e s s / d a t a / u s e r - G | b u s i n e s s / m i d - G | b u s i n e s s / v a l i d a t e - G | f o u n d a t i o n / d a t a b a s e - T | f o u n d a t i o n / k e y s t o r e - T | f o u n d a t i o n / w e b - T |
|:---------------------------|:-----------------------------------------------:|:-----------------------------:|:---------------------------------------------:|:---------------------------------------:|:---------------------------:|:-------------------------------------:|:-----------------------------------------:|:-----------------------------------------:|:-------------------------------:|
| **app/sales-api**          |                      **G**                      |             **G**             |                                               |                                         |                             |                                       |                   **T**                   |                   **T**                   |                                 |
| **app/sales-api/handlers** |                                                 |             **G**             |                     **G**                     |                  **G**                  |            **G**            |                 **G**                 |                   **T**                   |                                           |              **T**              |
| **business/data/product**  |                                                 |             **G**             |                                               |                                         |                             |                 **G**                 |                   **T**                   |                                           |                                 |
| **business/data/user**     |                                                 |             **G**             |                                               |                                         |                             |                 **G**                 |                   **T**                   |                                           |                                 |
| **business/mid**           |                                                 |             **G**             |                                               |                                         |                             |                 **G**                 |                                           |                                           |              **T**              |

### Legend

* Rows - Importing packages
* Columns - Imported packages


#### Meaning Of Row And Row Header Formatting

* **Bold** - God package (can use all packages)
* `Code` - Database package (can only use tool and other database packages)
* _Italic_ - Tool package (foundational, no dependencies)
* No formatting - Standard package (can only use tool and database packages)


#### Meaning Of Letters In Table Columns

* G - God package (can use all packages)
* D - Database package (can only use tool and other database packages)
* T - Tool package (foundational, no dependencies)
* S - Standard package (can only use tool and database packages)

```mermaid
erDiagram
    BOOKING ||--|{ ROOMSERVICE : has
    BOOKING{
      
    }
    BOOKING ||--|{ RATETYPE : has
    ROOMSERVICE ||--|{ PRODUCT : offer
    BOOKING }o--|| ROOM : places
    BOOKING }o--|| Guest : has
    ROOM ||--|{ ROOMTYPE: has
    ROOM ||--|{ ROOMSTATUS: has
   
```

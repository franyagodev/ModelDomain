#supermarket 

@startuml
StoreGroup *-- Store 
Store o-- Product
Store --Stock
Stock *--Article
Store *-- ShoppingList
ShoppingList *-- ShoppingListItem
ShoppingListItem--Article
Product -- Brand
Article -- Product
Product -- ProductType
Customer *-- ShoppingList
@enduml

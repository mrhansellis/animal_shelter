DB Config for Animal Shelter

**Entity** represents a single database **table** as a C# model in our app. In animal shelter this will be Animal.cs.

**Database context** represents the entire database (all tables) as as model in our app. It is called **ProjectNameContext**. It extends the functionality of EF Core's **DbContext** class. **DBContext** represents a sessiion with our database that can be used to query *instances* of our entities (**Animal.cs**). Every time we want to refernce a database in an app we will do so using an *instance* of the **DbContext** class. 


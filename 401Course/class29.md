##Room

### Save data in a local database using Room

* Room persistence library provides an abstraction layer over SQLite to allow fluent database access while harnessing the full power of SQLite.
* Room provides the following benefits - compile-time verification of SQL queries, convenience annotations that minimize repetitive and error-prone boilerplate code, and streamlined database migration paths.
> Setup - add these depencies: dependencies { def room_version = "2.2.6"

##### Primary components:
* The database class that holds the database and serves as the main access point for the underlying connection to your app's persisted data.
* Data entities that represent tables in your app's database.
* Data access objects (DAOs) that provide methods that your app can use to query, update, insert, and delete data in the database.

### Defining data using Room entities:

Each entity corresponds to a table in Room database, and each instance of an entity represents a row of data in the corresponding table.

1. Anatomy of an entity
* Each Room entity can be defined as a class that is annotated with `@Entity`. A Room entity includes fields for each column in the corresponding table in the database, including one or more columns that comprise the primary key.
* Room uses the class name as the database table name.

2. Define a primary key
* Each Room entity must define a primary key that uniquely identifies each row in the corresponding database table. The most straightforward way of doing this is to annotate a single column with `@PrimaryKey`.

3. Ignore fields

* If an entity has fields that you don't want to persist, you can annotate them using `@Ignore`, and can use ignoredColumns for an entity inherits fields from a parent entity.

4. Provide table search support
   Room supports several types of annotations that make it easier for you to search for details in your database's tables.


### Define relationships between objects:

> SQLite is a relational database, so you can specify relationships between entities.

**Create embedded objects**

`@Embedded` annotation - represents an object that you'd like to decompose into its subfields within a table.

* One-to-one relationship - between two entities is a relationship where each instance of the parent entity corresponds to exactly one instance of the child entity.

* One-to-many relationship between two entities is a relationship where each instance of the parent entity corresponds to zero or more instances of the child entity, but each instance of the child entity can only correspond to exactly one instance of the parent entity.

* Many-to-many relationship between two entities is a relationship where each instance of the parent entity corresponds to zero or more instances of the child entity, and vice-versa.

* Nested relationships - if you might need to query a set of three or more tables that are all related to each other.

### Accessing data using Room DAOs:

* Data access objects(DOA) - Each DAO includes methods that offer abstract access to your app's database.
* Can define each DAO as either an interface or an abstract class.
* Annotate your DAOs with `@Dao`

* Query methods - that let you write your own SQL query to interact with the database.
* `@Insert` annotation - allows you to define methods that insert their parameters into a table in the database.
* `@Update` annotation - allows you to define methods that update specific rows in a database table.
* `@Delete` annotation - allows you to define methods that delete specific rows from a database table.
* `@Query` annotation - allows you to write SQL statements and expose them as DAO methods.

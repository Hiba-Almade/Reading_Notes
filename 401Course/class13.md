## Related Resources and Integration Testing

### One-to-One Relationship
define two entity classes having a one-to-one relationship,
using the @OneToOne annotation to defind relation

The association name defaults to the property name and can be customized using the rel attribute of @RestResource annotation:

In order to expose these entities as resources,we need to create two repository interfaces for each of them, by extending the CrudRepository interface

Sending get request to an endpoint would return an empty object if no post requests was sent.
We use the PUT method to retrieve the JSON object or Delete to delete a record.


### One-to-Many RelationShip

A one-to-many relationship is defined using the @OneToMany and @ManyToOne annotations and can have the optional @RestResource annotation to customize the association resource.

to Expose it we need the same repository interface that extends CRUDRepository.

Use the PUT request to associate the repository with the association.


### Many-to-Many Relationship

A many-to-many relationship is defined using @ManyToMany annotation, to which we can add @RestResource.

we need to create a repository interface to manage the entity.

we need to sending a POST requests to the collection resource.

we can send a GET request to the association endpoint to verify both entity have been associated.


---------

### Testing the Endpoints With TestRestTemplate


Define a class that injects a TestRestTemplate.

Define the endpoints as strings.

Declare @Test method to start testing.

Make an object for each class you want to test the relation on.

Use postEntity to the specific objects.

use the HttpHeaders to add the headers of the request.

assertEquals the response for each.

Integration Testing in Spring

Preparation




# Class Notes 12

## Baeldung: Comparing repositories

- Every repositoty in Spring Data extends the generic Repositiory interface, They all have different functionality though.
- The CrudRepository provides CRUD functions.
- PagingAndSortingRepository provides methods to sort records and to do pagination.
- JPARepository is able to provide methods like flushing the persistance context and delete records in a batch.
- CRUD functionality includes these functions: save(), findOne(), findAll(), count(), delete(), and exists().
- JPARepository functionality includes: findAll(), save(), flush(), saveAndFlush(), and deleteInBatch().
- Some downsides to using spring repository are the posibility of exposing internal implementation details and the possibility of not having the amount of control we want.

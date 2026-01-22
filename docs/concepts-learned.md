@ElementCollection

- Useful when you need to associate a collection of values with an entity without the need for a separate entity table.
- Example : List<String> amenities , List<String> photos , List<Address> addresses etc .
- Jpa creates a separate table to store the collection.

Story 1: In order to track wildlife sightings, as a user of the API, I need to manage animals.

Branch: animal-crud-actions ✅

Acceptance Criteria

Create a resource for animal with the following information: common name and scientific binomial ✅

in console i see this:
3.2.0 :001 > Animal.all
  Animal Load (0.8ms)  SELECT "animals".* FROM "animals"
 => [] ✅
 Animal common_name:string scientific_binomial:string


Can see the data response of all the animals ✅

Can create a new animal in the database ✅

Can update an existing animal in the database ✅

Can remove an animal entry in the database ✅


Animal.create(common_name:" ", scientific_binomial:" ")
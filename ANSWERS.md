## Questions

1. What is the difference between `new` and `create` for a model?

The new instantiates an object without it being saved, while the create method will create and save a new record of the object into the database.

2. What command followed after with `Cat.new` will emulate the same behavior as `Cat.create`?
Cat.save will do the same.

3. What is the default integer column that exists on every table but we did NOT define?
This is the ID column


4. What single line of ruby code can insert a cat with the name "Kira" in the database?
c= Cat.create(name: "Kira")

5. How did you like this homework in comparison with the previous homeworks?
This one was a lot longer and harder than the others.

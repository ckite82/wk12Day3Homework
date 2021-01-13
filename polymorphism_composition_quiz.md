# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Answer - polymorphism is something that can take many different forms 

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

Answer - is when you can take many different classes which are similar and link them through inheritance.  A dog, cat, duck, are all different animals, but they similar attributes. 

3. What can we use to implement polymorphism in Java?

Answer - you can use method overloading to implement polymorphism in Java, so you can call the same method in a class but apply different parameters to obtain different results.

4. How many 'forms' can an object take when using polymorphism?

Answer - Endless forms, but convention would suggest to keep it to 3-4 levels of polymorphism, otherwise the code could become conveluted.

5. Give an example of when you could use polymorphism.

Answer - Using the same example above dog, cat and duck are all animals that are able to make a noise, you could use the same canSpeak method on each, but pass in a different animal each time and you will get three different results "bark", "meow", "quack"


# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Answer - composition in OOP is a way for relational classes to form a has-a relationship.

7. When would you use composition? Provide a simple example in Java.

Answer - A car is a vehicle, and has-a set of doors.

8. What is/are the advantage(s) of using composition?

Answer - it allows you to re-use methods without having to re-write them, so therefore keeps your code clean, easy to read and DRY. 

9. When an object is destroyed, what happens to all the objects it is composed of?

Answer - if an object is destroyed, the objects that it takes inheritance from would be isolated at that level and protected from any similar destruction / errors.

Hello everyone my name is Arthur.
Today we talk about javascript classes and inheritance in java script.
Let's see what it is let's look at a couple of examples.
Let's get down to collecting our topic today.

The first thing we touch on is the concept of classes in javascript.
A class is a scheme on the basis of which we can create objects.
In the same time an object is an independent unit that has properties and a specific type. The object is a real representation of our scheme,that is, for one class we can create several objects.

 What is an object in javascript is a modifiable collection of properties, that is, we can add or delete our properties at any stage.
 The object includes the key and value, that is, the object has some keys, these are the properties of our object and there is a value
corresponding to each key in the object. You also need to understand if the order of your values is important to you, then the object is not the best.
The key is always unique, specifically in the scope of this object, it is always a string, everything that you pass as a key, everything will be converted to a string. 
The value can be different, primitive object or function.
And you should know that in fact everything in javascript is an object, all that we work with is an object


And so, we will continue the classes in ec2015. Compared to previous classes, we can actually call them classes, because the keyword "class" has appeared.
And so we'll see, we have the keyword class and then how can we declare things common to all instances. Here the constructor is not required, it may not be,
to declare the method we write "say" and  inside curly brackets we do its implementation, inside each method there will be "this" and it will refer to our instance.
And we can still create objects of our class, we still use the keyword "New", call our class as a function, pass some objects, and so on.

There are some features that classes cannot be called as functions, the class call should be with the word "new." If you try to call a class, you will get an error type. 
There cannot be more than one constructor in a class; if you try to call, you will get a syntax error.
In the classes, setters and getters have appeared, we can now announce them, these are some kind of properet, to which we can write some restriction on access, or, on the contrary, extend it.
We will create a class "people" for all instances of this class will have a "new age", every time when we try to write something into this property, we will call this one function here.
And by analogy with a setter, there is a getter it will be a property, it is not a function, this property that cannot be assigned, but it can be read.

And here we have an example, we create an instance of this class, when we call "arthur. Represcent",
we see the default value that was assigned, then we call our setter,and the second time we call the repress we will see our age.
Thanks to these getters, we can make our code more beautiful.

So, TYPEOF.there is a construction that allows us to understand what type of instasas are, this is a typoff, this is what it looks like, in fact, this is an operator to which we pass an argument, 
and it returns to us with a string like our instance.
The type of numbers will be dialing, the strings will be string, the functions will be typing, it will be like, there will be a function,Type of true will be a boolean, and the object type is an object.
There are of course a few nuances, so you can see them here, there are not so many of them, you have probably already encountered many of them.
There is also such another way as an instance, but I will not dwell on it.


Let's continue and talk about inheritance. There are classical inheritance that exist in programming languages such as Java, C ++.
In classical inheritance, we always inherit classes from classes, this is important, and we create a hierarchy of subclasses using the parent and child class.
And there is a prototype inheritance just, it concerns us and javascript, the prototype is a working object of our instas and the object is inherited from another object.
In classical inheritance, classes are inherited from classes, in prototype inheritance, objects are inherited from objects.


Let's start ec2015.here the keyword "extentd".we are announcing a class here, peopleMan, we say that our peopleMan will be inherited, people will expand the class People.
Then we create a constructor, the word "super" appears inside, in fact, "super" is a reference to People.
We still add some methods with some kind of logic that do something.
And here we create a new people, and when we call ivanov.say, the first line is what we see in the first console.log, then we went to the "say" method of the parent,
and at the end finished with the second console.log.
Using "super" we have access to the base method of our class.


advanteges of classes
Help to organize data relationships.If you take your model and transfer it to OOP, then using classes you can create an interaction between these structures, data, and this makes it easier to understand your code.
Extensibility. classes can always be inherited, hence expanded, if you need to add claas to a new project, or an existing one, then it will not be difficult for you.
Help to define data structures.Yes, classes allow us to define the data structure, if you have a complicated domain, then it is best to create right away claas who will work with it and move on.

MINUSES OF CLASSES
Not flexible. Classes allow you to shove your data into your world, they are there trying to leave them, they have strict objects and everything is difficult somehow.
A lot of time designing the code. Yes, if you write with classes, you will need more time, at least to design your class hierarchy
May destroy "transparency" of logic.Yes, because when you look at a class, the logic of the class for which it is responsible may be lost due to inheritance


Here you can view the material that I studied, and study more in depth. At this I have everything, thank you for your attention.

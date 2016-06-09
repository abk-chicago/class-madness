# Class Madness

ARE YOU READY TO MAKE MOAR CLASSES?! [classes, android 101]

>> **Recommendation**: Create two projects at once so you practice each set of skills back to back. This will help you memorize the steps you need to take for future use.

## Let's Practice Making Classes

- You will create two Android projects for this exercise. One will be called `Haunted House` and the other will be `Paradise`.
- For each of these projects, you will create a Java class (`HauntedHouse` and `ParadiseLocale`). 
- Each class must have **4+** member variables declared as private (`mMyVar`).
- Each class must have **two** constructors: 
  - one that accepts **0** arguments (such as `new HauntedHouse()`)
  - one that accepts **5** arguments (such as `new ParadiseLocal(String name, Double lat, ...)`)
  - Both constructors must set values to the member variables of your class.
- Create **Getters** and *Setters** for at least _two_ member variables in each class.
  
## Let's Put our classes to use in an Activity!

>> **Test line by line**... _always debug_

- Now that you've created your classes, it is time to include it in your activity after `setContentView`.
- Add a `TextView` and a `Button` to your layouts for both applications. Make sure to give them `id`s.
- Inside of your `MainActivity` classes, create member variables or them.
- In your `onCreate` method, assign  values for your TextView and Button member variables using casting and `findViewById()`
- Create an `OnClickListener` using  `new View.OnClickListener() { ... /* override etc */ }`
- Assign the OnClickListener to your Buttons.
- Create a new private member variable for your MainActivity: one for each class in each corresponding project (`HauntedHouse mHauntedHouse;`
- Inside of `onCreate`, instantiate a new copy of your class using the constructor of your choice by assigning the `new` instance to your member variable (`mHauntedHouse`).
- Inside the OnCLickListener, `setText()` on your TextView member variable to display data from your class.

# Design Patterns Implementation (Bridge, Builder, Adapter)

In this project, I selected three design patterns after reading the full instructions. These patterns are Bridge, Builder, and Adapter. I tried to understand each pattern and then created simple examples using HTML, CSS, and JavaScript.

---

# 1. Bridge Pattern

In my Bridge pattern example, I used shapes like Circle and Square. These shapes are connected with different properties like color and size.

The main idea of Bridge pattern is to separate things so they can change independently. For example, shape and color are separate. If I change color, shape will not break.

So basically:
- Shape = abstraction  
- Color/size = implementation  

This makes the code more flexible and easy to manage.

# Why I used it
I used this pattern to show how we can connect two different parts without mixing them.

# Good things
- Easy to change one part without affecting others  
- Code looks cleaner  
- More flexible  

# Problems
- Code becomes little complex  
- Hard for beginners to understand  

---

# 2. Builder Pattern

In Builder pattern, I created example of Pizza and Burger using buttons.

When user clicks button:
- "Create Pizza" → pizza object is created  
- "Create Burger" → burger object is created  

Here, same process is used to create different objects.

The main idea is:
We build objects step by step instead of writing everything in one place.

# Why I used it
Because some objects are complex and have many parts, so builder makes it easy.

# Good things
- Easy to create complex objects  
- Code is more readable  
- Same process can create different results  

# Problems
- More code required  
- Not useful for simple objects  

---

# 3. Adapter Pattern

In Adapter pattern, I created a drawing app where user selects shape from dropdown (like Circle).

Different shapes may have different drawing methods, but adapter makes them work in same way.

So adapter acts like a middle person.

Example:
Old system → different format  
New system → different format  
Adapter → connects both  

# Why I used it
To show how different objects can work together even if they are not compatible.

# Good things
- Reuse old code  
- Connect different systems  
- Makes code organized  

# Problems
- Extra layer added  
- Can increase complexity  

---

# Final Thoughts

After doing this project, I understood that design patterns are not full programs but they help in writing better code.

At first it was confusing, but after making small examples, it became easier to understand.

I feel these patterns are useful in real projects, especially when code becomes big and complex.
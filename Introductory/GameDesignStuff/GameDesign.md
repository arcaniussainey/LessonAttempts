# A note

Please notify me of any errors, difficult to read or understand, or unclear segments of this writing at waltba04@pfw.edu. Written with love, and an abundance of newness, is my take at an introduction 

\- B. W

## What is Game Design? 
Described in a way I feel both simple and somewhat poetic, game design (or game development) is the interdisciplinary art of bringing artificial worlds to life. Much like a Game Manager for board games and TTRPGs, Game Designers seek to immerse their players in a world, and provide an experience for their players to enjoy. 

<div style="page-break-after: always;"></div>

More technically speaking, game designers work to convert abstract games, to real world technologies. If you’ve ever heard of games such as Dungeons and Dragons, Starfinder, Chess, Uno, or almost any other game, you’ve *likely* seen the poetic role of a game designer. Those games boast enjoyable experiences – experiences which consist of rules, a playing field, and interactions between the game and the player. 

Take the Dungeon Master of a game such as Dungeons and Dragons for instance. They create a world in concept, and fill it with details big and small: they create characters, places, scenarios, events, cultures, and fun little quirks for their world. They simulate the actions and behaviors of Non-Playable Characters for the players to interact with. They describe the things players see, and try to immerse players in a world that is both real and alive. They handle the rules of the game, making sure they’re properly communicated, and that they’re actually enforced. 

The DM (Dungeon Master) in this instance is maintaining a game, but the game is abstract. The game exists and runs and continues *only* with someone (our DM) helping to manifest it. They have to keep track of the details, and ensure the fulfillment of all aspects in the game. 

With our above definition then, we can say that a Game Developer, or GD, seeks to convert the abstract game into a real game. A game that contains within itself the content that it needs to run, and performs all the roles necessary to maintain the game, leaving only a role for a player’s input. You might argue that the game still isn’t “real” as it’s on a computer, but you must remember that everything the game keeps track of still exists within the computer. It’s real, it’s just a real *representation* rather than a real actualization of the game and its contents into our world. It just so happens that computers are extremely good at following specified instructions and repeating computations, unlike a human. 

To make all this happen, a Game Developer needs to construct and convey the rules of the game to a computer. This is what programming is actually about, and is what becomes the bread and butter of some of the coolest parts of game development. Programming is about designing instructions that a computer can run. That’s all. 

But conveying every aspect of a game is, in honesty, tiresome. Consider again, our Dungeon Master. A DM has many things they have to handle, and there are some things which are simply too lengthy or complex to easily convey completely. If a DM spent their time describing the number of trees in every valley, and the hairs on every NPC, and the color of every person’s clothing, they would never be able to get to actually running their game. To help manage this, a DM has two options: Either they make everything they have to manage simpler skipping over all of the smaller details, or they make use of tools to assist them. The latter approach is why a DM has references in the form of published worlds, rules, and stories, assets in the form of minifigs and pictures to represent characters and items, and tools for generating and deciding outcomes such as dice and tables. 

As people who are trying to convert this abstract game into a real one, Game Developers run into the same issues as a DM. It’s completely possible to design the rules for drawing characters onto the screen, and the rules for how the computer processes every “frame” or instant of the game, and the rules for how the computer should interact with the hardware, and how to scale and resize the window, and so on. However, as it’s tedious, taking this approach, depending on the depth, will often make the game harder and harder to complete. 

Instead, there are tools for the development of games, which aim to make this easier, much the same as a DM might be given. Tools such as Unity, Godot, and Unreal Engine are all tools known as “Game Engines”. They are programs and development spaces that have been designed for Game Developers, by Game Developers, and contain much of the needed functionality. This allows a Game Developer to just setup some settings, and begin writing the parts of the program they actually care about. 

And, once again like a DM, a Game Developer could work to convey every rule and detail of the characters and models in their world, stating the placement of the pixels, or the shape of the 3D model. However, a Game Developer could alternatively use an aspect of many Game Engines for what are called assets. Assets are just things like textures, images, 3D models, shapes, and so on, that can be developed in other specialized programs or software, and then imported into the Game Engine for use. 

To run over that, we have a few things introduced:
+ Game Developer – People who make game rules and ideas real
+ Programming – conveying the rules and functionality of a game to a computer
+ Game Engine – Toolkit to make game development easier
+ Assets – Objects and files made for use in a Game Engine. 

These things are the real focus of game design. 

When designing a game with a Game Engine, a Game Developer can work with many concepts related to game design – such as player characters, assets, worlds, levels, game menus, and more – being a given. They are simply there and usable. This is the benefit of a Game Engine, and throughout this writing (or series of writings, if needed) these same benefits will be assumed. 

## Programming 
### READ THE DOCS!!!!!!!
Programming is the art of communicating instructions to a computer. Upon receiving them, the computer will follow those instructions, regardless of whether they are well thought out, or well designed, or even doable. Additionally, since programming deals with communicating instructions in *computer programming languages* rather than in *English* it can be easy to make mistakes, and not notice them. 

It’s with these details in mind that I preface this by saying: don’t expect to perfectly remember or understand all details of programming or your Game Engine just by learning about them. 

Developing a good sense on what a program should look like requires reasonable programming experience and knowledge of the language (and its conventions), and developing a natural feel for navigating around any tool set (especially those as large as a Game Engine) requires years of hands on experience and wondering what in tarnation is going on. 

Instead of expecting to immediately and exactly understand or know something, look up the documentation for it. This is one of the most critical and important abilities a programmer, or technical fellow in general, can have. Be able to accept when you don’t or might not know something, and know how to figure it out. 

For programming languages and game engines, these are tools designed to be used, and are constantly updated. For that reason, they have expansive documentation, across multiple sources (including the creators of the content). 
+ [C# Docs](https://learn.microsoft.com/en-us/dotnet/csharp/)
+ [C++](https://devdocs.io/cpp/)
+ [Unity](https://docs.unity.com/)
+ [Godot](https://docs.godotengine.org/en/stable/index.html)
+ [Unreal Engine](https://docs.unrealengine.com/5.1/en-US/)

Do not be afraid to reference the documentation, do not be afraid to experiment with examples and ideas from the documentation. It is your friend, and even years into programming I will pull up a quick reference or some old code to know what I’m talking about. Of course, *you’re* here largely to pickup concepts and ideas that will let you more easily understand the documentation and presentations you see.

## Introduction
I will introduce basic programming concepts, and lead relatively slowly into examples. The examples I give will start off relying on english style psuedo-code (pretend code) alongside explanations in common terminology. This simply means you’ll be reading sentences that I’m telling you a computer will interpret, and I will explain why its written like that. 

Alongside those examples, and more heavily the deeper into this topic we dive, I will provide psuedo-code in the style of actual programming languages. I will focus most heavily on C#-like psuedo-code, simply because it’s commonly used in introductory game design teaching. 

In all of my examples, I have decided I will include a “given” section. A benefit, or several benefits, which we assume to be provided by the Game Engine. I will also attempt to provide example problems at the end of each section, to be solved using psuedo-code and the “given” section assigned to that problem. I believe this will increase your ability to use the benefits of a Game Engine effectively, as well as evaluate the benefits a Game Engine provides to decide if it matches a game-idea you might have in mind. I’ll say that, if possible, you should have a friend read and evaluate any psuedo-code you write the way that a computer would, exactly as stated and step by step. 

#### Simple Programming 

Simple Programming is just writing things that we want to have happen. Let’s practice some simple things with a simple Game Engine we’ll call *FizzFlark*

*FizzFlark Givens*

| Feature| How|
|--- | --- |
|Ability to detect input| Mouse input, Keyboard Input|
|Ability to display images | Displays images, with top left corner of image at given coordinates. Coordinates must be whole numbers. Update, Start, Close. |
|Named Callbacks| OnUpdate, OnStart, OnClose| 

The *FizzFlark* Game Engine is pretty simple. It consists of just a couple features, and is relatively bare. It features an awesome programming language called *FlarkSpeak* that exactly resembles the English language to the level of common interpretation. 
Let’s write a simple program in *FlarkSpeak*. We just want to display some basic words. 
```
Print to the screen “Hello World”
```
We can see an extremely simple program written on line one of our workspace. All that it does is ask the *FizzFlark* game engine to output the words “Hello World” to the screen, in whatever default manner it does so. 
It’s common to make a Hello World program as your first program in any language, both to test everything is working, and as a simple start. Luckily for us, this simple program serves as a relatively cheap introduction to a concept that pervades much of programming with or without the conscious consideration of programmers. That concept is the **data type**. 

A **data type** is as it sounds, a type for some piece of data. What that actually means though, is that it’s instructions for how the computer should package and handle that piece of data. In the above example, our data type is called the *string*, which is a list of characters. We told the computer the data type by putting quotation marks around the characters we wanted to be included. Thus, our data is “Hello World”, and we tell the computer that we want it to perform the action of [printing to the screen] on the data of [“Hello World”]. 
Data types are important because managing them makes sure everything is communicated correctly. When the computer represents data, it does so using numbers, or counts. This works perfectly fine, but it means all data stored on a computer is actually the same thing. Consider the number 90 for example. 
Now, if a computer represents all data with the same set of values, in order to treat that data differently, it must be told how to treat that data. Thus, if it’s told that a piece of data is a character, it will map that representation to a corresponding symbol, while if that piece of data is a number it will just treat it purely as a number. 
The data type also tells the computer the size of the data, or how much space it takes up. This is important because the data takes up physical space in the computers memory. The computer must know how many pieces of that memory to actually read. Combining the size and way to interpret it, the data type determines how you can use the data stored. 
Computer science contains many common data types, which I will quickly explain below, but many languages have their own lists which can be expanded or shortened from what I provide. 
- Byte – A data type representing the smallest unit of memory, a byte. It is treated as a number. A byte can represent 256 possible values. 
- Character or Char – A data type representing a keyboard character, a byte in size. There are only a couple hundred keyboard characters that actually fit in the char category, and things like special language symbols and emojis are often specially encoded combinations of characters. Examples include ‘A’, ‘3’, ‘?’, and so on. 
- String -  A data type representing a list of chars (characters). You can visualize this as a sentence, where the space is viewed as a character equivalent to any other. It’s size is dependent on how many characters it has. 
- Integer or int – A data type for numbers. It is 4 bytes in size, and ranges in values from -2,147,483,648 to 2,147,483,647. It cannot represent decimal numbers. 
- Long – A data type for numbers. Depending on implementation, it is either 4 or 8 bytes in size. If 4 bytes, it is equivalent to an int. Otherwise, it ranges values from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807. 
- Float – A data type for numbers with decimal parts. It is 4 bytes in size, and ranges in values from 1.175494351 E – 38 to 3.402823466 E + 38. The values it can represent are approximations of the decimals. 
- Double – A data type for numbers with decimal parts. It is 8 bytes in size, and ranges in values from 2.2250738585072014 E - 308 to 1.7976931348623158 E + 308. It also uses approximations. 
- Boolean or bool – A data type for the values of true and false. They either are or aren’t true. False is generally represented as a 0, and any other value is considered to be true. 
- Data types can also be what we call “unsigned” meaning that they lack the ability to be negative. To know their max and min value, simply add the negative range of values to the positive, and the range of values becomes 0 to whatever number the sum is. 
You don’t exactly need to memorize the data types and their ranges in detail. You *do* need to understand the basic idea that they represent different things, and different scales. It’s also important to know that the data types are instructions for the interpretations of the actual data. This means the actual data being represented isn’t always the same as the representation. The character ‘3’ is different from the number 3. The number 3 is simply the value 3, while the character ‘3’ is a value that the computer knows to correspond to the symbol ‘3’. To work with this, you need to convert a data type to be the same as another type *before* doing whatever you want. Many programming languages require you to do this explicitly, and there are a number of ways which we will discuss later. 

With the programming languages that we’ll be working with, typically you’re required to tell the computer the data type instead of making it guess. In FlarkSpeak you can include the data type, and we will to build a good habit. In our previous program, we told the computer the data type by using the quotation marks. 
Let’s do the same thing with what we call a **variable**. 

```
The String message = “Hello World” 
Print to the screen (message)
```

A **variable** is a name assigned to a piece of data. In this case, we assigned the string “Hello World” to the name (message). *FlarkSpeak* uses the parenthesis to indicate that something is a variable, for readability. Another cool thing about *FlarkSpeak* is that when we add a variable onto a string, it converts that variable to a string. So, we could also do something like the following. 

```
The int num1 = 30 
The int num2 = 2
Print to the screen “The operation is multiplication: ” + (num1) * (num2)
Print to the screen “The operation is addition: ” + (num1) + (num2)
Print to the screen “The operation is subtraction: ” + (num1) – (num2)
Print to the screen “The operation is division: ” + (num1) / (num2)
```
And we can redefine variables as well, so after doing this we could add something more interesting. 
```
The int num1 = 30 
The int num2 = 2
Print to the screen “The operation is multiplication: ” + (num1) * (num2)
Print to the screen “The operation is addition: ” + (num1) + (num2)
Print to the screen “The operation is subtraction: ” + (num1) – (num2)
Print to the screen “The operation is division: ” + (num1) / (num2)
Make num1 = 10
Print to the screen “The operation is addition: ” + (num1) + (num2)
```

Admittedly, this is some fun. However, in honesty, doing anything of use is difficult with such simple structures, and even if we could, writing everything would be tedious. Luckily for you, programming languages have solutions for both of these issues. Most programming langauges have multiple ways of including different behavioral patterns known as control structures, which allow us to develop more useful programs. The basic control structures are loops and conditionals:
- Loops - Control structures dedicated to repeating the same instructions, often on a condition being true. 
- Conditional Operation - Control structures that allow your program to make decisions by checking values. 
  
Programming languages also tend to include ways of packing operations and information under a name, similar to variables. The main ways to do this are functions and objects/structures:
- Functions/Methods - Names assigned to a series of operations, allowing us to call them repeatedly
- Objects/Structures - packages of data and functions, which we can create and store inside of a variable. 

To understand all of these we will consider each somewhat individually, in the following order:
- Functions/Methods
- Loops
- Conditional Operation
- Objects/Structures

If you're reading other learning material alongside this, you may think that I've swapped the order of the loops and conditionals from what is common in other guides. You would be correct, and this relates to a fundamental operation of most video games. 

#### Functions/Methods 

Let's imagine a Dungeon Master who has something that they need to do every game session, maybe even multiple times a session. Say, creating a bunch of generic NPCs. Doing that task a few times is relatively manaegable, especially for a DM who has been at this for a long time, but beyond that it becomes pretty tedious to do. Once a DM has a task that they know they need to complete multiple times, they tend to use a table of values and a dice roll, or perhaps a random generator app, to do the task instead. 

In the same way, as Game Developers we don't want to rewrite the same code repeatedly. It's tedious, it's annoying, and it introduces more room for errors. To solve this problem, most programming langauges include what are called functions. 

A function (sometimes called a method) is a name given to some actions we want to perform. Let's make an example in *FlarkSpeak*. First, let's decide what we need to do. 

```
Print to the screen "This is a cool message"
Print to the screen "So is this"
Print to the screen "And this"
```

We want to print those three messages to the screen, but every time we do so we want to erase them, and show an image on the screen. Instead of writing those three lines every time, we'll create a function. To create a function, we need to tell the computer what name our function will go by, what its **scope** is, and its **return type**. 

The **scope** of a function is the area that belongs to it, or the things it considers. Imagine an app or loot table for a DM. They might depend on certain values or rolls from the DM, but all of their operations and functionality are isolated from and independent of the rest of the game that is being played. The only thing a DM or player might care about is what gets returned from it. 

This brings us to the **return type** of a function. The return type is simply the data type that the function is expected to return when it's done. If it returns nothing, typically you specify the type as **void**: lacking in value. 

The function we are creating doesn't return anything, and is thus void in type. In this case, *FlarkSpeak* specifies scope with indentation. Sequential lines on the same level of indentation share a scope. To use a function, we "call" it, or invoke its functionality. To call a function, we just append parenthesis to the end, so for a function "foobuzz" we would say

> foobuzz()

In order to call it. 

Let's write our program out. 

```
A void function called Messages()
    Print to the screen "This is a cool message"
    Print to the screen "So is this"
    Print to the screen "And this"

Messages()
Clear the Screen
Draw the image (cool_cat_image)
Messages()
Clear the Screen
Draw the image (cool_dog_image)
Messages()
Clear the Screen
Draw the image (cool_mouse_image)
Messages()
Clear the Screen
Draw the image (cool_zebra_image)
Messages()
Clear the Screen
Draw the image (cool_horse_image)

```

This program is equivalent to the following program. 

```
Print to the screen "This is a cool message"
Print to the screen "So is this"
Print to the screen "And this"
Clear the Screen
Draw the image (cool_cat_image)
Print to the screen "This is a cool message"
Print to the screen "So is this"
Print to the screen "And this"
Clear the Screen
Draw the image (cool_dog_image)
Print to the screen "This is a cool message"
Print to the screen "So is this"
Print to the screen "And this"
Clear the Screen
Draw the image (cool_mouse_image)
Print to the screen "This is a cool message"
Print to the screen "So is this"
Print to the screen "And this"
Clear the Screen
Draw the image (cool_zebra_image)
Print to the screen "This is a cool message"
Print to the screen "So is this"
Print to the screen "And this"
Clear the Screen
Draw the image (cool_horse_image)

```

It's apparent that it became a bit shorter, and a bit more readable, but this could be improved still. There's a bit of code repitition in the above section. We could use another function, but how do we specify the image? 

Luckily for us, programming has again saved the day. Functions typically have the ability to accept, as inputs, variables. You define what variables the function will accept inside the function, and the function gains a slot for that value. When you call the function, you make sure to fill any slots in-between the parenthesis. 

In *FlarkSpeak* there's a special data type called the image-datatype, which stores the info to access images. That is the data type the Draw function accepts, so that is what we will use. 

```
A void function called Messages()
    Print to the screen "This is a cool message"
    Print to the screen "So is this"
    Print to the screen "And this"

A void function called ClearDraw(image-datatype imageVar)
    Clear the Screen 
    Draw the image (imageVar)

Messages()
ClearDraw(cool_cat_image)
Messages()
ClearDraw(cool_dog_image)
Messages()
ClearDraw(cool_mouse_image)
Messages()
ClearDraw(cool_zebra_image)
Messages()
ClearDraw(cool_horse_image)

```

Now that looks much better. It's more condensed, it's quicker to read, and it's less likely to have errors. Let's work to clean it up a bit. To do that, we should do things that make it easier to read and parse. 

One way to do this is to add comments to your code. Comments are little notes and messages left in a program, that the program will completely ignore. They exist for the people writing the programs to read later. 

In *FlarkSpeak* comments are indicated using either double slashes, "//", or asterix-slashes, "/\*" and "\*/". 

Double slashes indicate a single line commend, while asterix-slashes indicate a multiline comment. 

```c
A void function called Messages()
    // This function will print our messages to the screen
    Print to the screen "This is a cool message"
    Print to the screen "So is this"
    Print to the screen "And this"

A void function called ClearDraw(image-datatype image_var)
    // This function will clear the screen, and draw the input image. 
    Clear the Screen 
    Draw the image (image_var)

/* The below code will print out five different images 
    1. Cat image
    2. Dog image
    3. Mouse image
    4. Zebra image
    5. Horse image
    */
Messages()
ClearDraw(cool_cat_image)

Messages()
ClearDraw(cool_dog_image)

Messages()
ClearDraw(cool_mouse_image)

Messages()
ClearDraw(cool_zebra_image)

Messages()
ClearDraw(cool_horse_image)

```

You'll notice that I both added comments and spaced the lines of the program a bit (I also added color coding ;) ). Both of these serve to increase the general readability of the program, and have no ill effect on its running. 

One important thing to note when using comments is to avoid *over*commenting everything. Consider, for instance, the following example. 

```c
A void function called Messages()
    // This function will print our messages to the screen
    Print to the screen "This is a cool message"
    // The cool message
    Print to the screen "So is this"
    // Additional message
    Print to the screen "And this"
    // final message

A void function called ClearDraw(image-datatype image_var)
    // This function will clear the screen, and draw the input image. 
    Clear the Screen 
    // clearing the screen
    Draw the image (image_var)
    // Drawing the image

/* The below code will print out five different images 
    1. Cat image
    2. Dog image
    3. Mouse image
    4. Zebra image
    5. Horse image
    */
Messages() // calls the messages function
ClearDraw(cool_cat_image) // calls cleardraw
// Our first image
Messages()
ClearDraw(cool_dog_image)
// Our second image
Messages()
ClearDraw(cool_mouse_image)
// Our third image
Messages()
ClearDraw(cool_zebra_image)
// Our fourth image
Messages()
ClearDraw(cool_horse_image)
// Our fifth image

```
Or perhaps 
```c
// create a void function
A void function called Messages()
    // This function will print our messages to the screen
    Print to the screen "This is a cool message"
    // The cool message
    Print to the screen "So is this"
    // Additional message
    Print to the screen "And this"
    // final message

// create a void function
A void function called ClearDraw(image-datatype image_var)
    // This function will clear the screen, and draw the input image. 
    Clear the Screen 
    // clearing the screen
    Draw the image (image_var)
    // Drawing the image

/* The below code will print out five different images 
    1. Cat image
    2. Dog image
    3. Mouse image
    4. Zebra image
    5. Horse image
    */

// Message and image printing
Messages() // calls the messages function
ClearDraw(cool_cat_image) // calls cleardraw
// Our first image, the cat
Messages()
ClearDraw(cool_dog_image)
// Our second image, the dog
Messages()
ClearDraw(cool_mouse_image)
// Our third image, the mouse
Messages()
ClearDraw(cool_zebra_image)
// Our fourth image, the zebra
Messages()
ClearDraw(cool_horse_image)
// Our fifth image, the horse

```

This is a personal opinion of mine, but the previous example allowed the code to speak for itself. The functionality was relatively obvious just because we chose good names, and gave things good space. The comments we left were more like primers someone could quickly glance at to check their knowledge of the following section. The latter examples assumes some inability to read any of the code. There is a ratio of code to comments, and the healthy ratio changes depending on the code, and the readers. Often, if code you write suffers from a genuine need for overcommenting like this, it means you need to make sure you're following good coding practices more closely. Some examples inlude:
- Choose good names, ie "PrintMessage" instead of "Function1", or "player_character" instead of "Object_P". This makes use and functionality clear and obvious. 
- Follow a convention for styling and naming, and be consistent. This allows you to tell what something is, and navigate around it, easily and at a glance. For instance, in the above example we use
    - CamelCase (every new word starts capitalized) for functions. 
    - lower_snake_case (all lowercase, with underscores between words) for variables.
    - A newline after every function. 
- Commenting where and when it's needed. Some code will need commenting on the level of documentation, either because it's complex, or handles many many things. Other code will be so readable that you only need a few lines of comments to serve as reminders. Use your discretion to decide between these. 
- Choosing readability over "short" or "cool" code. For instance, these two do the same thing
- Be on the same page as any other developers
- [More advanced techniques](https://gist.github.com/peterhurford/3ad9f48071bd2665a8af)
- [How to write Unmaintainable code](https://cs.fit.edu/~kgallagher/Schtick/How%20To%20Write%20Unmaintainable%20Code.html)

Doing these things will ensure that after 8 hours of coffee induced rage, you can at least *somewhat* tell what you were doing, or what you did. 

Additionally it's possible to return a value from a function, instead of simply having the function be void. To do that, you change teh type of the function, and use the ```return``` keyword. A function's execution ends when it hits a return, so if you have code after a return statement, it won't actually run. Aside from that, the returned value is a stand-in for wherever the function is called. 

```c
A float function Pi()
    return 3.1415926536
    
Print to the screen "" + (10 * Pi()) // the value returned by the Pi function will be multiplied by 10. 
```

#### Loops
Sometimes we want to repeat code that we write multiple times, without rewriting it multiple times. Consider for instance, our above example. The code that we wrote up above was linear. It didn't loop. So, it would look something like this:

```mermaid
graph TD
    A[Messages] --> B[ClearDraw]
    B[ClearDraw] --> D[Messages]
    D[Messages] --> C[ClearDraw]
    C[Messages] --> E[ClearDraw]
    E[ClearDraw] --> F[Messages]
    F[Messages] --> J[...]
```

You'll notice that there's really only two things being done, and they're being done over and over again. Loops are a way to take code like this and re-run it, often on some temporary condition, while perhaps changing a detail or two. There are two main types:
- For Loops: Loop over a constantly update condition, ie counting up or down, or removing things from a stack or list. 
- While Loops: Loop while a specific condition is true, ie "the light is up", or "the variable x is less than five", often either a boolean variable is used, or an expression that evaluates to true or false (something like "5<= 4" is false, for example). 

Both of these loop types can work for almost all problems, but they're easier to more convenient to use when used with problems matching their purpose. You could, as an example, use a while loop to decrease a variable constantly and check it, but a for loop already serves that purpose more easily. 

In this case, we want to change the specific image that gets printed. This is where we will introduce **data structures**! Data structures are special ways we (or the programming language) can organize data to make it easier to manage, or faster to use. 

One thing we could make use of here are Lists or Arrays. Lists and Arrays are extremely similar, but Lists are more advanced. Here, advanced doesn't refer to skill, but feature richness. An Array is simply a collection of things. It's what we commonly imagine a list to be. Say you had a paper and some pencil. The paper and its lines are the computer's memory. The pencil represents actual things being stored, or data. If you are a computer writing things down, you'll just move along your paper (memory) and fill it in as you go (store data). 

##### Arrays
An Array is just a list of things you store one after another on the paper. You tell the computer you need an Array of say, 25 items, and it writes a section on the paper 25 lines long, specifically for you to write in. You can write and erase and rewrite in that section, but the sections around it will be given to other programs. 

The issue now is that, if you need say *26* items, you have to request a whole new section of paper, and move all of your values over. If you need to do that multiple times, it's obviously inefficient. Arrays work really well when you know the number, or max number, of things you'll be storing. Otherwise, it doesn't. 

##### Lists 
A List is a more advanced form of an array. Imagine if on your paper, instead of just writing that one section of the paper was yours, you asked the computer to leave a space for where you'll put *another* array, or section of paper. Then, you can request an amount of items you want, and then add onto it when you want by writing the location of the next page section you own. 

Lists also tend to come with lots of functionality such as sorting, inserting new items (not overwriting old ones) in whatever position you want, and other conveniences. 

Lists are typically (only slightly, usually ignorable) slower than arrays, but are more convenient when the amount of items is unknown. Of course, it's entirely possible to just have your program figure out how many things it needs before it creates an array. 

Typically, I will suggest the use of a List, because they're more convenient, harder to mess up, and there's rarely actual losses to it. For more knowledge on this, [here's a quick comparison](https://csharp-station.com/c-arrays-vs-lists/), or a [more detailed one](https://www.educba.com/c-sharp-list-vs-array/) between the two. 


##### Using Arrays and Loops

We now have a data structure we can use to store our data in one spot. Since we only plan to use 5 things, and we plan to do something very simple, I'll use an array. In *FlarkSpeak*, you can initialize arrays in a *FlarkSpeak*esque way, with english, or the way many other languages do with brackets. Thus:

```c

The int Array
```

is the same as 

```c 
The int[]
```
When using *FlarkSpeak*. We will use the way other langauges do, but if you'd like to write your psuedocode differently for your clarity, you may. 

Remember that Arrays are of fixed size. This means we must either tell the language the size of the array, or we must tell it what data to fit inside at the start. We will do that using curly braces, similarly to other languages. 

To create an array that can hold 5 booleans, we would say:
```c
the bool[5] our_booleans
```

To create an array with the first 10 integers we would say:
```c
the int[] first_ints = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
```


Arrays contain multiple values, so you must access them at what's called an "index". An index is the position or spot of an item in an Array, List, or other collection. We have to tell the array which of its values we actually want. Array indexes, like many other things in programming, start at the number 0. Let's look at an example in *FlarkSpeak*. 

```c
the int[] first_ints = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}

Print to the screen "" + first_ints[0] // Access the first item in the array
                                    // First_ints[0] is 1
                                    // Add to string to convert it (FlarkSpeak specific)
```
Outputs
```bash
> 1
```

We could also use that to create our list, such as the below:

```c
the int[10] first_ints
int[0] = 1
int[1] = 2
int[2] = 3
int[3] = 4
int[4] = 5
int[5] = 6
int[6] = 7
int[7] = 8
int[8] = 9
int[9] = 10

Print to the screen "" + first_ints[0]
// same output as before
```
Outputs
```bash
> 1
```

So, using this let's create a ```for``` loop. A for loop has four parts, which I will call the predicate, the condition, the body, and the step. 
- Predicate - the setup of the loop's variable.
- Condition - thing the loop is checking or waiting for.
- Body - What we do in the actual loop
- Step - what the loop does every time it finishes running once. 

Let's say we had a loop we wanted to have count from 0 to 10, and print it out. Breaking what we want to do down, we want to: (1) create a variable to store the value we're currently on, (2) print the variable, (3) increment (increase) the variable's value, and (4) check if we should continue counting. That would make our loop have this structure:
- Predicate = create an int equal to 0
- Condition = Predicate int variable is less than or equal to (<=) 10
- Body = Print out the variable 
- Step = Increase the predicate int variable by one. 

In *FlarkSpeak* this works relatively similar to other langauges. A psuedocode example of *FlarkSpeak* code would be:

```c
for (Predicate ; Condition ; Step) 
    Body
    // Indent to set the scope
```

The semicolons separate the code, so *FlarkSpeak* can tell what's what. In real *FlarkSpeak* our counting loop would look like this. 

```c
for (The int x = 0; x is <= 10; x = x + 1)
    Print to the screen "" + x
```
Which would output

```bash
> 0
> 1
> 2
> 3
> 4
> 5
> 6
> 7
> 8
> 9 
> 10
```



##### Loops and Games
Allow me to explain why I've moved both loops and functions up the list of typical topics. 

Games are different from many other programs that programmers create, because they don't exist to solve a problem or process something immediately. They work to react to a player and that player's input, constantly. Imagine the apps on your computer or phone. They sit and wait for you to use them. Chrome will run forever if you let it, doing almost nothing aside from some miscellaneous background acitivities, and will begin to do more the moment you interact. 

This is atypical for most programs produced by introductory CS students, which often do some thing - maybe pausing for input along the way - and then close. 

It's for this reason I must note that Game Development, and app development in general, is different from normal executable creation in that the loop is fundamental to its usability. For many other programs, a loop is a convenience for simplifying how much code you write. For things that can't close until a user tells them to, they are a necessity. 

Additionally, understanding that loops are integral to games helps understand some of why we write vode for a Game Engine the way that we will later. 

Recall prior that we are using a Game Engine for simplicity. As part of this, the Game Engine handles almost everything we don't want to, and it does this constantly. While our game runs, the part of the Game written by the Game Engine updates the screen, scans the input and output devices, gathers up data on the previous frame and how long everything took to calculate, and only then it calls the instructions we told it to. 

To call those instructions, Game Engines call special functions within the code that we write. A user (such as yourself) can use any of these special names to have that code placed in that step of the game's process. Often these functions, called "callback functions" (because the game code *calls* back to them when it does what it needs to). 

The callback functions have unique names. In the case of *FizzFlark* we are given three callbacks, which the names somewhat indicate by starting with the word "On". *FizzFlark* gives us:
- OnUpdate - Called after a frame update (a frame is an instant of the game)
- OnStart - Called after the game can be started
- OnClose - Called when the user closes

So, instead of our game just running the code we write, the game engine inserts some features. If we represent all of the functions added by *FizzFlark* we can see what this process looks like:

```mermaid
stateDiagram-v2
    [*] --> Initialize
    Initialize --> OnStart
    OnStart --> UpdateFrame
    UpdateFrame --> ApplyFrame
    ApplyFrame --> OnUpdate
    OnUpdate --> UpdateFrame
    ExitGame --> OnClose
    OnClose --> [*]
```

*FizzFlark* handles its end of the work in ```Initialize```, ```ApplyFrame```, and ```UpdateFrame``` functions. In these, it generates the code to handle any settings we provide, like window size, aspect ratio, resolution, framerate, updates any physics in the scene, finds all the assets and models, makes sure updates are reaching the screen, and so on. 

I consider this important because it explains why we place our code in certain functions when writing for a Game Engine, and being able to visualize this helps decide where certain code needs to be placed in that stack of functions. For instance, if you have a function that initializes data and only needs to run once, should it go in ```OnStart``` or ```OnUpdate```? What about a block of code that allows the player's input keys to move their character around? 

Beyond that, we only need to give the GameEngine our settings, and write the ```OnStart```, ```OnUpdate```, and ```OnClose``` methods to get all of the functionality that we're interested in. 
With this foundation set up, we will move onto a slightly more complex aspect of programming often found in Game Design. 


##### Using Arrays and Loops

We now have a data structure we can use to store our data in one spot. Since we only plan to use 5 things, and we plan to do something very simple, I'll use an array. In *FlarkSpeak*, you can initialize arrays in a *FlarkSpeak*esque way, with english, or the way many other languages do with brackets. Thus:

```c

The int Array
```

is the same as 

```c 
The int[]
```
When using *FlarkSpeak*. We will use the way other langauges do, but if you'd like to write your psuedocode differently for your clarity, you may. 

Remember that Arrays are of fixed size. This means we must either tell the language the size of the array, or we must tell it what data to fit inside at the start. We will do that using curly braces, similarly to other languages. 

To create an array that can hold 5 booleans, we would say:
```c
the bool[5] our_booleans
```

To create an array with the first 10 integers we would say:
```c
the int[] first_ints = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}
```


Arrays contain multiple values, so you must access them at what's called an "index". An index is the position or spot of an item in an Array, List, or other collection. We have to tell the array which of its values we actually want. Array indexes, like many other things in programming, start at the number 0. Let's look at an example in *FlarkSpeak*. 

```c
the int[] first_ints = {1, 2, 3, 4, 5, 6, 7, 8, 9, 10}

Print to the screen "" + first_ints[0] // Access the first item in the array
                                    // First_ints[0] is 1
                                    // Add to string to convert it (FlarkSpeak specific)
```
Outputs
```bash
> 1
```

We could also use that to create our list, such as the below:

```c
the int[10] first_ints
int[0] = 1
int[1] = 2
int[2] = 3
int[3] = 4
int[4] = 5
int[5] = 6
int[6] = 7
int[7] = 8
int[8] = 9
int[9] = 10

Print to the screen "" + first_ints[0]
// same output as before
```
Outputs
```bash
> 1
```

So, using this let's create a ```for``` loop. A for loop has four parts, which I will call the predicate, the condition, the body, and the step. 
- Predicate - the setup of the loop's variable.
- Condition - thing the loop is checking or waiting for.
- Body - What we do in the actual loop
- Step - what the loop does every time it finishes running once. 

Let's say we had a loop we wanted to have count from 0 to 10, and print it out. Breaking what we want to do down, we want to: (1) create a variable to store the value we're currently on, (2) print the variable, (3) increment (increase) the variable's value, and (4) check if we should continue counting. That would make our loop have this structure:
- Predicate = create an int equal to 0
- Condition = Predicate int variable is less than or equal to (<=) 10
- Body = Print out the variable 
- Step = Increase the predicate int variable by one. 

In *FlarkSpeak* this works relatively similar to other langauges. A psuedocode example of *FlarkSpeak* code would be:

```c
for (Predicate ; Condition ; Step) 
    Body
    // Indent to set the scope
```

The semicolons separate the code, so *FlarkSpeak* can tell what's what. In real *FlarkSpeak* our counting loop would look like this. 

```c
for (The int x = 0; x is <= 10; x = x + 1)
    Print to the screen "" + x
```
Which would output

```bash
> 0
> 1
> 2
> 3
> 4
> 5
> 6
> 7
> 8
> 9 
> 10
```

#### Objects/Structures
One thing that many GameEngines and programming languages support for modeling complex things and interactions is the concept of bundling things into Objects and Structures.

Objects and Structures are both concepts for organizing and collecting together data and methods into a singular entity. Let's return to our Dungeon Master analogy. 

A dungeon master doesn't only rely on having tables of information, rules for dice rolls, and ways to quickly perform tasks related to their game. They rely on it being organized, and on being able to access a single card or sheet that holds all of that information for them. They might have a sheet for character creation, or a sheet for combat rules, or a sheet with all of the basic class or spell information they need. The same applies for players and the things they used to quick reference, or easily play. 

These organizations of data and functions are to tabletop games what objects and structures are to programming. 

The running theme with the above is that everything that belongs together, is encapsulated into its own unit. This simplifies a DM's job, because they can manage a single thing in a single situation, and have everything they might need to do that. 

The same concept occurs in computer programming in the form of Objects and Structures. Not all programming languages support Objects or Structures, but many do, and for some it's integral to the language's use. In the field of game design, Object Oriented Languages (those that make obvjects integral to their use) make up a significant amount of the market for the langauges Game Engines and video game programmers use. This has to do with the principle behind Object Oriented design. 

Object Oriented design typically aims to *model* an entity or target through code. For instance, instead of creating all of the functions and rules related to say, an apple, and then promising to only use them correctly, an Object Oriented language would want you to make all of the functions for an apple *inside* of an 'apple' object. Then, you would use that object to call them. 

Generally speaking, Objects can be abstract, or they can be instanced. An 'abstract' object is one that has all of the principles of an object, but doesn't need to be stored in a variable. An abstract object typically serves more as a collection of functions, or a model for other instanced objects, than an object itself. A 'instanced' object on the other hand, typically expects to be created and stored into a variable. Regardless of which of these you refer to, we often call objects 'classes' or 'classes of objects'.

Consider a car factory and a car. You might put all of the functions a car factory performs in a "car factory" object, and call them on variables you want to. But, you might want to specifically save data related to specific "car" objects, so you would make multiple variables of the "car" type that you create. 

##### Object Examples

Luckily *FlarkSpeak* supports objects. Let's look at making an example object in *FlarkSpeak*, such as our car and car factory. First, let's decide what we want each to do, and what we want each to have. 

The car Object should have:
- Gas, determining how much energy it has
- Mileage, determining how far it can get on x amount of gas. 
- Passengers, determining how many people it has inside
- Seats, determining how many people it can hold
- Driver, determining if it has a driver or not

Now, for each of the above we want to choose a data type that would represent it well, and be useful to us. 
- Gas would be well represented by a float (decimal), so we can have partial gallons
- Mileage would be well represented by a float (decimal), so we can have partial miles per gallon 
- Passengers would be well represented by an int (number), because we can't have a part of a person
- Seats would likewise be well represented by an int (number), because we can't have partial seats (or partial people)
- Driver would be well represented by a boolean, because we want to answer a true or false question. 

We also want our car to be able to do some stuff. For now, let's just let it check if it can do stuff. 
- canDrive, given a distance decide whether or not the car can go 
- canPickup, given a number of passengers decide whether it could fit them 
- canDropoff, given a number of passengers decide whether it could drop them off

All of these answer true or false questions, so they should all return boolean values. And, each of these should accept a value. 
- canDrive should accept a float distance (since we allow partial miles), and return a boolean
- canPickup should accept an integer amount of people, and return a boolean
- canDropoff should accept an integer amount of people, and return a boolean. 

If we want to try to implement this, we'll need to understand conditionals. 

##### Conditionals 

Conditionals are, like they sound, statements that evaluate and execute based on conditions. The "While" loop, is a conditional loop, and the "for" loop generally uses a condition. 

The main conditional statements are ```if``` and ```else```. The ```if``` conditional executes anything within its body "if" the condition it's given calculates out to be true. The ```else``` conditional executes anything within its body if the conditional above it failes to execute. 

An example condition might be "2 >= 5". This statement is, clearly, false. Thus, the below code will do nothing. 

```c
if (2 >= 5)
    Print to the screen "The milk tastes weird"
```

Versus the below code

```c
if (2 >= 5)
    Print to the screen "The milk tastes weird"
else 
    Print to the screen "The milk tastes normal"
```

Would output

> The milk tastes normal 

Conditionals can check equality, numeric difference, or the result of an operation. Generally, if something equates to a non-zero value it can be considered true. To check equality, we use a double equal sign or "==" to distinguish from a single equal sign, which sets equality. To do numeric equality and inequality, we can use the greater and lesser than signs, alongside the equal sign. 

```c
(2 < 3) // this is true
(2 > 3) // this is false
(2 >= 2) // this is true
(10 + 2) // this is true
(0) // this is false
(5 == 5) // this is true 

// initialize a variable 
the int x = 7

(x == 9) // this is false
(x = 11) // this is true, and changes the value of x!!!
(x == x) // this is true 
```

All of the above can be placed inside of a conditional. We can also add the "not", "and", and "or" operations - "!", "&&", and "||" respectively.

```c
(2<3 || 3 < 2) // this is true
(2<3 && 3<2) // this is false
(!false) // this is true
(!true) // this is false
```

The real strength of conditionals comes with composing their conditions of variables. For instance, you could check if a variable equals true, or you could check if player 1's number is bigger than player 2's number. Alternatively, or perhaps in addition, you can compose conditions and conditionals together. For instance, we could take user input, and store it in a variable, and check what it equals

```c
The char user_input = Accept a character of input

if (user_input == 'y') // check if it's equal to the character 'y'
    Print to the screen "Awesome!"
else if (user_input == 'm') // Note this! It's chaining two conditionals together
    Print to the screen "Maybe awesome?"
else 
    Print to the screen "Not Awesome.."
```

First, allow me to note the middle conditional is actually two together. It's an else, connected to the first conditional, and then there's a second within it. It's thus equivalent to this

```c
The char user_input = Accept a character of input

if (user_input == 'y')
    Print to the screen "Awesome!"
else 
    if (user_input == 'm')
        Print to the screen "Maybe awesome?"
    else 
        Print to the screen "Not Awesome.."
```

I'd also note that this accepts all possible character values in the last condition. So, if I entered 's' it would print "Not Awesome..". If we want only three values to be considered, we could either chain another if onto this, or remove the elses entirely. 

So either

```c
The char user_input = Accept a character of input 

if (user_input == 'y')
    Print to the screen "Awesome!"
else if (user_input == 'm')
    Print to the screen "Maybe awesome?"
else if (user_input == 'n') 
    Print to the screen "Not Awesome.."
        
```

or just 

```c
if (user_input == 'y')
    ... 
if (user_input == 'n')
    ...
if (user_input == 'm')
    ...
```

The issue with not chaining if's with elses is that they're unaware of each other, so they can be unperformant. If a single if is true, it's assumed that the else conditions don't need to run, but independent if statements can't consider that. 

But breaking from this quick introduction, let's implement our car. 

##### Using Objects 

Our car object will be implemented with the goals we mentioned at the start of this section. 

```c
The class Car
    the float gas
    the float mileage
    the int passengers
    the int seats
    the bool driver
    
    A bool function called canDrive(float Distance)
        float number_of_gallons = Distance/mileage
        if (number_of_gallons > gas)
            // the number of gallons needed is greater than the amount of gas we have
            return false
        else 
            // else runs if the above statement doesn't
            return true 

    A bool function canPickup(int numPeople)
        if (numPeople > (seats-passengers))
            return false
        else 
            return true
            
    A bool function canDropoff(int numPeople)
        if (numPeople>passengers)
            return false
        else 
            return true
```

First, I think that's a bit ugly. *FlarkSpeak* has some cool conventions that can make that simpler for us. One, we can get rid of the unneccessary the's, a's, and other introductory words. So, instead of 

```c
the float gas
```


we could just say

```c
float gas
```
 
 Additionally, the scope is a little bit unclear at times. Especially when we have a line between lines. We can use curly-braces to indicate scope, so this:
 
 ```c
bool function called canDrive
    line1..
    line2..
    line3..
    
    line_4..?
int count = 3 // stuff outside the function
```

Is the same as:

```c
bool function called canDrive(){
    line1..
    line2..
    line3..
    
    line4..
}
int count = 3 // stuff outside the function
```

We'll also get rid of the extra fluff around functions and arrays. The parenthesis and square brackets are enough of an indicator, and we can use naming convention to make their differences more apparent. Let's also end lines with semicolons

Let's apply our new conventions to the object class. 

```c#

class Car {
    float gas;
    float mileage;
    int passengers;
    int seats;
    bool driver;
    
    bool canDrive(float Distance) {
        float number_of_gallons = Distance/mileage;
        
        if (number_of_gallons > gas)
            // the number of gallons needed is greater than the amount of gas we have
            return false;
        else
            // else runs if the above statement doesn't
            return true;
    }

    bool canPickup(int numPeople){
        if (numPeople > (seats-passengers))
            return false;
        else 
            return true;
    }
            
    bool canDropoff(int numPeople){}
        if (numPeople>passengers)
            return false;
        else 
            return true;
        }
}
```

At first glance, this feels slightly less readable, however it removes instances of ambiguity. The conditional statements (if and else) should technically also have the curly braces, but conditionals with a single line afterwards don't need curly braces eiter for convention or readability, so I shall leave them. 

But now that we have a class comes using it. Each of the things defined inside of a class can be called one of its "members". To access members, we use the dot operator, or ```.```, followed by what we want to access. So, let's create a Car, and access the number of passengers. 

```C#
Car red_car = new Car()
```

This line creates a new instance of the "Car" class, and stores that object in the variable "red_car". The type of an Object is the same as the class it's made of, so a "Car" object is of type "Car" (or maybe "Object"). 

Let's apply the dot operator to show how many passengers the car has. 

```C#
Car red_car = new Car()

Print to the screen "The number of passengers is: " + red_car.passengers
```

This would output

> The number of passengers is: {???}

The "{???}" is a quirk of *mine*, not the class. There's an issue with the above code. We never initialized, or set, the values inside of "red_car". So, any number could go there. Whatever was there when the memory was taken by our program would still be there. Some programming languages would automatically set it to zero for us, but *FlarkSpeak* wants us to be educated, so it doesn't. 

There are two main ways to go about initializing these values. We could use what's called a constructor, or we could use manual initialization. 

##### Constructors and Initialization 

A constructor is a special function whose purpose is to setup and create an Object, or class instance. It typically has the same name as the class, and is defined within the class. It's also possible to apply a method called overloading, where you create multiple functions with the same name but different inputs, to get multiple different constructors. 

A constructor is always necessary for a class to be created, and we called it above without realizing it.

```C#
Car red_car = new Car();
```

The first use of "Car" is saying that the type of the "red_car" variable is a car. But, the second use has parenthesis after it. That is a function, which serves to initialize the object. The ```new``` keyword just tells the program to give up some storage space for whatever the constructor does.

We didn't create this constructor. It was provided by default by the programming language. It does the bare minimum possible, basically just making sure there's enough memory for all the members of the class to exist. Usually the default constructor initializes a class to empty or general values, such as 0, or undefined. It'd also be possible to make it return an error, that way you know the values are always being provided.

Let's add a constructor to our class. We'll start with a default.

```c#

class Car {
    float gas;
    float mileage;
    int passengers;
    int seats;
    bool driver;

    Car() {
        gas = 0;
        mileage = 0;
        passengers = 0;
        seats = 0;
        driver = false;
    }

    ... // the rest of the class
}
```

Now we have a default Constructor! First, notice that we didn't need to provide a type for the constructor. This is typically the case. Second, let's have another lesson on readability!!!

Since classes, and certain other structures in programming, need "instances" of them created, they get a special keyword for referring to themselves. That is the ```this``` keyword. The ```this``` keyword refers to the specific instance running the code.

When you create a "Car" Object, the computer finds the "Car" class and copies over all of its data to a new variable. That new variable is what "this" refers to.

So, let's rewrite our class.


```c#

class Car {
    // we don't need to use this when creating these, but we could?
    float gas;
    float mileage;
    int passengers;
    int seats;
    bool driver;

    Car() {
        this.gas = 0;
        this.mileage = 0;
        this.passengers = 0;
        this.seats = 0;
        this.driver = false;
        /* We could also do something like
        this.color = "red";
            Even though we don't have a color property at present
        */
    }

    ... // the rest of the class
}
```

Now, let's add a constructor that accepts a value for the gas, and number of seats.

```c#

class Car {
    // we don't need to use this when creating these, but we could?
    float gas;
    float mileage;
    int passengers;
    int seats;
    bool driver;

    Car() {
        ... // Our Car constructor from above
    }

    Car(int gasAmnt, int seatsNum){
        this.gas = (float) gasAmnt; // "(float)" converts the value after it into a float type, instead of an int.
        this.seats = seatsNum;
    }

    ... // the rest of the class
}
```

The above constructor doesn't initialize the other values to zero.. We could add that, or we could be lazy. Constructors can call other constructors!

```c#

class Car {
    // we don't need to use this when creating these, but we could?
    float gas;
    float mileage;
    int passengers;
    int seats;
    bool driver;

    Car() {
        ... // Our Car constructor from above
    }

    Car(int gasAmnt, int seatsNum){
        Car(); // Empty constructor initializes everything to zero.
        this.gas = (float) gasAmnt; // change from zero to new val
        this.seats = seatsNum; // change from zero to new val
    }

    ... // the rest of the class
}
```

We could also make a constructor that accepts all of the values, and have our default call that.

```C#
class Car {
    // we don't need to use this when creating these, but we could?
    float gas;
    float mileage;
    int passengers;
    int seats;
    bool driver;

    Car() {
        Car(0, 0, 0, 0, false); // This will call the constructor below
                                // The program can recognize which constructor you mean because of the input types
    }

    Car(float gasAmnt, float mileageAmnt, int passAmnt, int seatsNum, bool isDriven)
        this.gas = gasAmnt; // change from zero to new val
        this.mileage = mileageAmnt;
        this.passengers = passAmnt;
        this.seats = seatsNum; // change from zero to new val
        this.driver = isDriven;
    }

    ... // the rest of the class
}
```

I will note that this works because of the above mentioned overloading. Overloading works because the computer sees these functions by their names AND their inputs. This is called their signature. Thus, for the computer it's less like Car vs Car, and more like "Car:Void" vs "Car:Float-Float-Int-Int-Bool". You can tell which is which pretty easily.

Let's get back to using our code. Our Car class looks like this:

```C#
class Car {
    // we don't need to use this when creating these, but we could?
    float gas;
    float mileage;
    int passengers;
    int seats;
    bool driver;

    Car() {
        Car(0, 0, 0, 0, false); // This will call the constructor below
                                // The program can recognize which constructor you mean because of the input types
    }

    Car(float gasAmnt, float mileageAmnt, int passAmnt, int seatsNum, bool isDriven)
        this.gas = gasAmnt; // change from zero to new val
        this.mileage = mileageAmnt;
        this.passengers = passAmnt;
        this.seats = seatsNum; // change from zero to new val
        this.driver = isDriven;
    }

    bool canDrive(float Distance) {
        float number_of_gallons = Distance/mileage;

        if (number_of_gallons > gas)
            // the number of gallons needed is greater than the amount of gas we have
            return false;
        else
            // else runs if the above statement doesn't
            return true;
    }

    bool canPickup(int numPeople){
        if (numPeople > (seats-passengers))
            return false;
        else
            return true;
    }

    bool canDropoff(int numPeople){}
        if (numPeople>passengers)
            return false;
        else
            return true;
        }
}
```

And using it looks like this

```C#
Car car_one = new Car();
Car car_two = new Car(5, 5, 10, 10, true);

Print to the screen "The number of passengers in the second car is: " + car_two.passengers;
Print to the screen "It is " + car_two.canPickup() + " that the second car can pickup more passengers.";
```

Would output

```bash
> The number of passengers in the second car is: 10
> It is false that the second car can pickup more passengers
```

We could also use an Object to interact with a specific screen.

```C#
Screen MainScreen = The user's screen;
Car car_one = new Car();
Car car_two = new Car(5, 5, 10, 10, true);

Screen.printLine("The number of passengers in the second car is: " + car_two.passengers);
Screen.printLine("It is " + car_two.canPickup() + " that the second car can pickup more passengers.");
```

Some objects will be provided by the language, others will be provided by the Game Engine, while even more will need to be created by you.

Let's give a cool example of a way someone might use a class. One of our friends created a function that checks if a Car object is a bus. They define a bus as any Car object with exactlty 24 seats.

```C#
bool carIsBus(Car car_in){
    if (car_in.seats = 24){
        return true;
    }
    if (car_in.seats != 24) { // this is the NOT equal operator
        return false;
    }
}
```

Let's use our brilliant coder friend's function.

```C#
Car our_car = new Car(100, 100, 0, 5, true);

// this car has 5 seats! It's not a bus

Screen.printLine("It is " + carIsBus(our_car) + "that this car is a bus, because it has " + our_car.seats + "seats");
```

Outputs

> It is true that this car is a bus, because it has 24 seats.

Wait a minute! This isn't right.. Why not? Because our coder friend is STUPID. Or maybe they just messed up. Whatever the case, reread their conditional. They said "=" instead of "==". That means they *set* the value of the seats field, they didn't *check* the value.

That's a rather simple mistake to make, and can be hard to notice. And, if we're dealing with less competent or experiences programmers, they might do things that don't work, or aren't clear.

To mitigate issues from both of these, we can use something called access control, or access modifiers.

encapsulation, abstraction, inheritance, and polymorphism [TODO]

### Structures 

A structure is, simply put, a new description for a way to organize data. It structures other data types into a new one. In Object oriented Languages (programming languages that use Objects as a main part of the language) often used for game design, such as C#, the structure or struct is actually just a "lightweight object". usually an object without functions. 

Recall how we had data types such as the String, int, boolean, and so on. Each of those data types has a certain size within the computer, and each has their own rules for being interpreted. A structure is the same way. For instance, we could make a new structure that consists of two ints, and have that new structure be called a coordinate. The two ints could represent an x and y position. We now have a new datatype that we can use easily for our variables, instead of needing to use two separate variables. With a struct, to access its members we use an operator called the dot operator. The dot operator (```.```) basically means "go to this location within this data". So something like 

```c
variable.second_variable
```

Means go to the "second_variable" location within the variable memory space. Since we're putting multiple variables inside of a new type, structures allow us to use the dot operator to access that internal data. Let's see this in action, and compare them below. 

```C#
// The non-struct method 
int x_pos;
int y_pos;

x_pos = 5;
y_pos = 7;

print to the screen "" + x_pos
print to the screen "" + y_pos
```
Which would output 
```bash
> 5
> 7
```

Versus 
```C#
// The struct method

struct coordinate { // create the struct
  int x; // create an x member
  int y; // create a y member
}

coordinate my_cord; // create the coordinate variable

my_cord.x = 5;
my_cord.y = 7;

print to the screen "" + my_cord.x;
print to the screen "" + my_cord.y;
```
Which would output
```bash 
> 5
> 7
```

While this example may make the struct seem like a lot of extra work, consider what happens when instead of handling one coordinate, you're handling several. Let's go through the above example again with three coordinates. Let's print the x and y values of three different coordinates. 

```C#
// The non-struct method 
int x_pos1;
int y_pos1;

x_pos1 = 5;
y_pos1 = 7;


int x_pos2; 
int y_pos2; 

x_pos2 = 8;
x_pos2 = 9; 

int x_pos3;
int x_pos3;

x_pos3 = 9;
x_pos3 = 4;

print to the screen "" + x_pos1
print to the screen "" + y_pos1

print to the screen "" + x_pos1
print to the screen "" + y_pos2

print to the screen "" + x_pos3
print to the screen "" + y_pos3
```

Which would output 

```bash 
>5
>7
>5
>9
>9
>4
```

Evaluate the code and the outputs. Did everything go as expected? if not, why? Let's look at the example using structs. 

```C#
// The struct method

struct coordinate { // create the struct
  int x; // create an x member
  int y; // create a y member
}

coordinate my_cord1; // create the coordinate variable
coordinate my_cord2;
coordinate my_cord3;

my_cord1.x = 5;
my_cord1.y = 7;

my_cord2.x = 8;
my_cord2.y = 9;

my_cord3.x = 9;
my_cord3.y = 4;

print to the screen "" + my_cord1.x;
print to the screen "" + my_cord1.y;


print to the screen "" + my_cord1.x;
print to the screen "" + my_cord2.y;


print to the screen "" + my_cord3.x;
print to the screen "" + my_cord3.y;
```
Which outputs 
```bash 
>5
>7
>5
>9
>9
>4
```

They're still very very similar. Overall, this whole thing is a mess. Let's clean them up a bit. One, both structs and variables can be initialized (have their values set) when they're created. With structs, this happens inside of curly braces (like with arrays) and you treat each of its members like an internal (in its scope) variable. Example:

```C#
struct TestStruct {
  bool cool_bool;
  int fun_int; 
  String angry_string;
}

TestStruct my_variable = new TestStruct {cool_bool = false, fun_int = 3, angry_string = "IM MAD"};
``` 

You'll notice there that I've used the ```new``` operator. The ```new``` operator  calls on an Object or Structs "contructor" function. A constructor is a function whose job is to setup the memory for an object or structure, so that it can be used. Structs do *not* need to be initialized via the ```new``` operator, but if they aren't then you need to set each field manually, like below, before you can use it. 

```C#
struct TestStruct {
  bool cool_bool;
  int fun_int; 
  String angry_string;
}

TestStruct my_variable; 
my_variable.cool_bool = false;
my_variable.fun_int = 3;
my_variable.angry_string = "IM MAD";
``` 

Right now we're using the default constructor, since we haven't written one, which doesn't really do much, so we assign the values after between the curly braces ```{...}```. 

Let's redo the above examples like this. 

```C#
// The non-struct method (redone)
int x_pos1 = 5;
int y_pos1 = 7;

int x_pos2 = 8; 
int y_pos2 = 9; 

int x_pos3 = 9;
int x_pos3 = 4;

print to the screen "" + x_pos1
print to the screen "" + y_pos1

print to the screen "" + x_pos1
print to the screen "" + y_pos2

print to the screen "" + x_pos3
print to the screen "" + y_pos3
```

Which would output 

```bash 
>5
>7
>5
>9
>9
>4
```
And then our struct version.
```C#
// The struct method (redone)

struct coordinate { // create the struct
  int x; // create an x member
  int y; // create a y member
}

coordinate my_cord1 = new coordinate {x = 5, y = 7}; // create the coordinate variable
coordinate my_cord2 = new coordinate {x = 8, y = 9};
coordinate my_cord3 = new coordinate {x = 9, y = 4};


print to the screen "" + my_cord1.x;
print to the screen "" + my_cord1.y;

print to the screen "" + my_cord1.x;
print to the screen "" + my_cord2.y;

print to the screen "" + my_cord3.x;
print to the screen "" + my_cord3.y;
```
Which outputs 
```bash 
>5
>7
>5
>9
>9
>4
```

That's looking a little bit cleaner. But let's introduce another benefit of Structs and Objects, their use in loops and functions. 

Loops can loop over more than a simple condition. Loops can often *also* be given an "iterator" or iteration condition. An iterator is something that creates an iterator condition. 

What is an iterator condition? An iterator condition is something that gives a loop the command to continue, and does so until it has nothing else to iterate over. For instance, if we have an array, we can loop over the elements within that array. For this, the *FizzFlark* GameEngine gives us the ```foreach``` statement. The ```foreach``` statement executes for each element in an enumerable or iterable condition - A.K.A a condition that has multiple values within it. 

A simple use of the ```foreach``` statement is the ```foreach ... in ...``` statement. It is structured as such: 
```C#
foreach ( datatype var_name in Iterable){
  ... // the stuff to be done
 }
```
Here's an example:
```C#
int[] my_numbers = new {0, 1, 2, 3, 4, 5, 6, 7, 8, 9, 10}

foreach (int number in my_numbers){
  print to the screen "" + number;
}
```
Outputs
```bash
> 0
> 1
> 2
> 3
> 4
> 5
> 6
> 7
> 8
> 9
> 10
```

For something like counting to ten, this is pretty weak, but what about for our coordinates? We could make a list of coordinates, loop over them, and print out their fields. 

```C#
// The struct method (redone)

struct coordinate { // create the struct
  int x; // create an x member
  int y; // create a y member
}

coordinate my_cord1 = new coordinate {x = 5, y = 7}; // create the coordinate variable
coordinate my_cord2 = new coordinate {x = 8, y = 9};
coordinate my_cord3 = new coordinate {x = 9, y = 4};

coordinate[] coords = {my_cord1, my_cord2 my_cord3};

for (coordinate coord in coords){
  print to the screen "" + coord.x
  print to the screen "" + coord.y
}
```
Which outputs 
```bash 
> 5
> 7
> 8
> 9
> 9
> 4
```

Now that we've combined structures and an iterator, we have code that is concise, and significantly easier to spot bugs in than what we started with. 

We can also use structs in functions. What if we want to return an x and a y coordinate pair from a function? If we wanted to do it without structs, we would need to use an int array of size two. With a struct, we can do the same thing but cleaner. 

```C#
struct coordinate {
  int x
  int y
}

A coordinate function starshipPosition(ship)
        int ship_x = getXLocation(ship);
        int ship_y = getYLocation(ship);
        coordinate return_coordinate = new coordinate{x = ship_x, y = ship_y};
        return return_coordinate;
```
Or in a less *FlarkSpeakean* way

```C#
struct coordinate {
  int x
  int y
}

coordinate starshipPosition(Ship ship) /* Ship is a class */ {
        int ship_x = getXLocation(ship);
        int ship_y = getYLocation(ship);
        coordinate return_coordinate = new coordinate{x = ship_x, y = ship_y};
        return return_coordinate;
}
```



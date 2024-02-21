## PersonalMethodologies
Jake Malmrose
Personal Methodologies

#Design and brainstorm:  
Get a mental map of the software. If you’re working with pre-existing programs or libraries that I haven’t learned, reading up on that comes first.  
Start creating skeleton classes for major components, use this to figure out whether or not stuff needs to be broken down or redesigned.  
For bigger programs, diagram out components using UML or something that serves the same purpose.   

#Write functionality skeleton:  
Write skeleton methods, stuff will come up when figuring out what methods will take in/output so be prepared to re-design.  
Here, set up tests and start writing some tests for core functionality. Complete TDD can be hard, but writing skeleton methods alongside tests should help figure out how to properly design your code, and catch bugs early.  

#Write functionality:  
Start writing functionality within all the methods. Again, be prepared to refactor at least once.  
If methods start balooning in size, break them up and refactor.  
Keep an eye on code complexity. If you write a method that requires you to keep track of 7+ "things", consider refactoring after it passes tests.  

#Bugfix/rewrite:  
Test for bugs, and rewrite whatever is broken. Most of my time is spent here

##Rules:
Code should explain itself and be legible. It shouldn’t be overwhelming to look at. This means the following requirements: 
Dont encode type information in variable names.  
Variables are named concisely. Descriptive comes before short in variable names.  
Small functions are king. Single responsibilities for each function. This facilitates readability and maintainability.  
There shouldn’t be more than 6 things you need to keep track of within a function.  
Be prepared to resign frequently to maintain readability. Time spent earlier is usually saved later.  
Other things:  
I try to avoid coding with music, but if I have to it must not have lyrics. You can write code while zoned out, but it produces unreadable code.  
I don’t have a preference between group work and solo work. Both have pros and cons, and situations where either should be used. I do enjoy pair programming and think it often much more than doubles productivity between two people, but more than two is usually ineffective for anything other than sharing information.  
Trello is useful, and I’d say vital for larger projects. It’s unfortunate so far only 1 of my classes have had a project large enough for me to deem Trello necessary, and even then it was only due to lack of experience with technologies used.  
Coding is fun, and you need to self reflect for it to be enjoyable. Whether it’s on your process or your code, spending time reflecting makes it more enjoyable and saves time down the line.  

# upper 

converts given string to uppercase ( yeah, really)

its a static method , so enjoy calling directly you pythonista :p ( dont forget to import the class though, and adding a semicolon is something you will do even if i warn also  😂 )



# What is this ?

I wanted to know how i can use a package as dependency in other , so i looked for the simplest way possible


# Why?

learning packaging and how the code you write can be reused makes me think like i am actully engaged and doing something productive 🤓


# How? 
This is how i created this package

```
mvn archetype:generate
```
it asks to type the GAV ( in maven terminology a GAV is expansio of GroupId , ArtefactId , and Version 🧘‍♂️)  coordinates , create one for yourself
then edit the entry class and added a static method  that converts a given string to UPPERCASE 🥶
for this package to be exporte  the classpath is always a pain in the back. so i just added a configuration XML shit to the  maven-jar-plugin [MORE HERE](https://stackoverflow.com/questions/9689793/cant-execute-jar-file-no-main-manifest-attribute)

essentially you just need to tell what is your Main-Class to maven to package it. 


# Things Learnt:
1. Maven ( not the nitty gritty)
2. How to package your single java class so that world can use it [READ HOW](http://tutorials.jenkov.com/maven/publish-to-central-maven-repository.html) 
3. Creating Simple things brings happines :smile:

# why so much README? 

its not for you , i might come back and look at my own code in case i dont do anything after this and completely forget about what i have built. 

reading back my own readme helps me getting their faster :) 



peace 



# Development-Best-Practices
Writing code is different then the real development. Only a good developer knows, how to develop a good, scalable, secure, managed application. This Repo help you to learn some good practices, which a developer should follow. 

## Clean Code :
### Overview & 
#### 1. First Chapter :
#### 

#### 2. Second Chapter (Meaningful Name) :
Names are everything in software. We name our variables, our functions, our arguments, classes, and packages. We name our source files and directories that contains them. Because we do so much of it, we'd do it well.
What follows are some simple rules for creating good names.

- <b>Use Intention-Revealing Names</b>:
    * The Name of variable, function, or class, should answer all the big questions. It should tell you why it exist, what it does, and how it is used. If a name requires a comment, then the name does not revel its intent. Choosing names that revel intent can make it much easer to understand and change code.
- <b>Avoid Disinformation</b>: 
    * Programmer must avoid leaving false clues that obscure the meaning of the code. We should avoid words whose entrenched meaning vary from our intended meaning. For example, *hp, aix*, and *sco* would be poor variables name because they are the name of the Unix platform or variants.
    * Do not refer to a grouping as an *accountList* unless it's actually a *List*. The word list means something specific to programmers. if the container holding the accounts is not actually a *List*. it may lead to false conclusion. So *accountGroup* or *bunchOfAccounts* or just plain *accounts* would be better.
    * Beware of using names which vary in small ways. How long does it take to spot the subtle difference between a *XYZControllerForEfficientHandlingOfString* in one module and somewhere a little more detail more distant   *XYZControllerForEfficientStrongOfString*?
- <b>Make Meaningful Distinctions</b> 
    * a function or variable name should make a meaningful distinction from one another. like *getUserAccount()* is distinguishable from *account()*, but at the same time *getActiveAccount(), getActiveAccounts(), getActiveAccountInfo(), moneyAccount(), account()*. these names are indistinguishable from each other. In these type of names you have to add a proper comment for each of the functions.
- <b>Use Pronounceable Names</b>
    * Added change

    

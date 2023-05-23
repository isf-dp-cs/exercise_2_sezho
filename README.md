# Instructions
## Create the Avengers class based on the UML diagram below
The `printInfo()` method should print out all the attributes, including each power


|   <center>Avengers</center>  |
|:------------------------|
  |  |
| - name: String    |
| - alias: String   |
| - age: int        |
| - powers: String[] |
  |  |
| + Avengers(name:String, alias:String, age:int, powers:String[]) |
| + getName():String |
| + setName(name:String):void |
| + getAlias():String |
| + setAlias(alias:String):void |
| + getAge():int |
| + setAge(age:int):void |
| + getPowers():String[] |
| + setPowers(powers:String[]):void |
| + printInfo():void | 
  
 The `printInfo()` method should print out all the attributes, including each power
  
 ## Test the Avengers Class
  `AvengersTest` includes the first steps of testing your class. 
  1. In the `main()` method, change the attributes of `avenger1` using your setters
  2. Print the updated information of `avenger1`
  3. Create a second avenger and print its information



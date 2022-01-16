🌱 Automation Code Basics :

1. Never Hardcode
2. Make the class as final to avoid extending it
3. Create private constructor to avoid creating objects of that class
4. Create getter method to call any variables except constants
5. Make variables as private
6. Make variable as static to use it without creating objects
7. Create Framework constants in src/main
8. Keep only tests in src/test
9. Keep resources in src/test/resources
10. Create BaseTest for drivers setup() and teardown() and extend it with all classes
11. Use Owner jar for reading property
12. Use Zerocell jar for reading and writing excel
13. Use AssertJ jar for doing hard and soft assertions instead of Testng or junit 
14. Use Local date joda jar for using date and time instead of localdate from java 
15. Always use trim() when reading any string values
16. Create page classes and By return type variables in it and make it as private final
17. Always include type value for password xpath(id = "password" and type = "password")
18. Use method chaining by adding return this at last line of all the methods in a class and return type of methods as same class name so that we can access the methods in chains instead of calling objects always in other classes
19. Use By element instead of PageFactory so that dynamic xpath can be created which is not possible in pagefactory 
20. PageFactory may give stale element reference or Null pointer exception - so avoid using it

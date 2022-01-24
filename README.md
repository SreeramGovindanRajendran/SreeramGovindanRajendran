🌱 Automation Code Basics :
1. Never Hardcode
2. Make the class as final to avoid extending it
3. Create private constructor to avoid creating objects of that class
4. Create getter method to call any variables except constants
5. Make variable as static to use it without creating objects and private along with getter and setters
6. Create page objects in src/main
7. Keep only tests in src/test
8. Create BaseTest for drivers setup() and teardown() and extend it with all classes
9. Use Owner for property, Zerocell for excel, Lombak for POJO, AssertJ for assertions, Local date joda for date/time, Allure and Extent for reports
10. Always use trim() when reading any string values
11. Create page classes and By return type variables and make it as private final
12. Use method chaining so that we can access the methods in chains instead of calling objects always
13. Use By element instead of PageFactory so that dynamic xpath can be created which is not possible in pagefactory 
14. PageFactory may give stale element reference or Null pointer exception - so avoid using it
15. Create enums and ExplicitWaitFactory for waits
16. Use Inheritance only if it satisfies IS A relationship and many methods of super class needs to used in subclass

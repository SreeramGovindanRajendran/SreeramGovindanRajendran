# Automation Code Basics :
1. Make the class as final to avoid extending it
2. Create private constructor to avoid creating objects of that class
3. Create getter method to call any variables except constants
4. Make variable as static to use it without creating objects and private along with getter and setters
5. Create BaseTest for drivers setup() and teardown() and extend it with all classes
6. Use Owner for property, Lombak for POJO,AssertJ for assertions,Localdatejoda for date/time,Allure/Extent for reports
7. Always use trim() when reading any string values
8. Create page classes and By return type variables and make it as private final
9. Use method chaining so that we can access the methods in chains instead of calling objects always
10. Use By element so that dynamic xpath can be created which is not possible in pagefactory
11. Avoid using PageFactory may give stale element reference or Null pointer exception
12. Create enums and ExplicitWaitFactory for waits
13. Use Inheritance only if it satisfies IS A relationship and many methods of super class needs to used in subclass
14. Create ThreadLocal for driver instantiation of parallel execution

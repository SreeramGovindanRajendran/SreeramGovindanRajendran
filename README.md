🌱 Automation Code Basics :
Make the class as final to avoid extending it
Create private constructor to avoid creating objects of that class
Create getter method to call any variables except constants
Make variable as static to use it without creating objects and private along with getter and setters
Create page objects in src/main
Keep only tests in src/test
Create BaseTest for drivers setup() and teardown() and extend it with all classes
Use Owner for property,Zerocell for excel,Lombak for POJO,AssertJ for assertions,Localdatejoda for date/time,Allure/Extent for reports
Always use trim() when reading any string values
Create page classes and By return type variables and make it as private final
Use method chaining so that we can access the methods in chains instead of calling objects always
Use By element so that dynamic xpath can be created which is not possible in pagefactory 
PageFactory may give stale element reference or Null pointer exception - so avoid using it
Create enums and ExplicitWaitFactory for waits
Use Inheritance only if it satisfies IS A relationship and many methods of super class needs to used in subclass
Create ThreadLocal for parallel execution

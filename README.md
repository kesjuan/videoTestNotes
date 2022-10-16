# videoTestNotes
// Junit5.org/junit5		
//@BeforeAll will run once before all and is static
// @AfterAll will run after all and is static and is used to tear down methods
// assertThrows tests exception and uses a lambda. (Exception, () -> , “The code that should throw the exception)” // can add customized message string. () -> lambda can be used to specify message to show if test fails
@DisplayName can replace the class name and method name can be used to clarify what the test should do
@Nested can be used to nest tests output 
assertAll can test multiple assertions with lambda //assertAll ( () -> “assertions”)
@Tag targets the tests that match the expression passed in
//Can write tests for methods that haven’t been created yet


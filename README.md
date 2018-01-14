HMRC:: ShoppingCart Requirements

Step 1: Shopping cart

● You are building a checkout system for a shop which only sells apples and oranges.

● Apples cost 60p and oranges cost 25p.

● Build a checkout system which takes a list of items scanned at the till and outputs the total cost

  For example: [ Apple, Apple, Orange, Apple ] => £2.05
  
● Make reasonable assumptions about the inputs to your solution; for example, many candidates take a list of strings as input


Instructions to Use This application:

I have used the following technologies to develop this application:

a) Scala

b) Spec2 for Functional Tests

c) TDD Approach

d) IntelliJ IDEA 14

e) Maven

f) SBT

Please run "uk.gov.hmrc.shoppingcart.ShoppingCartITest" functional tests to verify the ShoppingCart functionality.

$ sbt test

or 

$ sbt "test-only uk.gov.hmrc.shoppingcart.ShoppingCartITest"
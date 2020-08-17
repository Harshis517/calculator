# Addition

Scenario: Add two numbers.
  
  Given I have a calculator that's turned on.

  When I enter "number 1"
  And I press "+" button
  And I enter "number 2"
  And I press "="button
  
  Then I see the "added-sum" as the result.


  


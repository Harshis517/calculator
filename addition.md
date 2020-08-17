# Addition

Scenario: Add two numbers.
  
  Given I have a calculator that's turned on.

  When I enter "number 1"
  And I press "+" button
  And I enter "number 2"
  And I press "="button
  
  Then I see the "added-sum" as the result

Scenario: Add two real numbers.
  
  Given I have calculator that's turned on and the sum will have the same sign as the numbers with the greater absolute value.
  
  When I enter "number 1"
  And I enter "number 2"
  And I press "="button
  
  Then I see the "added-sum" with the sign as the result

  


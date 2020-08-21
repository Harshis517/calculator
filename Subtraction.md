# Subtraction

Scenario: First number is 0.

Given I have a calculator that's turned on.

When I enter "number1"
And I press "-" button
And I enter "number2"
And I press "=" button 

Then I see the "number 2" prefixed by "-"as the result.

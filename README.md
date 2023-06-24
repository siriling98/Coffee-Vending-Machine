<h1> COFFEE VENDING MACHINE ☕ </h1>
<br> 1. Prompt user by asking “What would you like? (espresso/latte/cappuccino):” </br>
<br>  a. Check the user’s input to decide what to do next.</br>
<br>  b. The prompt should show every time action has completed, e.g. once the drink is</br>
<br>     dispensed. The prompt should show again to serve the next customer.</br>
<br> 2. Turn off the Coffee Machine by entering “off” to the prompt.</br>
<br>    a. For maintainers of the coffee machine, they can use “off” as the secret word to turn off</br>
<br>       the machine. Your code should end execution when this happens.</br>
<br> 3. Print report.</br>
<br>    a. When the user enters “report” to the prompt, a report should be generated that shows</br>
<br>       the current resource values. e.g.</br>
<br>       Water: 100ml</br>
<br>       Milk: 50ml</br>
<br>       Coffee: 76g</br>
<br>       Money: $2.5</br>
<br> 4. Check resources sufficient?</br>
<br>    a. When the user chooses a drink, the program should check if there are enough</br>
<br>       resources to make that drink.</br>
<br>    b. E.g. if Latte requires 200ml water but there is only 100ml left in the machine. It should</br>
<br>       not continue to make the drink but print: “Sorry there is not enough water.”</br>
<br>    c. The same should happen if another resource is depleted, e.g. milk or coffee.</br>
<br> 5. Process coins.</br>
<br>    a. If there are sufficient resources to make the drink selected, then the program should</br>
<br>       prompt the user to insert coins.</br>
<br>    b. Remember that quarters = $0.25, dimes = $0.10, nickles = $0.05, pennies = $0.01</br>
<br>    c. Calculate the monetary value of the coins inserted. E.g. 1 quarter, 2 dimes, 1 nickel, 2</br>
<br>       pennies = 0.25 + 0.1 x 2 + 0.05 + 0.01 x 2 = $0.52</br>
<br> 6. Check transaction successful?
<br>    a. Check that the user has inserted enough money to purchase the drink they selected.</br>
<br>       E.g Latte cost $2.50, but they only inserted $0.52 then after counting the coins the</br>
<br>       program should say “Sorry that's not enough money. Money refunded.”.</br>
<br>    b. But if the user has inserted enough money, then the cost of the drink gets added to the</br>
<br>       machine as the profit and this will be reflected the next time “report” is triggered. E.g.</br>
<br>       Water: 100ml</br>
<br>       Milk: 50ml</br>
<br>       Coffee: 76g</br>
<br>       Money: $2.5</br>
<br>    c. If the user has inserted too much money, the machine should offer change.</br>
<br>       E.g. “Here is $2.45 dollars in change.” The change should be rounded to 2 decimal</br>
<br>       places.</br>
<br> 7. Make Coffee.</br>
<br>    a. If the transaction is successful and there are enough resources to make the drink the</br>
<br>       user selected, then the ingredients to make the drink should be deducted from the</br>
<br>       coffee machine resources.</br>
<br>       E.g. report before purchasing latte:</br>
<br>       Water: 300ml</br>
<br>       Milk: 200ml</br>
<br>       Coffee: 100g</br>
<br>       Money: $0</br>
<br>       Report after purchasing latte:</br>
<br>       Water: 100ml</br>
<br>       Milk: 50ml</br>
<br>       Coffee: 76g
<br>       Money: $2.5</br>
<br>   b. Once all resources have been deducted, tell the user “Here is your latte. Enjoy!”. If</br>
<br>      latte was their choice of drink.</br>

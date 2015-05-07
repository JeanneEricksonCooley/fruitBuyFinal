Our site will allow the user to access a market with fruit for sale - apples, oranges, bananas, and pears. The market will be based on a stock-market model, prices fluctuating. The user comes to the fruit market with a certain amount of money to spend. The user will purchase fruits, one at a time. The site will keep track of the users “fruit basket” (inventory of items purchased). Ultimately the user will be able to sell the products they have purchased (ideally at a profit). The game is designed for a single user. The market contains an endless supply of fruit.

Upon opening of the site (located: localhost:63342/fruitBuy/index.html) the user will see:
Pretty fruit market image on the site background
An “Open Market” button, at the top and center of page, that allows the user to initiate the game.
A “Market” section (with a opaque green background) on the left of the page that contains:
images of the specific fruits, with no name labels
a visible buy button, but no prices yet
A “Basket” section (with an opaque blue background) on the right of the page that contains:
names of fruits, with no images
a visible sell button (but no beginning customer inventory to sell yet)
opening tally of user money with label “How much money you have:” The user begins with $50.00

User will open the fruit market by clicking on the “Open Market” button.
prices appear under the images of the fruits, starting at random whole dollar amount between $1.00 and $5.00

Prices of the individual fruits will update every 15 seconds, with or without user interaction.
prices can fluctuate between $.50 and $9.99
prices listed with dollars and cents

The user can purchase a fruit at any time, at the price listed at the time, by initiating with a mouse click on the “Buy” button.
the purchase will be deduct from the user’s money in the “How much money you have:” section
If the user does not have enough money, an alert will be prompted saying “you do not have enough money"
Labels appear in individual fruit sections of “Basket"
A “Quantity” label will appear under the purchased fruit with a quantity of “1.” This will be updated as additional purchases are made of this same fruit.
An “Average Price” label will appear under the purchased fruit with the price of the first purchase being reflected. Each additional purchase will refactor this amount to reflect the average price paid for this particular fruit.

Once the user has bought fruit (even just one piece), they can use the sell function with a mouse click on the button labeled “Sell."
the sale price is the price reflected in the “Market” section under the fruit images. Users can, in effect, sell the individual pieces of fruit at a profit
the “Quantity” and “Average Price” displays will be updated to reflect the sale.
if this was a sale of the last fruit in a category, “Quantity” and “Average Price” labels will remain, but with values of “0” and “$0,” respectively
the users money will increase based on the amount in which they sold the fruit

The game will continue endlessly as long as the user keeps the display window open. All information will be lost upon window closure. The user does not have an option to save their game.
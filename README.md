# cs1570-homework-8-card-wars-solved
**TO GET THIS SOLUTION VISIT:** [CS1570 Homework 8-Card Wars Solved](https://www.ankitcodinghub.com/product/cs1570-homework-8-card-wars-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;101961&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;1&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (1 vote)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS1570 Homework 8-Card Wars Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (1 vote)    </div>
    </div>
<div class="page" title="Page 1">
<div class="section">
<div class="layoutArea">
<div class="column">
Card Wars

Background

You are the ruler of a very small country with incredibly odd laws. For the past four years you have had a very successful reign. However, one of the unchangeable laws of your country of Fifteenseventystan is that the position of ruler can be taken by anyone who beats the current ruler at a game of war. Today, you have been challenged by a young adventurer covered in slime, for some reason. In order to keep your position, you must beat him at war.

Modified Game Rules

War is a simple two-person card game. Each player receives half of the deck. Each player will then flip over one card at a time. Whoever has the higher valued card will then receive both cards, and place them at the bottom of their deck. If the values of both cards are the same, both cards will be destroyed and removed from the game forever. This will continue until a player has equal to or less than 10 cards remaining in their deck. When this happens, the other player will be announced the winner.

</div>
</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="section">
<div class="layoutArea">
<div class="column">
The card values are, in ascending order, 2-3-4-5-6-7-8-9-10-J-Q-K-A. Each card will also have a suit, either clubs, hearts, diamonds, or spades. Therefore, the full deck has a total of 52 cards. Specifications for how cards are ranked will be stated later in the assignment description.

Specifications

For this assignment, you are going to create several classes.

The card class (used to store the value of a single playing card) Private members:

A character to represent the cards value (2,3,4,5,6,7,8,9,J,Q,K,orA)

A character to represent the suit (H for heart, C for club, S for spade, and D for diamond)

A boolean to represent whether or not

the card has been destroyed. Public members:

A default constructor should be made

available that does nothing. This is simply put in place to guarantee a successful compilation of the program.

A parameterized constructor should be made available to take in both the card’s value and its suit.

Overloaded + operator: The + operator should be overloaded within this class. When two cards are added together, it should return an integer which is the sum of the values of the 2 cards. For purposes of this function, count J,Q,K, and A as having a value of 10. For example, if you added the 7 of clubs and the queen of diamonds together, it should return a 17. If the sum of two cards is 11, both cards should be destroyed.

Overloaded &gt; and &lt; operators: These operators should be overloaded to compare the value of two cards. CardA&gt;CardB should return true if card A is greater than card B, and false if otherwise. Similarly, CardA&lt;CardB should return false if card A is greater than card B, and true if otherwise. How cards are compared are as follows:

If the two cards have different suits, then the card with the higher value is greater. The only exception to this is when the cards’ values are 2 and A, in which case the value 2 will be considered the greater card.

If the two cards have the same suit, then the card with the lower value is greater. The only exception to this is when the cards’ values are 2 and A, in which case the value A will be considered the greater card.

</div>
</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="section">
<div class="layoutArea">
<div class="column">
Overloaded == and != operators: This operator should compare two cards. The == operator overload should return true if the two cards have the same value, and false if otherwise. Similarly, the != operator should return false if the two cards have the same value, and true if otherwise. Overloaded ~ operator: This operator should destroy the card forever. Overloaded insertion operator (&lt;&lt;): This operator should return an ostream object by reference. It must output the card’s value, followed by its suit. For example, the 7 of clubs would be output as 7C.

The Deck class (used to represent a deck of cards) Public members:

A default constructor should be made to populate the deck with all 52 cards.

A parameterized constructor should be made

available to take in an array of cards, and an

integer representing the size of the array of cards. The deck should be set equal to the card array.

A shuffle function: This function should randomize the position of all of the cards within the card array.

A getCard function: This function should take

an integer parameter as the index. It should

return the card within the card array at that index position.

Private members:

An array of at most 52 card objects.

An integer to represent how many cards are actually in the deck.

Overall Program Flow

<ol>
<li>Create a deck of 52 cards with your default constructor.</li>
<li>Shuffle the deck.</li>
<li>Create two arrays of cards, one which contains the first 26 cards in the deck you just
created, and one which contains the remaining 26 cards in the deck you just created.
</li>
<li>Create two more decks of cards, setting the cards they contain equal to the arrays you
created in step 3.
</li>
<li>Compare the cards in each of your 2 decks one by one, starting from the beginning of
the cardArray, and ending at the end. When you hit the end of either player’s card

array, start again from the beginning of the card array.
</li>
<li>If a card is destroyed, leave it in place in the array, and decrement the number of cards
in that deck by 1.
</li>
</ol>
</div>
</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="section">
<div class="layoutArea">
<div class="column">
<ol start="7">
<li>If a card that has been selected has already been destroyed, simply move on to the next card in that player’s array. Do not move onto the next card in the other players array unless it has also been destroyed.</li>
<li>This process should repeat until a player has 10 or fewer cards. When this happens, announce that the game is over, and announce the winner.</li>
</ol>
Notes

<ul>
<li>● &nbsp;Set the random seed for this assignment to be 469.</li>
<li>● &nbsp;It is recommended that each class definition goes in their own header file.</li>
<li>● &nbsp;You may define additional functions to be used to improve the program’s organization.
This includes global functions and member functions for the classes as well.
</li>
<li>● &nbsp;You may use functions from existing libraries if 1) they are explicitly stated in the assignmentor2) theusageofthelibraryfunctionshasbeenthoroughlyintroducedin class. Otherwise, the usage of functions from existing libraries is prohibited without
the permission of your instructor.
</li>
<li>● &nbsp;If the parameters and return type of a function is not specified, then it is your
responsibility to determine the most appropriate function signature.

Sample Outputs

Sample outputs regarding the format are provided below for your reference, i.e. the data values used in the output might be completely made up. Your actual program output does not have to match the sample exactly. Make sure that yours is nicely formatted and is readable to anyone.

Sample Output

This is war!

Input defender name:

Julian

Input attacker name:

Normo

Battle commence!

//Sample Output Coming Soon

–Game over–

Congratulations Normo, you have won! Enjoy your new country!
</li>
</ul>
</div>
</div>
</div>
</div>

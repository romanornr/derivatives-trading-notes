### option price components 

An option's premium is always composed of
* *-> intrinsic value
* -> time values<br>

The intrinsic value will be the difference between
* -> the buying price and the selling price of the [[options]] if it exercises immediately
Reference: [[exercise and assignment]]
<br>
<p>Time value</p>
* -> is the amount of premium beyond the intrinsic value that traders are willing to pay for an option.<br>
<p>An option's price in the marketplace will be greater than its intrinsic value.</p>

<p>As in any competitive market, an option's price, or premium, is set by how many people are willing to buy and sell it.</p>

<p>Buyers and sellers compete with each other in the market.
When a bid and an offer match, a trade is made.
The price you pay for an option can be broken down into two parts: intrinsic value and time values

You can buy low and sell high with an option that has intrinsic value. The intrinsic value is the difference between the price you pay and the price you get.</p>

If the [[exercise price]] of a call is less than the current market price of the [[underlying]] contract
<ul>
<li>-> then the call has intrinsic value</li>
<li>-> No one would want to buy high and sell low, so no one would buy a call.</li>
<li>-> Only a put with a higher [[exercise price]] will be intrinsic because no one would want to sell low and buy high.</li>
</ul>
<p>An intrinsic value is a difference between the amount of money you pay for a call and how much money you get for a put.</p>

No option can have an intrinsic value that is less than 0.

```S = spot price of the underlying contract```
```X = exercise price```

```
Call intrinsic value = maximum of either 0 or S – X.
Put intrinsic value = maximum of either 0 or X – S.
```
<br>
It is important to note that the intrinsic value is not affected by when the money is due to run out.
* *-> With [[underlying]] contract at $83
* *-> a March 70 call and a September 70 [[call option]] both have an intrinsic value of $13.
* *-> A June 90 put and December 90 put both have an intrinsic value of $7
<br>
<p>Most of the time.</p>
* -> an option's price in the market will be higher than its intrinsic value

Options have a "time value".
* -> Can also be called their "time premium" or "extrinsic value."

It is the extra money that traders will pay for them over and above the option's intrinsic value.

People are willing to pay this extra money.
* -> Because an option gives them more protection than an outright long or short position in the underlying contract.</p>


Examples of intrinsic value and time value 
<ul>
<li>if a call option with a $400 strike price</li>
<li>is trading at $50</li>
<li>with the underlying trading at $435</li>
<li>The time value of the call must be $15</li>
<li>because the intrinsic value is $35 (435-400 = 35)</li>
</ul>


<p>The two parts of the option's price must add up to $50.</p>
<ul>
<li>-> $70 put on a stock</li>
<li>-> trading for $11 with the stock trading at $62</li>
<li>-> the time value of the put option must be $3</li>
<li>-> because the intrinsic value is $8</li>
<li>-> the intrinsic value and the time value must add up to the option’s premium ($11)</li>
</ul>

![[Intrinsic value and time value.png]]

<p>So option premiums always include both intrinsic value and time value</p>
* -> but one or both of these can be zero at the same time.

If the option does not have any intrinsic value.
* its price in the market will only be based on how long it will be before it expires

If the option has no time value.
* -> its price will only be based on its intrinsic value. 

In this case, traders say that the option is trading at the same price as the stock.

The intrinsic value of an option can never be less than zero.
* -> but it is possible for a European option ([[exercise style]]) to have a time value that is less than zero.

<p>During this time, the option can trade at a lower price than its par value. Most of the time, however, an option's price will reflect some non-negative amount of time value.</p>

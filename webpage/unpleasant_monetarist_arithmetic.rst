.. _unpleasant_monetarist_arithmetic:

================================
Unpleasant Monetarist Arithmetic
================================

Recall that in the Government Budget Constraint lecture, we derived an expression
for real seignorage revenue.  In that lecture, we assumed that real money demand was only 
a function of real income and that real income
was constant.  But clearly, income is rarely constant, and the demand for money most likely depends 
on other factors than just income.  

In this lecture, we first want to present a richer theory of money demand.

Second, we will discuss how the quantity of revenue the government can collect from seignorage can increase
or decrease as the inflation rate rises.

Third, we will return to the government budget constraint to illustrate how if a fiscal
authority runs persistent deficits, then low inflation today can mean high inflation in the future.  
This "unpleasant" result was first brought to light in [SargentWallace1981]_ .

A More Complete Description of Money Demand
===========================================

One of money's three primary functions is to serve as a store of value. Of course, there 
are many other assets that can serve as a store of value as well: stocks, bonds, houses, ...
It is natural
to assume that people will want spread their wealth across several types of assets rather than
hold all their wealth in a single asset.

Thus how much of a person's wealth he or she will want to store in money will be part of 
a larger portfolio allocation.  
 
People generally care about three things when deciding how to
allocate their wealth among various assets.

       1. the asset's expected return
 
       2. the riskiness of the asset's return
 
       3. the liquidity of the asset

We will go through each of these factors individually.

The expected return on money
----------------------------

What is the opportunity cost of holding money?  In other words,
suppose you decide, on average, to keep \$100 in your wallet.  What
are you giving up?


   1. real return you would have received by holding  your
      wealth in some other form.

   2. devaluation of money in pocket due to inflation.

Alternatively, one can simply think of the cost in nominal terms.

    * If I keep \$100 in my wallet, at the end of a year I have \$100.

    * If I lend the \$100 for one year, at the end of a year I have :math:`\$100 \times(1+R)`.

    * Cost (per dollar) of holding money equals :math:`R`.

* Makes sense since we know :math:`R \approx r + \pi`.

Risk
----

Risk is the degree of uncertainty in an asset's return.

People don't like risk.

Currency is not a risk free asset. Currency crises make this point.

The rate of inflation, devaluations are all uncertain.

Liquidity
---------

Liquidity is the ease and quickness with which an asset can be traded. People tend to like liquidity.

Some assets like houses are very illiquid; that is, they may be hard to 
sell quickly.

Other assets such as stocks traded on the New York Stock Exchange are very liquid; they 
are easy to sell quickly.

It is hard to think of an asset that is more liquid than U.S. dollars.  In the U.S. every 
cashier is willing to accept dollars in return for providing a good or service.

In summary,

    *money has a low rate of return, can at time be very risky, but is very liquid.*

Macroeconomic factors that affect money demand
----------------------------------------------

There are also macroeconomic factors that affect money demand

   * Real Income (or real GDP) :math:`Y`

   * The price level, :math:`P`

The money demand function
-------------------------

The demand function for *nominal money balances*:

.. math::

     M^d = P \Phi(Y,R) = P \Phi(Y,r+\pi).  
     
where

.. math::

     M^d  &=& \mbox{nominal aggregate money demand} \\
     P    &=& \mbox{price level} \\
     \Phi    &=& \mbox{real money demand function} \\
     Y    &=& \mbox{real income or output} \\
     R    &=& \mbox{nominal interest rate of non-monetary assets} \\
     r    &=& \mbox{real interest rate of non-monetary assets} \\
     \pi &=& \mbox{inflation rate}

In this specification we assume that nominal money demand is proportional to the price level.  That is, if
the price level rises by 10 percent then households and firms will need 10 percent more money to carry about 
the same number of transactions.

We also assume that an increase in income, :math:`Y`, increases money demand.

Finally we assume that an increase in the nominal return of non-monetary assets, :math:`R`, reduces money demand.

We can also talk about *real money balances*:

.. math::
    {{M^d}\over{P}} = \Phi(Y,R) 

The function :math:`\Phi` expresses how much money the economy is
willing to hold in terms of real  :math:`\Phi(Y,R)` is how many "market
baskets" worth of money the economy is willing to hold.

The Inflation Tax
=================

Recall that in the Government Budget Constraint lecture, we derived the following expression
for real seignorage revenue

.. math::

    \frac{M_{t} - M_{t-1}}{P_t}  = \frac{\mu}{1+\mu} \frac{M_{t-1}}{P_{t-1}} 
    
where :math:`\mu` was the money growth rate and :math:`\Phi` denoted the demand for real money balances.    

Recall that under the quantity theory of money, the inflation rate, :math:`\pi` will equal the money growth 
rate, :math:`\mu`.

Using our richer description of money demand

.. math::

    \frac{M_{t} - M_{t-1}}{P_t}  = \frac{\pi}{1+\pi} \Phi(Y,r+\pi) 

We see that as the inflation rate increases

   1.  the "tax rate" :math:`\frac{\pi}{1+\pi}` increases, but 
   2.  the demand for real money balances :math:`\Phi(Y,r+\pi)` decreases.
   
So will an increase in the inflation rate cause seignorage revenue to increase or decrease?  Well, it 
depends whether the tax rate increases more or less than the demand for real money balances decreases.

When we look at the data, we typically find that at low rates of inflation, seignorage revenue
is an increasing function of the inflation rate.  But as the inflation rate grows, the demand for
real money balances  falls dramatically as consumers and firms actively substitute other 
assets (often other currencies) to use as a store of value.  Hence there is a maximum value of 
seignorage revenue that a government can hope to raise.

.. figure:: _static/figures/seignorage.png
    :scale: 60%
    :align: center

    **Revenue from Seignorage as a Function of the Money Growth Rate**

In the above figure we plot seignorage revenue :math:`\frac{\mu}{1+\mu} \Phi(Y,r+\mu)` 
as a function of :math:`\mu`.
This relationship with tax revenue and the tax rate is known as a *Laffer curve*.  
When money growth rate is
zero, inflation is zero and the revenue generated from seignorage is zero.

If we increase the money growth rate, seignorage revenue increases but less than one-for-one.  As the 
money growth rate, and thus 
the inflation rate, increases, real money demand falls. As the rate of return on money decreases, people 
wish to hold a smaller share of their wealth in money, shifting more of their wealth into other 
assets such as stocks and foreign currencies.

If the money growth rate becomes sufficiently large, money demand falls faster than the increase in the 
inflation rate.  On the right hand side of the Laffer curve, higher money growth rates generate 
*less* not more seignorage revenue.  In the data, the inflection point is 
often around an inflation rate of about 30 percent.  

Robert Barro ([Barro2009]_, page 210) writes

.. epigraph::

   In normal times for most countries, the government obtains only a small portion of
   its revenue from printing money.  In 2005, the Federal Reserve obtained \$24 billion 
   from this source.  This amount constituted 1.1\% of total federal receipts and 0.2\%
   of GDP.  These figures are typical for most developed countries
   
   In a few high inflation countries, the reenue from printing money became more more 
   important.  For example, in Argentina from 1960 to 1975, money creation accounted
   for nearly half of government revenue and about 6\% of GDP.  Some other countries 
   in which revenue from printing money was important were Chile (5\% of GDP from 1960 
   to 1977), Libya (3\% of GDP from 1960 to 1977), and Brazil (3\% of GDP from 1960 to 
   1978).
   
   :math:`\vdots`
   
   In some hyperinflations, the revenue approached 10% of GDP, which seems to be about 
   the maximum attainable from printing money.
    
Budget Constraint Arithmetic
============================

Consider a sequence of government budget constraint beginning at an initial date, time 1.

.. math::

     B_{1}  &=&  (1+r) B_{0} + G_1 - T_1 - \frac{M_1 - M_{0}}{P_1} \\
     B_{2}  &=&  (1+r) B_{1} + G_2 - T_2 - \frac{M_2 - M_{1}}{P_2} \\
     B_{3}  &=&  (1+r) B_{2} + G_3 - T_3 - \frac{M_3 - M_{2}}{P_3} \\
     \vdots 

We can rewrite this third equation as:

.. math::

     B_2 = \frac{1}{1+r} \left( B_3 - G_3 + T_3 + \frac{M_3 - M_2}{P_3} \right). 
  
Substituting this expression for :math:`B_2` into the second 
equation yields:

.. math::
 
     \frac{1}{1+r} \left( B_3 - G_3 + T_3 + \frac{M_3 - M_2}{P_3} \right) = (1+r) B_{1} + G_2 - T_2  - \frac{M_2 - M_{1}}{P_2}.

Re-arranging terms, we get

.. math::

    G_2 - T_2 + \frac{G_3 - T_3}{1+r} + (1+r)B_1 - \frac{B_3}{1+r} =  \frac{M_2 - M_{1}}{P_2} + \frac{1}{1+r} \frac{M_3 - M_{2}}{P_3}. 

If we repeat this recursive substitution an infinite number of times, we get

.. math::

    \sum_{t=2}^{\infty} \left(\frac{1}{1+r}\right)^{t-1} (G_t - T_t) + (1+r)B_1  = \sum_{t=2}^{\infty} \left(\frac{1}{1+r}\right)^{t-1} \frac{M_t - M_{t-1}}{P_t}

This expression states that the discounted present value of the stream of government deficits 
from period 2 onward plus the initial 
value of the debt equals
the discounted present value of the stream of seignorage revenue. 

Let's rewrite this as

.. math::

    \sum_{t=2}^{\infty} \left(\frac{1}{1+r}\right)^{t-1} (G_t - T_t) + (1+r)B_1  = \sum_{t=2}^{\infty} \left(\frac{1}{1+r}\right)^{t-1} \frac{\mu}{1+\mu} \Phi(Y,r+\mu).

Consider this the *long-run* budget constraint.

Then recall we still have the first period budget constraint

.. math::

     B_{1}  =  (1+r) B_{0} + G_1 - T_1   \frac{M_1 - M_{0}}{P_1}.

Consider this the *short-run* budget constraint.

Now suppose that the government keeps spending, taxes, debt and the money growth rate 
fixed from period 2 on.  In equations, we state, for :math:`t \ge 2` set

.. math::

      G_t &=& G \\
      T_t &=& T \\
      B_t &=& B \\
      \frac{M_t}{M_{t-1}} &=& 1+\mu.
 
In this case, we can write the long run budget constraint as;
 
.. math::
    \frac{G - T}{1 - \frac{1}{1+r}}  + (1+r)B  = \frac{\frac{\mu}{1+\mu} \Phi(Y,r+\mu)}{1 - \frac{1}{1+r}}.

We can simply this expression to

.. math::
  G - T + rB = \frac{\mu}{1+\mu}\Phi(Y,r+\mu).
  
This expression just states that each period the deficit must equal the seignorage revenue.  

In the figure below we plot the left hand side and the right side of the equation for different values of
the money growth rate :math:`\mu`.  Since the left hand side (i.e. the deficit) does not depend on 
the money grwoth rate, it is a 
horizontal line.  We plot it in red.  The right hand side is the seignorage revenue.  It does depend on 
:math:`\mu`.  We plot it in blue.  It is the Lafer curve that we plotted in the previous figure.

There line cross twice. Once at a low money growth rate.  Once at a high money growth rate.  Focus on the
lower intersection. This intersection determines the money growth rate the monetary authority must run in 
order to cover the fiscal deficits.

.. figure:: _static/figures/equilibrium1.png
    :scale: 60%
    :align: center

    **Determining the Rate of Money Growth so that the Government Budget Constraint Holds**


Monetarist Arithmetic
=====================

Assume that the current fiscal and monetary authoroties are handed intial conditions :math:`B_0` and :math:`M_0`

The fiscal authority sets  :math:`G_0` :math:`G`  :math:`T_0` and :math:`T`
  
The monetary authority conducts monetary policy by trading bonds for money (i.e. open market operations).
 
In equilibrium, the initial price level, :math:`P_0` and real money demand :math:`\Phi(Y,r+\mu)` adjust 
so that the budget constraints hold.

Suppose the goal of the monetary authority is a lower price level, :math:`P_0`.  How should monetary
policy be conducted?

Decrease the money supply.  That means selling bonds.  So :math:`M_1` goes down and :math:`B` goes up.

But note that if government debt rise, then so does the long-run interest payments on the debt :math:`r B`.  
If the fiscal authority keeps spending :math:`G` and taxes :math:`T` fixed, the monetary authority will
be forced to cover the larger deficit by increasing seignorage revenue.   

.. figure:: _static/figures/equilibrium2.png
    :scale: 60%
    :align: center

    **The Effect of an Increase in Bonds on Future Money Growth**

In other words, exchanging  "zero-interest" money for interest-bearing debt increase future interest payments.  
If spending or taxes do not adjust to pay for these higher interest costs, future seignorage revenue must 
be increased.

Hence, by reducing the money supply today, the monetary is causing higher inflation in the future.  This
result is known as *unpleasant monetarist arithmetic*.

One Step Further
----------------

We can extend the analysis one step further and show that an open market operation 
that *reduces* the money supply
could have the perverse result of *increasing* the price level, if the drop 
in real money balances 
is sufficiently large.

While theoretically possible, this result is a special case and we are not going 
to appeal to this case in future lectures.  So we will not cover
it here. If you would like to learn more about this case, see section 26.3.4 on pages 1055-1056 
of [LjungqvistSargent2012]_. 

                        
                         
Exercises
---------

1. Assume the demand for real money balances is

.. math::
 
    \frac{M}{P} = 100*e^{-0.9*\pi}
 
where :math:`\pi` is the inflation rate.
 
For inflation rates of :math:`0`, :math:`10\%`, :math:`20\%`, :math:`30\%`, :math:`40\%`, 
:math:`50\%`, :math:`60\%`, :math:`70\%`, :math:`80\%`  and :math:`90\%`
compute real money demand and seigniorage.

What is the revenue maximizing inflation rate?


2. **Without Assistance from the Fiscal Authority, Low Inflation Today Means High Inflation in the Future**

Consider a country in which the fiscal authority is hopelessly deadlocked.  Taxes are fixed at 90 and government 
spending is fixed 100.  These values will last forever.  All units of account are denominated in Shamolians.

In this country, the quantity theory of money holds and velocity is constant.  Since output is 
also constant, demand for money balances is fixed at 200.  The central bank sets the growth rate of 
nominal money, :math:`\mu`, so the nominal money supply follows

.. math::
 
       M_t = (1+\mu) M_{t-1}.

Since velocity and output are fixed, in equilibrium the inflation rate, :math:`\pi` equals 
the growth rate of money :math:`\mu`.

The government budget constraint is

.. math::

      B_t = B_{t-1} + r B_{t-1} + G_t - T_t - \left(\frac{\pi_t}{1+\pi_t}\right) \frac{M_{t-1}}{P_{t-1}}.

Assume :math:`r` equals 6 percent.  The interest rate and government debt are real 
(i.e. they cannot be inflated away). The budget arithmetic for 50 periods is set up 
for you in the EXCEL spreadsheet PS3.xls.  For each case, suppose the country starts 
with zero debt.


   a. What money growth rate (i.e. inflation rate) will the country need to run if it 
      wants to keep debt fixed at zero forever?  (You can use the Excel solver or just 
      find the money growth rate via trial and error.)


   b. Suppose the country's central bank wishes to keep inflation low, so it sets the 
      money growth rate to 0 for the first five periods. Starting in period 6, the 
      central bank sets the money growth rate to keep the debt from rising any further. 
      What is the inflation rate from period 6 on ...?


   c. Suppose the country's central bank is REALLY TOUGH and commits itself to setting 
      the money growth rate to 0 "forever".  However, when government debt reaches three 
      times the levels of tax revenue, lenders refuse to extend to the government any 
      further credit.  The fiscal authority still refuses to cut spending or increase 
      taxes.  At this point, what money growth rate will the central bank be forced to 
      set if it does not want to default on the debt and keep :math:`B \le 3 \times T`?

3. **Fiscal and Monetary Policy**

A country called :math:`X` has been experiencing rapid inflation.  Table 1 displays the 
fiscal condition in the form of
steady state values of government expenditures :math:`G`, tax collections :math:`T`, and 
real value of government debt :math:`B`.
The gross real rate of return on interest-bearing government debt is :math:`1+r`.  Table 2 
displays the monetary conditions in
terms of the public's demand for real balances of government issued money :math:`\Phi(Y,r+\mu)`.  
Here :math:`\mu` is
the stationary net growth rate of the nominal money supply, namely, 

.. math::
    M_t = (1+\mu)M_{t-1}, 
    
where :math:`M_t` is the nominal money supply at time :math:`t`.

 The unit of time is one year and all quantities are expressed as fraction of GDP per year.

+----------+----------+----------+----------+----------+-----------------+---------------+
|    Budget Worksheet                                                                    |
+----------+----------+----------+----------+----------+-----------------+---------------+
| G        |     T    |   B      |   1+r    |   rB     | primary deficit | total deficit |  
+----------+----------+----------+----------+----------+-----------------+---------------+
| 0.22     |  0.21    |   0.4    |   1.10   |          |                 |               |
+----------+----------+----------+----------+----------+-----------------+---------------+

             **Table 1: Fiscal Worksheet**


+----------------------+---------------+----------------------------+----------------------------------------+
|  Money Demand                                                                                              |
+----------------------+---------------+----------------------------+----------------------------------------+
|        tax base      |  money growth |                  tax rate  |          seignorage                    |
+----------------------+---------------+----------------------------+----------------------------------------+
|:math:`\Phi(Y,r+\mu)` |  :math:`\mu`  |  :math:`\frac{\mu}{1+\mu}` | :math:`\frac{\mu}{1+\mu}\Phi(Y,r+\mu)` |
+----------------------+---------------+----------------------------+----------------------------------------+
| 0.25                 |  0            |                            |                                        |
+----------------------+---------------+----------------------------+----------------------------------------+
| 0.15                 |  1/3          |                            |                                        |   
+----------------------+---------------+----------------------------+----------------------------------------+
| 0.1                  |    1.00       |                            |                                        |
+----------------------+---------------+----------------------------+----------------------------------------+
| 0.05                 |   3.00        |                            |                                        |    
+----------------------+---------------+----------------------------+----------------------------------------+

               **Table 2: Monetary Worksheet**

     a. Please fill in the empty cells in the federal budget worksheet.

     b. Please fill in the empty cells in the monetary worksheet.

     c. With these fiscal and monetary fundamentals, please tell what country X's rate 
        of inflation is.

     d. Please describe the monetary and fiscal adjustments, if any that country X should 
        implement if it wants to eradicate inflation.

     e. A new central banker has just been appointed who has promised permanently to eradicate 
        inflation within a year.  She promises to do so by using open market operations.  It is 
        within her power to execute open market operations (exchanges of currency for interest 
        bearing bonds).
    
        Please write a one-paragraph memo to this central banker advising her about her promised 
        policy and its prospects for success.



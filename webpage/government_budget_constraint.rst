.. _ government_budget_constraint:

*********************************
The Government Budget Constraint
*********************************

Your Credit Card Bill
=====================

If you have a credit card, you get a bill each month.

Your balance this month is

.. math::
        \mbox{Balance this month}  &=&  \mbox{Balance last month} \\
        && \; + \; \mbox{ Finance Charge} \\
        && \; + \; \mbox{ New Purchases} \\
        && \; - \; \mbox{ Payments}
        :label: credit_card_lom

Let's re-write this as

.. math::
        B_t  =  B_{t-1} + r B_{t-1} + G_t - T_t

where we let 

* :math:`B` denote the balance, 

* :math:`r` denote the monthly interest rate (so :math:`rB` is the finance charge), 

* :math:`G` be new purchases, and 

* :math:`T` be payments.

Stock Variables and Flow Variables
==================================


*Stock variables* are measured at a point in time.

*Flow variables* are measured over a period of time.

So for your credit card

* :math:`B` is a stock variable, and  

* :math:`r B`,  :math:`G`, and :math:`T` are flow variables.


The Government Budget Constraint
================================

A sovereign government faces a budget constraint that
must hold at each period, :math:`t`:

.. math::
        B_{t} =  B_{t-1} + r B_{t-1} + G_t + TR_t - T_t

where

.. math::
   G_t  &=& \mbox{government spending during period } t \\
   TR_t &=& \mbox{transfer payments (e.g. social security) during period } t \\
   T_t &=& \mbox{taxes collected during period } t \\
   B_{t}  &=& \mbox{this period's } t \mbox{ government debt} \\
   r  &=& \mbox{real interest rate}

Many macro textbooks write it this way

.. math::
     B_{t} =  B_{t-1} + INT_t + G_t + TR_t - T_t

Fiscal Data: Federal Government
===============================

* Prior to 1790

  * constructed accounts from various reports

* 1790-present

   * U.S. Treasury (1790-1940)

   * Office of Management and Budget (1934-present)

* 1929-present

   * National Income and Product Accounts (NIPA)

NIPA vs Treasury/OMB
====================

* NIPA

  * calendar year/quarter, 1929-present

  * consistent accounting with state/local as well as GDP

  * main spending categories

     * Government consumption, :math:`G_t`

     * Transfer payments, :math:`TR_t`

     * Net interest payments, :math:`INT_t`

* Treasury/OMB

  * fiscal year

  * spending divided by function

      * pre-1940: war, navy, pensions, indians, interest, ...

      * 1934-present: national defense, human resources, physical resources, net interest, ...

Comparison Between Federal and State \& Local
=============================================

* Combined U.S. federal, state, and local government together.

   * spending well over 1/3 of GDP.

*  Current composition of the federal government budget is quite different from state and local budgets.

   * One often hears

     *The federal government is a gigantic insurance company 
     with a side business in defense.*

* State and local governments more directly involved in government purchases

NIPA: Total Government Receipts and Expenditures as a Percent of GDP
====================================================================

.. figure:: _static/figures/all_gov_rec_exp.png
    :scale: 60%
    
NIPA: Total Government Expenditures Decomposed By Type
======================================================

.. figure:: _static/figures/all_gov_exp_decomp.png
    :scale: 60%

NIPA: Federal Expenditures Decomposed By Type
=============================================

.. figure:: _static/figures/fed_gov_exp_decomp.png
    :scale: 60%


NIPA: State and Local Expenditures Decomposed By Type
=====================================================

.. figure:: _static/figures/sl_gov_exp_decomp.png
    :scale: 60%

1790-1940: Federal Government Expenditures Decomposed By Type
=============================================================

.. figure:: _static/figures/fed_expend_decomp_1776_1940.png
    :scale: 60%

OMB: Federal Government Expenditures Decomposed By Type
=======================================================

.. figure:: _static/figures/federal_expend_decomp_1940_2011.png
    :scale: 60%

OMB: Medicare and Social Security Spending
==========================================

.. figure:: _static/figures/Med_SS_per_GDP.png
    :scale: 60%


Revenue Side
============

NIPA: Six principal categories

#. Personal taxes:

  * Personal income taxes

2. Taxes on production and imports

  * sales taxes

  * property taxes
   
  * customs
 
3. Taxes on corporate income

4. Contributions for Social Insurance

  * Social Security

5. Transfers

6. Other

  * income on assets and government enterprises

Revenue: Federal vs. State/Local
================================

* Federal government

  * Income taxes

  * Contributions for social insurance

* State/Local

  * property and sales taxes

  * transfers from the federal government

* Compositional changes for federal government over time

  * customs to internal revenue (income taxes)

Deficits and Surpluses
======================

The budget deficit that gets reported in the newspaper is

.. math::
  G_t + TR_t + INT_t - T_t

When this number is positive there is a budget deficit.

When this number is negative there is a budget surplus.

Change in the debt is equal to the deficit

.. math::
  B_{t} - B_{t-1}  =  INT_t + G_t + TR_t - T_t

The *net-of-interest deficit* or *primary deficit* is 

.. math::
  G_t + TR_t - T_t

The total or gross deficit tells the amount the government must borrow to
cover all of its expenditures.

The primary deficit ignores interest payments

The Printing Press
======================

Since the signing of the U.S. Constitution, the Federal government can raise revenue by issuing money.

   State and local governments can not.

For the Federal government

.. math::
  B_{t}  =  B_{t-1} + r B_{t-1} + G_t + TR_t - T_t  - \frac{M_t - M_{t-1}}{P_t}

where

.. math::
    M_{t}-M_{t-1} &=& \mbox{New money printed this period.} \\
    P_t           &=& \mbox{Price level this period ($t$)} \\
    & & \mbox{i.e. the relative price of money in terms of goods}

This additional term is called {\em seignorage} or the inflation tax.

So the government budget constraint becomes

.. math::
    B_{t}  &=&  B_{t-1} + r B_{t-1} + G_t + TR_t - T_t  - \frac{M_t - M_{t-1}}{P_t}

Write it as

.. math::
    B_{t}  -  B_{t-1} + \frac{M_t - M_{t-1}}{P_t}  =  r B_{t-1} + G_t + TR_t - T_t

Decisions about :math:`G_t`, :math:`TR_t` and :math:`T_t` are called *fiscal policy*

Decision about :math:`B_t` and :math`M_t` are called *monetary policy*.

Debt-to-GDP Ratio
=================

Suppose the credit card balance is :math:`\$20,000`.  Is this a big balance?

* Well it depends

  * If your annual income is :math:`\$15,000`, then yes.

  * If your annual income is :math:`\$1,500,000`, then no.

* It also depends on how fast your income is growing.

So we might be interested in the ratio of debt-to-income.  Let's call income :math:`Y`, and the ratio of
debt-to-income :math:`\frac{B}{Y}`.

A Digression on the U.S. Debt
=============================

See the `U.S. Treasury Monthly Statement of the Public Debt
<http://www.savingsbonds.gov/govt/reports/pd/mspd/mspd.htm>`_.

* Marketable Debt

  * Treasury bills, notes, and bonds

  * can be bought and sold on secondary markets

* Non-marketable Debt

  * no secondary market -- saving bonds,  state and local governments

* Held by the Public

  * you, me, China

* Held inside the government

  * Social Security Trust Fund

Ignore seignorage for now, set :math:`TR = 0`.

.. math::
   B_{t}  &=&  B_{t-1} + r B_{t-1} + G_t - T_t \\
   &=&  (1+r) B_{t-1} + G_t - T_t

Divide both sides of the equation by current income :math:`Y_t`

.. math::
    \frac{B_{t}}{Y_t}  &=&  (1+r) \frac{B_{t-1}}{Y_t} + \frac{G_t - T_t}{Y_t} \\
    &=&  (1+r) \frac{B_{t-1}}{Y_t}\frac{Y_{t-1}}{Y_{t-1}} + \frac{G_t - T_t}{Y_t} \\
    &=&  (1+r) \frac{B_{t-1}}{Y_{t-1}}\frac{Y_{t-1}}{Y_{t}} + \frac{G_t - T_t}{Y_t}

Let :math:`g` denote the percentage change in :math:`Y`

.. math::
   g = \frac{Y_t}{Y_{t-1}} - 1

so

.. math::
   \frac{Y_{t-1}}{Y_t} = \frac{1}{1+g}

So we can write

.. math::
    \frac{B_{t}}{Y_t} &=&  \frac{(1+r)}{(1+g)} \frac{B_{t-1}}{Y_{t-1}} + \frac{G_t - T_t}{Y_t} \\
    &\approx&  (1+r-g) \frac{B_{t-1}}{Y_{t-1}} + \frac{G_t - T_t}{Y_t} \\

To keep the math simple, assume :math:`G` and :math:`T` grow at rate :math:`g`.

Most countries have positive debt-to-GDP ratios.  In the short-term, it is often no big deal if this ratio rises.

But can debt-to-GDP ratios rise forever?

  * debt crisis
  
  * currency crisis

  * hyperinflation

In other words, which paths of :math:`B/Y` are stable? which are explosive?

.. math::
   \frac{B_{t}}{Y_t} =  (1+r-g) \frac{B_{t-1}}{Y_{t-1}} + \frac{G - T}{Y_t}

Consider two cases

1. :math:`g>r`

2. :math:`g \le r`

If :math`g > r`, the debt-to-GDP ratio will not blow up.
So a government can sustain persistent deficits as long as growth
in output is greater than the real interest rate.

In the U.S. :math:`r = 0.016`  and :math:`g = 0.033`.

Don't necessarily need a balanced budget.

\begin{frame}{Seignorage}

\bigskip

But first, a few basics about money ...


\end{frame}

\begin{frame}{Velocity and the Quantity Theory of Money}

\begin{itemize}

\item Velocity, $V$, measures how much money ``turns over'' each period.
$$ V \equiv {{\mbox{Nominal GDP}}\over{\mbox{nominal money stock}}} =
{{PY}\over{M}}. $$

\item The way the quantity theory of money is usually written is:

\bigskip

\begin{tabular}{ccccccc}
Money & $\times$ & Velocity & = & Price & $\times$ & Output \\
 $M$  & $\times$ & $V$      & = & $P$   & $\times$ &  $Y$  \STRUT \\
\end{tabular}


\item Real money demand is proportional to real income.  So
$${{M^d}\over{P}} = kY $$ Assumes constant velocity.

\end{itemize}

\end{frame}

\begin{frame}{Money and Inflation}

\begin{itemize}

\item Inflation is an increase in the price level. That is, define
inflation as: $$ \pi = \frac{\Delta P}{P} $$

\bigskip

\item A famous quote from Milton Friedman:

\medskip

\begin{quote}
Inflation is always and everywhere a monetary phenomenon.
\end{quote}

\end{itemize}

\end{frame}

\begin{frame}

\begin{itemize}

\item In a world without frictions, doubling the money supply has
no effect on output, it just doubles the price level.  So
$$ \pi = {{P_{t+1} - P_{t}}\over{P_t}} = {{\Delta P}\over{P}} =
{{\Delta M}\over{M}} $$

\item Output does not change, velocity does not change.  Quantity theory
of money.

\medskip

\item Money had no effect on anything anybody cared about.  In other
words money is {\em neutral.}

\medskip

\item The classic dichotomy: money only changes the price level.

\end{itemize}

\end{frame}

\begin{frame}{Deficits and Inflation}

\begin{itemize}

\item Recall the government budget constraint
\begin{eqnarray*}
B_{t}  &=&  B_{t-1} + r B_{t-1} + G_t + TR_t - T_t  - \frac{M_t - M_{t-1}}{P_t}
\end{eqnarray*}

\item Set transfers and government borrowing to zero, so we get
\begin{eqnarray*}
G_t  - T_{t} = {{M_{t} - M_{t-1}}\over{P_t}}
\end{eqnarray*}
So this an all-currency economy.

\item The revenue that a government raises by printing money is called
{\em seignorage}.  This is the inflation tax.

\item Revolutionary War

\end{itemize}

\end{frame}

\begin{frame}{A Great Quote}

\begin{quote}
Lenin is said to have declared that the best way to destroy the
capitalist system was to debauch its currency.  By a continuing
process of inflation, governments can confiscate, secretly and
unobserved, an important wealth of their citizens.
\end{quote}
\smallskip

\noindent{John Maynard Keynes}

\end{frame}

\begin{frame}{Real seignorage and inflation}

\begin{itemize}

\item Consider our all-currency economy. No government debt.

\item If the velocity of money is fixed and output is fixed, so real money demand is constant.
Then $$ \pi = \frac{\Delta P}{P} = \frac{\Delta M}{M} $$

\item Real seignorage revenue, $R$, is
$$ \frac{M_{t} - M_{t-1}}{P_t}  = \frac{\Delta M}{P}.$$
\item Since $\pi = {{\Delta M}\over{M}}$, real seignorage revenue is
$$ R = \pi \frac{M}{P}$$.

\end{itemize}

\end{frame}

\begin{frame}

\begin{itemize}

\item So seignorage is a tax at the rate of inflation on real money balances.
That's why it is called the inflation tax.

\medskip

\item The government collect revenue from the inflation tax when it
buys goods with newly printed money.

\medskip

\item So Friedman's really should have said,
\begin{quote}
Inflation is always and everywhere a fiscal phenomenon.
\end{quote}

\medskip

\item Since seignorage is a distortionary tax, as the government
increases this tax, people will hold lower real balances.

\medskip

\item Whether seignorage rises or falls depends on whether inflation
rises more or less than the decline in money holdings.

\end{itemize}

\end{frame}

\begin{frame}{Government Debt is a Weighted Accumulation of Past Deficits}

\begin{itemize}

\item To keep the analysis simple, ignore transfers and money creation for now.

\item A time $t$ the G.B.C. is:
\begin{eqnarray*}
B_{t}  &=&  (1+r)B_{t-1} + G_t  - T_t
\end{eqnarray*}

\item A time $t-1$ the G.B.C. is:
\begin{eqnarray*}
B_{t-1}  &=&  (1+r)B_{t-2} + G_{t-1}  - T_{t-1}
\end{eqnarray*}

\item A time $t-2$ the G.B.C. is:
\begin{eqnarray*}
B_{t-2}  &=&  (1+r)B_{t-3} + G_{t-2}  - T_{t-2}
\end{eqnarray*}

\end{itemize}

\end{frame}

\begin{frame}

\begin{itemize}


\item Substitute for $B_{t-1}$
\begin{eqnarray*}
B_{t}  &=&  (1+r) \left((1+r)B_{t-2} + G_{t-1}  - T_{t-1} \right)  + G_t  - T_t \\
       &=&  (1+r)^2 B_{t-2} +(1+r)\left( G_{t-1}  - T_{t-1} \right)  + G_t  - T_t
\end{eqnarray*}
\item Substitute for $B_{t-2}$
\begin{eqnarray*}
B_{t}  &=&  (1+r)^3 B_{t-3} + (1+r)^2\left( G_{t-2}  - T_{t-2} \right) \\
       & & + (1+r)\left( G_{t-1} - T_{t-1} \right)  + G_t  - T_t
\end{eqnarray*}

\item Keep going to the beginning of time (i.e. $t=0$)
\begin{eqnarray*}
B_{t}  &=&  (1+r)^t B_{0} + \sum_{j=0}^{t} (1+r)^j \left( G_{t-j}  - T_{t-j} \right)
\end{eqnarray*}

\end{itemize}

\end{frame}

\begin{frame}{Government Debt is a Weighted Sum of Future Surpluses}

\begin{itemize}

\item A time $t$ the G.B.C. is:
\begin{eqnarray*}
B_{t}  &=&  (1+r)B_{t-1} + G_t  - T_t
\end{eqnarray*}

\item A time $t+1$
\begin{eqnarray*}
B_{t+1}  &=&  (1+r)B_{t} + G_{t+1}  - T_{t+1}
\end{eqnarray*}
or
\begin{eqnarray*}
B_{t}  &=&  \frac{1}{1+r} \left( B_{t+1} + T_{t+1}  - G_{t+1} \right)
\end{eqnarray*}

\end{itemize}

\end{frame}

\begin{frame}

\begin{itemize}

\item Thus we can write $B_{t+1}$ as
\begin{eqnarray*}
B_{t+1}  &=&  \frac{1}{1+r} \left( B_{t+2} + T_{t+2}  - G_{t+2} \right)
\end{eqnarray*}

\item Substitute
\begin{eqnarray*}
B_{t}  &=&  \frac{1}{1+r} \left( \frac{1}{1+r}\left( B_{t+2} + T_{t+2}  - G_{t+2} \right)+ T_{t+1}  - G_{t+1} \right)
\end{eqnarray*}

\item Do this 100 times
\begin{eqnarray*}
B_{t}  &=&  \left(\frac{1}{1+r}\right)^{100} B_{t+100}  + \sum_{j=1}^{100} \left(\frac{1}{1+r}\right)^{j}(T_{t+j} -G_{t+j})
\end{eqnarray*}

\item Do this an infinite number of times
\begin{eqnarray*}
B_{t}  &=&   \sum_{j=1}^{\infty} \left(\frac{1}{1+r}\right)^{j}(T_{t+j} -G_{t+j})
\end{eqnarray*}

\end{itemize}

\end{frame}

\begin{frame}{Debt is both a backward-looking and a forward-looking variable}

\begin{itemize}

\item Sum of past spending

\bigskip

\item Sum of future surpluses

\end{itemize}
\bigskip

\bigskip
\footnotesize{just like your credit card balance ...}


\end{frame}


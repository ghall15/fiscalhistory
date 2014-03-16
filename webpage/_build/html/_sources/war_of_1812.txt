.. _war_of_1812:

***************
The War of 1812
***************

* Background

* A Theory of War Finance

    * taxes versus debt

    * Ricardian equivalence

    * Gallatin-Barro tax smoothing

* Financing the War: Theory and Practice

* How Much Did the Federal Government Pay to Borrow?

* Legacy of the War


Background
==========

* Gordon S. [Wood]_: "The War of 1812 is the strangest war in American history."

* Articulation by Gallatin of Principles for War Finance

* Leads to

   * a fiscal crisis,

   * the burning of Washington D.C.,

   * a reversal of Republican fiscal goals, and

   * the end the Federalist party

Reasons for War
---------------

* Stated Reasons

    * British impressment of American sailors

    * British violation of maritime rights

* Gordon S. [Wood]_: "the war became the logical consequence of the Republicans' diplomacy since 1805."

* Declaration of War in June 1812

    * House: 79 to 49 for war

    * Senate: 19 to 13

    * Support from South and West, Republicans

    * New England and Federalists were opposed


Background: Key Dates
---------------------

    +-----------------------+--------------------------------------------------------+
    | June 18, 1812         | Declaration of war by the United States                |
    +-----------------------+--------------------------------------------------------+
    | Summer/Fall 1812      | U.S. invades Canada, fails                             |
    +-----------------------+--------------------------------------------------------+
    | August 19, 1812       | USS *Constitution* defeats the HMS *Guerriere*         |
    +-----------------------+--------------------------------------------------------+
    | September 1813        | Commodore Perry defeats the British fleet in Lake Erie |
    +-----------------------+--------------------------------------------------------+
    | August 14, 1814       | Burning of Washington D.C.                             |
    +-----------------------+--------------------------------------------------------+
    | September 13-14, 1814 | Attack on Fort McHenry                                 |
    +-----------------------+--------------------------------------------------------+
    | December 1814         | Hartford Convention                                    |
    +-----------------------+--------------------------------------------------------+
    | December 14, 1814     | Treaty of Ghent signed                                 |
    +-----------------------+--------------------------------------------------------+
    | January 8, 1815       | The Battle of New Orleans                              |
    +-----------------------+--------------------------------------------------------+
    | February 15, 1815     | U.S. ratifies Treaty of Ghent                          |
    +-----------------------+--------------------------------------------------------+

How Should a Country Finance a War?
===================================

The government's budget constraint

.. math::

    {B_t} = \sum_{s=0}^{\infty} \left(\frac{1}{1+r}\right)^s ( T_{t+s} - G_{t+s} ).

If an unexpected increase in spending occurs, the government can do three things:

   1. cut spending somewhere else,

   2. raise taxes now or later

   3. impose a capital loss on the bond holders

Debt or taxes?
--------------

* Consider a one-period example

* Assume no foreign borrowing or lending

* The private sector (i.e. households) budget constraint:

.. math::

    Y-T =  C + S_{pvt}

where

.. math

   Y        &=& \mbox{income}
   T        &=& \mbox{lump-sum taxes}
   C        &=& \mbox{consumption}
   S_{pvt}  &=& \mbox{private saving}

* Government saving, :math:`S_{gvt}`, is just the opposite of the deficit

.. math::

    S_{gvt} = T - G

* National saving

.. math::

    S &=& S_{pvt} + S_{gvt}
      &=& Y-T - C + T - G
      &=& Y - C - G

* Since national saving must be zero: :math:`Y = C + G`

Consider a Two-Period Example
-----------------------------

* Assumptions

    1. lump-sum taxes

    2. no money, so no inflation

    3. no uncertainty

* Consider an environment in which households live for two periods:

    * period 1: now

    * period 2: the future

* Assume an individual gets happiness from consumption (:math:`C_t`) in each period. So happiness is a function of :math:`C_1` and :math:`C_2`.

* In period 1, the individual has some after-tax income :math:`Y_1 - T_1` so her budget constraint is:

.. math::

    C_1 + S_{pvt} = Y_1 - T_1

* In period 2, the individual has after-tax income :math:`Y_2 - T_2` plus her savings from the previous period

.. math::

     C_2 = Y_2-T_2 + (1+r)S_{pvt}

Note :math:`S_{pvt}` can be positive or negative.

* We can substitute out for :math:`S_{pvt}`.

.. math::

    C_2 = Y_2 - T_2 + (1+r)(Y_1 - T_1 - C_1)

* Rearranging we get

.. math::

    C_1 + \frac{C_2}{1+r} = Y_1 - T_1 + \frac{Y_2 - T_2}{1+r}

* Everything in this equation is units of "goods in period 1".  The term :math:`\frac{1}{1+r}` is
  relative price of goods between the two periods and converts the units from the second period into
  the first.

* This budget line equates the present value of lifetime
  consumption (PVLC) to the present value of lifetime resources (PVLR).

The household's budget constraint
---------------------------------

Let's think about the problem graphically.

* The budget constraint can be written in :math:`y = b + mx` form.

.. math::

     C_2  = (1+r) (Y_1 - T_1) + (Y_2 -T_2) - (1+r)C_1

* What is the opportunity cost of additional consumption in period 1?  of additional consumption in period 2?

Household Preferences for Consumption Over Time
-----------------------------------------------

* Households prefer a little bit of consumption each period rather than a lot one period and a little the other.

* Consider your eating patterns ...

* For now, let's take this assumption to the extreme.

* Assume households always choose

.. math::

    C_1 = C_2

* Measured private saving is

.. math::

    S_{pvt} = (Y_1 - T_1) - C_1

Now Add a Government
--------------------

* The government spends G in period 1 and nothing in period 2.

* The government can pay for it across two periods. So the
  present value government budget constraint is

.. math::

    G  = T_1 + \frac{T_2}{1+r}

* The government has to raise the revenue to cover this
  expenditures.  Consider two policy options:

   1. tax finance: set :math:`T_1 = G`, :math:`T_2 = 0`

   2. debt finance: set :math:`T_1 = 0`, :math:`T_2 = (1+r)G`

Will these two financing arrangements have different effects on
the household's consumption patterns?  Let's think
through the intuition

    * Taxes just reduce the household's after-tax income :math:`Y_1 - T_1` and/or :math:`Y_2 - T_2`.

    * Both policies are going to reduce the PVLR by the same amount.

    * So the household doesn't care which one of these policies the government implements.

Ricardian Equivalence
---------------------

* Robert Barro

* Ricardian equivalence implies that the timing of taxes is irrelevant on household consumption choices.

* A change in current taxes, exactly offset in present-value terms by an equal and opposite change in future taxes will have no effect on the optimal choices of :math:`C_1` and :math:`C_2`.

* A tax cut this period, leaving government spending unchanged, will decrease government saving this period.

But this decrease in government saving will be exactly offset by an increase in private saving, leaving national
saving unchanged.

When will Ricardian Equivalence not hold?
-----------------------------------------

* Taxes are not lump-sum

* Borrowing and lending constraints

* Short-sightedness

* Are taxpayers and bondholders the same people?  Who pays?


Gallatin's Principles of War Finance
====================================

* In peacetime, the government should not borrow to finance current expenditures.


* `On November 6, 1807, Gallatin wrote (see page 360)`_  Tax rates should be set to ...

.. epigraph::

     *provide a revenue at least equal to the annual expenses on a peace establishment,
     the interest on the existing debt, and the interest on the loans which may be raised.*

     *losses and privations caused by war should not be aggravated by taxes beyond what is strictly necessary*

.. _On November 6, 1807, Gallatin wrote (see page 360): http://fraser.stlouisfed.org/docs/publications/treasar/AR_TREASURY_1807.pdf


**Why doesn't Gallatin believe in Ricardian equivalence?**

Robert Barro's (Gallatin's?) Model of Tax Smoothing
---------------------------------------------------

* See [Barro1979]_

* Infinite horizon

* Tax create distortions (i.e. inefficiencies) which increase at an increasing rate with the tax rate.

* Government would like to minimize these inefficiencies.

* First, consider a deterministic setting.

    * That is, the path of government purchases (:math:`G_t`) is given

* Assume the real interest rate  (:math:`r`) is fixed.

* The initial outstanding stock of debt :math:`B_0` is some number (perhaps zero).

* The government budget constraint is:

.. math::

     B_t = (1+r) B_{t-1} + G_t - T_t

* In present value form

.. math::

    \sum_{t=1}^{\infty} \frac{G_t}{(1+r)^t} + B_0 = \sum_{t=1}^{\infty} \frac{T_t}{(1+r)^t}

* The government want to choose the path of taxes :math:`T_t` and debt :math:`B_t`
  to satisfy its budget constraint while minimizing the present value of the costs of distortions that the taxes
  create.

* Consider government choose pathes of taxes and debt to minimize

.. math::

     \sum_{t=0}^{\infty} \left(\frac{1}{1+r}\right)^t \left( \phi_1 T_t + \frac{1}{2} \phi_2 T_t^2 \right).

* The government budget constraint is

.. math::

     B_t = (1+r) B_{t-1} + G_t - T_t.

* Assume :math:`G_t` is a deterministic process.

* Assume :math:`B_0 = 0`.

* Set up the Lagrangian

.. math::

     {\cal L} = \min_{T_t, B_t} \sum_{t=0}^{\infty} \left(\frac{1}{1+r}\right)^t \left( \phi_1 T_t + \frac{1}{2}
     \phi_2 T_t^2  + \lambda_t( B_t - (1+r) B_{t-1} - G_t + T_t)\right)

* Take first order conditions

.. math::

    \frac{\partial \cal L}{\partial T_t} &=& \phi_1 + \phi_2 T_t - \lambda_t = 0  \; \; \forall t \\
    \frac{\partial \cal L}{\partial B_t} &=& \lambda_t  - \frac{1}{1+r} (1+r) \lambda_{t+1} = 0  \; \; \forall t \\
    \frac{\partial \cal L}{\partial \lambda_t} &=& B_t - (1+r) B_{t-1} - G_t + T_t = 0  \; \; \forall t \\

* The first two FOCs imply

.. math::

    T_t = T_{t+1} \; \; \forall t

* Taxes  must be constant.  A smooth tax rate minimizes distortions over time.

Tax Smoothing in a stochastic setting
-------------------------------------

* Now consider an environment in which :math:`G_t` follows a stochastic process.

* The government's problem becomes

.. math::

     \min_{T_t} E \sum_{t=1}^{\infty}  \left(\frac{1}{1+r}\right)^t  \left( \phi_1 T_t + \frac{1}{2} \phi_2 T_t^2 \right)

subject to

.. math::

     \sum_{t=1}^{\infty} \frac{G_t}{(1+r)^t} + B_0 = \sum_{t=1}^{\infty} \frac{T_t}{(1+r)^t}

The :math:`E` stands for expectation.

Again we can set up a Lagrangian

.. math::

     {\cal L} = \min_{T_t, B_t} E_0 \sum_{t=0}^{\infty} \left(\frac{1}{1+r}\right)^t \left( \phi_1 T_t +
     \frac{1}{2} \phi_2 T_t^2  + \lambda_t( B_t - (1+r) B_{t-1} - G_t + T_t)\right)

Take first order conditions

.. math::

     \frac{\partial \cal L}{\partial T_t} &=& \phi_1 + \phi_2 T_t - \lambda_t = 0  \; \; \forall t \\
     \frac{\partial \cal L}{\partial B_t} &=& \lambda_t  - E_t \frac{1}{1+r} (1+r) \lambda_{t+1} = 0  \; \; \forall t \\
     \frac{\partial \cal L}{\partial \lambda_t} &=& B_t - (1+r) B_{t-1} - G_t + T_t = 0  \; \; \forall t \\

The first two FOCs imply

.. math::

    T_t = E_t T_{t+1} \; \; \forall t

**Tax rates follow a random walk.  There cannot be predictable changes in the tax rate.**

Implications
------------

* This implies :math:`E_t T_{t+s} = T_t` for any :math:`s > 0`.

* Consider again the government budget constraint.

.. math::

      \sum_{t=1}^{\infty} \frac{G_t}{(1+r)^t} + B_0 = \sum_{t=1}^{\infty} \frac{T_t}{(1+r)^t}

or

.. math::

      B_0 = E_t \sum_{t=1}^{\infty} \frac{T_t - G_t}{(1+r)^t}

* So we can write the GBC as

.. math::

     B_t = \frac{T}{r} - E_t \sum_{s=0}^{\infty} \frac{G_{t+s}}{(1+r)^{s+1}}


A Temporary Increase in Government Expenditures
-----------------------------------------------

Suppose government spending follows the stochastic process

.. math::

    G_t &=& \bar{G} + \epsilon_t
    E_t \epsilon_{t+1} &=& 0.

So shocks are purely transitory.  Then

.. math::

    B_t &=& \frac{T_t}{r} - E_t \sum_{s=0}^{\infty} \frac{G_{t+s}}{(1+r)^{s+1}}
        &=& \frac{T_t}{r} - \frac{\bar{G}}{r} - \frac{\epsilon_t}{1+r}

so

.. math::

     T_t = \bar{G} + rB_t + \frac{r}{1+r} \epsilon_t

and

.. math::

     B_{t+1} = \frac{T_{t+1}}{r} - \frac{\bar{G}}{r} - \frac{\epsilon_{t+1}}{1+r}

so

.. math::

    E_t B_{t+1} &=& \frac{E_t T_{t+1}}{r} - \frac{\bar{G}}{r}
                &=& \frac{T_t}{r} - \frac{\bar{G}}{r}
                &=& B_t + \frac{\epsilon_{t+1}}{1+r}

This holds for all subsequent periods

.. math::

    E_t B_{t+n} = B_t + \frac{\epsilon_{t+1}}{1+r}

:math:`\frac{1}{1+r}` of the increase is absorbed through an increase in debt.

:math:`\frac{r}{1+r}` of the increase is absorbed through an increase in taxes.

Recall Gallatin's quote:  Tax rates should be set to ...

.. epigraph::

    *provide a revenue at least equal to the annual expenses on a peace establishment,
    the interest on the existing debt, and the interest on the loans which may be raised.*

.. figure:: _static/figures/barro_tax_smooth.png
    :scale: 60%
    :align: center

    **Deficits Under Tax Smoothing**

A Permanent Increase in Government Expenditures
-----------------------------------------------

* Suppose government spending increases by :math:`\Delta G` permanently.

* The government budget constraint is

.. math::

     (1+r) B_{t+s} = T_{t+s} - (\bar{G} + \Delta G) + B_{t+s+1}  \; \; \forall s \ge 0

* If we want to smooth taxes :math:`T_{t+s} = T_t`, then:

.. math::

    (1+r) B_{t+s} = T_{t} - (\bar{G} + \Delta G) + B_{t+s+1}  \; \; \forall s \ge 0

So :math:`B_{t+s} = B_{t+s+1}` for all :math:`s`, so debt must stay constant.

* Entire shock is absorbed by the tax rate.  Taxes rise by :math:`\Delta G`.

From Theory to Reality:  Gallatin's Estimates
---------------------------------------------

* [Wood]_, page 670,

.. epigraph::

    Albert Gallatin pointed out at the outset [ March 1812], the Republicans needed to conduct a war without
    promoting "the evils inseparable from it ...
    debt, perpetual taxation, military establishments, and other corrupting or anti-republican habits or
    institutions."

* Gallatin estimated peacetime expenditures at \$7 million and peacetime revenue at \$14 million.

* Estimated 50\% loss of revenue from the war

* Need internal tax increases to cover the interest cost of the war loans.

Reality: Financing of the War of 1812
-------------------------------------

* Prior to declaration of war, the Madison and Gallatin anticipate war with Britain, but

    * from 1807 to 1812, lots of talk and planning, little in action

    * in 1810 rather than raise taxes, spending on the military is cut (what the \%\#\@\|?)

    * talk about moth-balling the navy

    * 1811 killed the BUS

* Six Per Cent Loan of 1812

    * March 14, 1812

    * \$11 million

* War declared on June 18, 1812.

Taxes
-----

* In the early 1800s Gallatin eliminated most sources of internal revenue

     * there is no machinery for collecting internal taxes

* On July 1, 1812, U.S. doubles customs duties

     * Remind me who the U.S. is at war with ... as yes, their primary trading partner ...

* Gallatin proposes raising taxes and is labelled a "A Rat" by House Republicans.

* March 1813 Treasury is almost out of money

* In June 1813 Congress passes a comprehensive tax bill

    * stills, retailers, land, sugar, carriages

    * won't go in effect until 1814

* Another tax increase in 1814

Difficulty Borrowing
--------------------

* Sixteen Million Loan of 1813

    * February 8, 1813

    * 6 per cent interest

    * no taxes created to "fund" the loan

    * sold for 88 cents on the dollar

* Geographical subscription of the loan

     +--------------------------+--------------+
     |  States East of New York | \$486,700    |
     +--------------------------+--------------+
     |  State of New York       | 5,720,000    |
     +--------------------------+--------------+
     |  Philadelphia            | 6,858,400    |
     +--------------------------+--------------+
     |  Baltimore and D.C.      | 2,393,900    |
     +--------------------------+--------------+
     |  Virginia                | 187,000      |
     +--------------------------+--------------+
     |  Charleston, S.C.        | 354,000      |
     +--------------------------+--------------+
     |                          | \$16,000,000 |
     +--------------------------+--------------+


The Financial Humiliation of 1814
---------------------------------

* In 1814 Congress authorizes a \$25 million loan, paying a 6\% coupon.

* Treasury partitioned into three installments.

* Under the Treasury's invitation for subscriptions, buyers of the first installment were promised retroactively
  more favorable terms if subsequent installments garnered lower prices.

* This was indeed the case, and the Treasury was forced to issue additional shares to buyers of the first
  installment.

* End up selling the loan at 80 cents on the dollar.

Deficits and Loans
------------------

    +------+--------------+----------+----------+
    |      | Expenditures | Receipts | Deficits |
    +------+--------------+----------+----------+
    | 1812 |   \$20.3     | \$9.8    | \$10.5   |
    +------+--------------+----------+----------+
    | 1813 |     31.7     | 14.3     | 17.4     |
    +------+--------------+----------+----------+
    | 1814 |     34.7     | 11.2     | 23.5     |
    +------+--------------+----------+----------+
    | 1815 |     32.9     | 15.7     | 17.2     |
    +------+--------------+----------+----------+
    |      |              |          | 68.6     |
    +------+--------------+----------+----------+

+-------------------+------------+-----------------+----------+---------------+
| Act               | Authorized | Face Value Sold | Discount | Amount Raised |
+-------------------+------------+-----------------+----------+---------------+
| March 14, 1812    | \$11       | \$10.3          | 1.00     |   \$10.3      |
+-------------------+------------+-----------------+----------+---------------+
| February 8, 1813  | 16         |   18.1          | 0.88     |     16.0      |
+-------------------+------------+-----------------+----------+---------------+
| August 2, 1813    | 7.5        |    8.5          | 0.88     |      7.5      |
+-------------------+------------+-----------------+----------+---------------+
| March 24, 1814    | 25         |   16.0          | 0.80     |     12.9      |
+-------------------+------------+-----------------+----------+---------------+
| November 15, 1814 | 3          |    1.5          | 1.00     |      1.5      |
+-------------------+------------+-----------------+----------+---------------+
| February 24, 1815 | 25         |    9.1          | 1.00     |      9.1      |
+-------------------+------------+-----------------+----------+---------------+
|                   |            | \$63.5          |          |   \$57.3      |
+-------------------+------------+-----------------+----------+---------------+

Were these loans sufficient to cover the deficits? No.

.. figure:: _static/figures/debt_decomp_1792_to_1825.png
    :scale: 60%
    :align: center

    **Federal Debt by Types of Loans**

.. figure:: _static/figures/bonds_notes_prices_1812.png
    :scale: 60%
    :align: center

    **Prices of 6\% Bonds and Treasury Notes**

.. figure:: _static/figures/par_and_market_value_debt.png
    :scale: 60%
    :align: center

    **Quantity of the Federal Debt: Principal Outstanding and Market Value**

.. figure:: _static/figures/ratio_market_to_par.png
    :scale: 60%
    :align: center

    **Ratio of Market Value to Par Value of the Debt**

Issuance of Treasury Notes
--------------------------

What are Treasury Notes?

   * one-year loans

   * paid :math:`5\frac{2}{5}` per cent interest

         * 1.5 cents a day per \$100

   * Minimum denomination was originally \$100

   * large in size

   * could pay taxes or purchase government bonds or public lands

   * later in the war smaller denominations issued

They were kind-of-sort-of  money-ish.

Were Treasury Notes money?
--------------------------

* The ghost of the Continental Dollar?

* Gallatin recognized the currency-aspect of Treasury notes

* In a letter to Congress in January 1812, Gallatin states

.. epigraph::

    Treasury notes, bearing interest, might to a certain extent be issued, and to that extent
    diminish the amount to be directly borrowed. The advantage they would have would
    result from their becoming a part of the circulating medium, and taking, to a certain
    degree, the place of bank-notes.

* Shortage of currency

    * Bank of United State dissolved

* Were never made legal tender

* Could pay taxes with them, support value

* Five Issues

* Generally trade near par

* 1817 Issuing Treasury Notes considered an "embarrassment"

.. figure:: _static/figures/treasury_notes_outstanding_1812.png
    :scale: 60%
    :align: center

    **Treasury Notes Outstanding**

Was Gallatin Able to Carry Out His Policy?
------------------------------------------

Let's do a rough calculation ...

* What was peacetime :math:`G`?

     * average annual expenditures from 1801 to 1811: \$8.7 million

* What was the cost of the war?

     * average annual expenditures from 1812 to 1816: \$30.1 million

     * So the war cost :math:`5 \times (30.1 - 8.7)  =`  \$110 million

* Assume a 6\% interest rate, so Gallatin should have

     * raised taxes by :math:`\frac{.06}{1+.06} \times 110 =` \$6.2 million

     * and borrowed :math:`110 - 6.2 =` \$103.8 million

   +------+---------+------------+------------+------------+----------------+-------------+
   | Year | Indians |  War+Navy  | Interest   | Pensions   | Miscellaneous  |   Total     |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1809 | 337,504 | 5,773,531  |  2,866,075 |  87,834    |  1,215,804     |  10,280,747 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1810 | 117,625 | 3,948,568  | 3,163,671  |  83,744    |  1,101,145     |  8,414,753  |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1811 | 151,875 | 3,998,395  | 2,585,436  |  75,044    |  1,367,291     |  8,178,040  |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1812 | 277,845 | 15,777,163 | 2,451,273  |  91,402    |  1,683,088     |  20,280,771 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1813 | 167,358 | 26,098,613 | 3,599,455  |  86,990    |  1,729,436     |  31,681,852 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1814 | 167,395 | 27,662,097 | 4,593,239  |  90,164    |  2,208,030     |  34,720,925 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1815 | 530,750 | 23,454,294 | 5,990,090  |  69,656    |  2,898,870     |  32,943,661 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1816 | 274,512 | 19,920,375 | 7,822,923  |  188,804   |  2,989,741     |  31,196,356 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1817 | 319,464 | 11,318,835 | 4,536,283  |  297,374   |  3,518,937     |  19,990,892 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1818 | 505,704 | 8,576,410  | 6,209,954  |  890,720   |  3,835,840     |  20,018,628 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1819 | 463,181 | 10,353,941 | 5,211,731  |  2,415,940 |  3,067,211     |  21,512,004 |
   +------+---------+------------+------------+------------+----------------+-------------+
   | 1820 | 315,750 | 7,018,382  | 5,151,004  |  3,208,376 |  2,592,022     |  18,285,535 |
   +------+---------+------------+------------+------------+----------------+-------------+

       **Federal Expenditure by Type**

.. figure:: _static/figures/expenditures_1791_1825.png
    :scale: 60%
    :align: center

    **Federal Government Expenditures by Type as a Share of GDP**

    +------+-------------+------------------+---------------+---------------+--------------+
    | Year | Customs     | Internal Revenue | Sale of       | Miscellaneous | Total        |
    |      |             | + Direct Taxes   | Public Lands  |               |              |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1809 | \$7,257,507 |  \$11,552        |     \$442,252 | \$62,163      | \$7,773,473  |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1810 | 8,583,309   |  19,879          |      696,549  | 84,477        | 9,384,214    |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1811 | 13,313,223  |  9,963           | 1,040,238     | 59,211        | 14,422,634   |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1812 | 8,958,778   |  5,762           | 710,428       | 126,165       | 9,801,133    |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1813 | 13,224,623  |  8,561           | 835,655       | 271,571       | 14,340,410   |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1814 | 5,998,772   |  3,882,482       | 1,135,971     | 164,400       | 11,181,625   |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1815 | 7,282,942   |  6,840,732       | 1,287,959     | 285,283       | 15,696,917   |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1816 | 36,306,875  |  9,378,343       | 1,717,985     | 273,782       | 47,676,986   |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1817 | 26,283,348  |  4,512,288       | 1,991,226     | 312,187       | 33,099,050   |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1818 | 17,176,385  |  1,219,604       | 2,606,565     | 582,618       | 21,585,171   |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1819 | 20,283,609  |  313,244         | 3,274,423     | 732,098       | 24,603,374   |
    +------+-------------+------------------+---------------+---------------+--------------+
    | 1820 | 15,005,612  |  137,847         | 1,635,872     | 1,061,338     | 17,840,670   |
    +------+-------------+------------------+---------------+---------------+--------------+

     **Federal Revenue by Source**

.. figure:: _static/figures/revenue_1791_1825.png
    :scale: 60%
    :align: center

    **Government Revenue by Type as a Share of GDP**

.. figure:: _static/figures/revenue_expend_1790_1835.png
    :scale: 60%
    :align: center

    **Federal Government Revenue and Expenditure as a Share of GDP**

* Assuming a 6\% interest rate, Gallatin should have

    * raised taxes by :math:`\frac{.06}{1+.06} \times 110 \; = \; 6.2`

    * and borrowed :math:`110 - 6.2 = 103.8`

* average tax revenue

    * from 1801 to 1811: \$13.1 million

    * from 1812 to 1816: \$19.7 million

    * difference: \$ 6.6 million

* debt outstanding

    * March 1812: \$45.4 million

    * September 1816: \$136.5 million

    * difference: \$91.1 million

What is this calculation missing?

.. figure:: _static/figures/primary_deficit_to_gdp_1791_1835.png
    :scale: 60%
    :align: center

    **Federal Gross and Primary Deficits as a Share of GDP**

.. figure:: _static/figures/barro_tax_smooth.png
    :scale: 60%
    :align: center

    **Deficits Under Tax Smoothing**

War Finance: Theory and Practice
================================

.. epigraph::

    In theory, there is no difference between theory and practice. In practice, there is.

    -- Yogi Berra

* theory assumes

    * any tax rate between 0 and 1 is feasible

    * can borrow as much money as needed at the fixed interest rate

* practice: taxes

    * What was the primary source of revenue?

    * Who was the U.S. main trading partner?

    * Who did the U.S. declare war on?

* practice: borrowing

    * What happened to the Bank of the United States?

    * Where are the banks in the U.S.?  Where are they located?

    * Do the bankers support the Republicans and the war?


How much did the government really pay to borrow money?
=======================================================

In a 1830 U.S. House Committee on Ways and Means Report, Mr. M'Duffie reckoned that during the War of 1812,
the Government paid \$46 million to borrow \$80 million.  On page 12 of the report he states:

.. epigraph

    The government borrowed, during the short period of the war, eighty
    millions of dollars, at an average discount of fifteen per cent. giving certificates
    of stock, amounting to eighty millions of dollars, in exchange for sixty-eight
    millions of dollars, in such bank paper as could be obtained. In this statement,
    treasury notes are considered as stock, at twenty per cent. discount. Upon the
    very face of the transaction, therefore, there was a loss of twelve millions of
    dollars, ...  But the sum
    of sixty-eight millions of dollars, received by the government, was in a depreciated
    currency, not more than half as valuable as that in which the stock given
    in exchange for it, has been and will be redeemed. Here, then, is another loss
    of thirty-four millions, resulting, incontestibly and exclusively, from the depreciation
    of the currency, and making, with the sum lost by the discount, forty-six millions of dollars.

.. figure:: _static/figures/bonds_notes_prices_1812.png
    :scale: 60%
    :align: center

    **Prices of 6 Per Cent Bonds and Treasury Notes**

.. figure:: _static/figures/ratio_market_to_par.png
    :scale: 60%
    :align: center

    **Ratio of the Market Value to the Par Value of the Outstanding Debt**

.. figure:: _static/figures/coupons_return.png
    :scale: 60%
    :align: center

    **Coupon Payments and Official Interest Payments as a Percent of the Market Value of the Debt**


+-------+-----------+------------+-------+------+----------+------------+-------+-----------+---------+------------+
|       | Beginning of Year              |      |   End of Year                 |                                  |
+-------+-----------+------------+-------+------+----------+------------+-------+-----------+---------+------------+
|       | Par value | Balance in | Net   |      |Par value | Balance in | Net   | Change in | primary |            |
+       +           +            +       +      +          +            +       +           +         +            +
|  Year | of debt   | Treasury   | Debt  | Year | of debt  | Treasury   | Debt  | Net Debt  | deficit | difference |
+-------+-----------+------------+-------+------+----------+------------+-------+-----------+---------+------------+
|  1812 |  46.6     |  3.5       |  43.1 | 1815 | 131.8    | 13.1       | 118.7 | 75.6      |  51.9   |   23.7     |
+-------+-----------+------------+-------+------+----------+------------+-------+-----------+---------+------------+
|  1816 | 131.8     | 13.1       | 118.7 | 1816 | 131.1    | 22.0       | 109.1 | -9.6      | -24.3   |   14.7     |
+-------+-----------+------------+-------+------+----------+------------+-------+-----------+---------+------------+
| Total |                                                                       | 66.0      | 27.6    |   38.4     |
+-------+-----------+------------+-------+------+----------+------------+-------+-----------+---------+------------+

    **Back-of the-Envelop Calculation of War of 1812 Borrowing Cost**

Debt-to-GDP Accounting
----------------------

* Debt-to-GDP ratio

   * 1812:  4.8 \%

   * 1816:  11.6 \%

   * 1812:  9.4 \%

* Recall

.. math::

     \frac{B_t}{Y_t} - \frac{B_{t-1}}{Y_{t-1}} = i_t \frac{B_{t-1}}{Y_{t-1}} -\pi_t \frac{B_{t-1}}{Y_{t-1}} -g_t
     \frac{B_{t-1}}{Y_{t-1}}  +  \frac{G_t  - T_t}{Y_t}


.. figure:: _static/figures/par_and_market_value_debt_gdp.png
    :scale: 60%
    :align: center

    **Debt-to-GDP Ratio**

.. figure:: _static/figures/inflation_gdpgrowth_1810_1825.png
    :scale: 60%
    :align: center

    **Inflation and GDP Growth**

.. figure:: _static/figures/holding_period_return_1792_1825.png
    :scale: 60%
    :align: center

    **Holding Period Returns to Bondholders**

.. figure:: _static/figures/primary_deficit_to_gdp_1791_1835.png
    :scale: 60%
    :align: center

    **Federal Gross and Primary Deficits as a Share of GDP**

+-------+------+-------+------+--------++---------+------------+--------+---------+
|              | Debt to GDP           ||  Bond   |            | GDP    | deficit |
+              +-------+------+--------++         +            +        +         +
|      Year    | start | end  | change || Returns | Inflation  | Growth | to GDP  |
+-------+------+-------+------+--------++---------+------------+--------+---------+
|  1812 | 1816 |  4.8  | 11.6 | 6.2    ||  4.0    |  1.4       |  -0.7  | 1.4     |
+-------+------+-------+------+--------++---------+------------+--------+---------+
|  1816 | 1825 | 11.6  | 9.4  | -2.8   ||  7.6    |  4.1       |  -4.2  | -10.3   |
+-------+------+-------+------+--------++---------+------------+--------+---------+
|  1812 | 1825 | 4.8   | 9.4  | 3.5    || 11.6    |  5.6       |  -4.9  | -8.8    |
+-------+------+-------+------+--------++---------+------------+--------+---------+


**Contributions to Changes in the Debt-to-GDP Ratio**


     +-------------------------------------+-------+---------+
     | Variable                            |  Mean | Std Dev |
     +-------------------------------------+-------+---------+
     | Nominal Rate of Return              |  7.65 | 10.97   |
     +-------------------------------------+-------+---------+
     | GDP defl inflation                  | -2.86 | 8.15    |
     +-------------------------------------+-------+---------+
     | Real Rate of Return                 | 10.51 | 18.05   |
     +-------------------------------------+-------+---------+
     | Real GDP growth                     |  3.74 |  1.71   |
     +-------------------------------------+-------+---------+
     | $100 \times$ primary Deficit-to-GDP | -0.60 |  1.34   |
     +-------------------------------------+-------+---------+

     **Means and Standard Deviations of Components to Debt-to-GDP Dynamics: 1810-1825**

Post-War Surge in Revenue
-------------------------

* Internal tax increases finally kick in

* Customs revenues surge in 1816

    * imports surge from \$13 million in 1814 to \$147 million in 1816

    * war in Europe ends

    * tariff rates still high from 1812

* Tariff of 1816

    * move from revenue-focused to protectionism-focused

Establishment of the Second Bank of the United States
-----------------------------------------------------

* War made clear the need for short-term loans

* First attempt in January 1815 vetoed by Madison

* Second attempt in March 1816 passed and signed by Madison

    * 20 year charter

    * Philadelphia

The War and Republican Goals
----------------------------

* Elimination of the debt

* Elimination of internal taxes

* No standing army and no involvement in European Wars

* Elimination of the Bank of the United States


The War and the Federalists
---------------------------

* Hartford Convention

    * December 1814

    * 26 delegates met in secret

* Create list of Federalist grievances

    * end of 3/5 rule of slaves

    * no new states

    * clumsy proposals to limit Virginia's power

* Report comes out at same time as news of the Treaty of Ghent

* End of the Federalist Party

Legacy of the War of 1812
-------------------------

* Bondholders who stuck with the U.S. earned fantastic rates of return

    * 1815: 45.1\% returns

    * 1816: 20.7\%

    * 1817: 20.9\%

    * no defaults, even to British creditors

* U.S. government refrained from using the inflation tax.

     * Treasury notes held their value and paid off in full

* Soon after the war, U.S. Treasury securities consistently traded at par for the first time in U.S. history.


War Patterns
------------

In almost every war, you see the following

1. Early on, the war promises to be short and inexpensive.

2. Early on, rely on short-term financing

3. Wars are rarely short and cheap, need for more revenue requires tax increases and long-term lending

4. After the war expenditures rarely fall to pre-war levels

     * interest payments

     * pensions

     * other stuff

.. figure:: _static/figures/revenue_expend_1790_1835.png
    :scale: 60%
    :align: center

    **Federal Government Revenue and Expenditure as a Share of GDP**

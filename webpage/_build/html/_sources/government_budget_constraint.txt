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

*  Current composition of the  federal government budget is quite different from state and local budgets.

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



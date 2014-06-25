.. _data_appendix:

***************************************
Appendix:  Fiscal Data for 1775 to 1941
***************************************

In this appendix, we report the receipt, expenditure, and debt series from 
1775 to 1941 that we use in this website.

The receipts and expenditure data are reported annually by fiscal year.
The first fiscal year for the 
U.S. Government started January 1, 1789. In 1842, Congress changed the beginning 
of fiscal year from January 1 to July 1.  In 1977, it was changed again from July 1 to October 1 
where it remains today.

Much of the data on the federal debt is recorded quarterly prior until 1871 and monthly thereafter.

The entire zipped subdirectory of excel and matlab files is available from
`Debt_and_fiscal_accounts_1775-1941.zip
<http://people.brandeis.edu/~ghall/_build/data/Debt_and_fiscal_accounts_1775-1941.zip>`_.  
Below, we describe the content and
sources of each file individually.

Federal Receipts and Expenditures
=================================

* From 1776 to 1789.  These data will be posted soon.

* From 1790 to 1940 the receipt and expenditure data come from the `Annual Reports of the Secretary of Treasury`_.  
  In 1922, the Treasury changed reporting from receipts and expenditures from disbursements to reporting these figures 
  from warrants.  The differences between these two methodologies are small.  The most noticeable difference occurs 
  in the *Civil and Miscellaneous* category of expenditure.  For completeness, we make both available.

    * The 1791-1940 data for these files are from the `1940 Annual Report`_, pages 642 - 650. In the 
      Treasury Report, the numbers are rounded to the nearest dollar. In the excel files, figures 
      are reported to the penny when such details are available from older reports. 

       -- `Receipts 1790-1940`_
       
       -- `Expenditures 1790-1940`_

    * The 1790-1921 data for these files are from the `1921 Annual Report`_, pages 512-526.
    
       --  `Receipts 1790-1921`_
    
       --  `Expenditures 1790-1921`_

.. _Annual Reports of the Secretary of Treasury: http://fraser.stlouisfed.org/publication/?pid=194

.. _1815 Annual Report: http://fraser.stlouisfed.org/docs/publications/treasar/AR_TREASURY_1815.pdf

.. _1921 Annual Report: http://fraser.stlouisfed.org/docs/publications/treasar/AR_TREASURY_1921.pdf

.. _1940 Annual Report: http://fraser.stlouisfed.org/docs/publications/treasar/AR_TREASURY_1940.pdf

.. _Receipts 1790-1940: http://people.brandeis.edu/~ghall/_build/data/Receipts%20(post%201921%20revisions).xlsx

.. _Expenditures 1790-1940: http://people.brandeis.edu/~ghall/_build/data/Expenditures%20(post%201921%20revisions).xlsx

.. _Receipts 1790-1921: http://people.brandeis.edu/~ghall/_build/data/Receipts%20(pre%201921%20data).xlsx

.. _Expenditures 1790-1921: http://people.brandeis.edu/~ghall/_build/data/Expenditures%20(pre%201921%20data).xlsx

Federal Debt 
============

Below we describe a security-level data set of U.S. Treasury loans. All data are of the end of the month.  

The matlab script gross_debt_plot_1776_1941.m_ constructs a measure of gross debt from these individual securities.
It then compares the constructed series with the official Treasury series. 

1776 - 1840
-----------

There are three excel files

    * Bond_List_1776_1840.xls_  -- list and provides basic information (e.g. name, term, coupon rate, ...) for each
      loan in the database
      
    * Gov_Bond_Quant_1776_1840.xls_  -- provides the principal value outstanding for each loan
    
    * Gov_Bond_Price_1776_1840.xls_ -- provides the market price for each loan   

The matlab function bond_load_1776_1840.m_ reads in the data from these three excel files and
organizes the data into structures.

The sources for the data are:

    * The description of each bond comes from [Bayley1882]_.

    * For the quantity outstanding from 1776 to 1790.
        - the foreign loans are the quantities outstanding implied from the issues and redemptions reported by [Bayley1882]_.
        - the domestic loans are constructed by the authors.  A description 
          of the sources and methods for
          constructing these data are in [HallSargent2013]_.
          
    * From 1790 to 1840 the quantity outstanding data for specific loans 
      are the stocks outstanding implied from the flows 
      reported by [Bayley1882]_.  We cross checked these implied quantities outstanding 
      with those reported in [Registers_Office]_.
      The unfunded debt is from pages 47-50 of the `1815 Annual Report`_. 
          
    * The price data are from [Sylla_Wilson_Wright]_ and [Razaghain]_. 

.. _Bond_List_1776_1840.xls: http://people.brandeis.edu/~ghall/_build/data/Bond_List_1776_1840.xls

.. _Gov_Bond_Quant_1776_1840.xls: http://people.brandeis.edu/~ghall/_build/data/Gov_Bond_Quant_1776_1840.xls

.. _Gov_Bond_Price_1776_1840.xls: http://people.brandeis.edu/~ghall/_build/data/Gov_Bond_Price_1776_1840.xls

.. _bond_load_1776_1840.m: http://people.brandeis.edu/~ghall/_build/data/bond_load_1776_1840.m

.. _gross_debt_plot_1776_1941.m: http://people.brandeis.edu/~ghall/_build/data/gross_debt_plot_1776_1941.m

1840 to 1900
------------

There are four excel files

    * Bond_List_1840_1900.xls_  -- list and provides basic information (e.g. name, term, coupon rate, ...) for each
      loan in the database
      
    * Gov_Bond_Quant_1840_1900.xls_  -- provides the principal value outstanding for each loan
    
    * Gov_Bond_Price_1840_1900.xls_ -- provides the market price for each loan   

    * Gov_Bond_Call_1840_1900.xls_ -- provides the date and quantities of Treasury calls for each loan  

The matlab function bond_load_1840_1900.m_ reads in these data from these four excel files and
organizes the data into structures.

The sources for the data are:

    * The description of each bond comes from [Bayley1882]_ and [Childs_1947]_.
        
    * The quantity outstanding data
     
       -- from 1790 to 1871 are from [Bayley1882]_ and checked with [Registers_Office]_.
    
       -- from 1871 to 1900 are from the `Monthly Statements of the Public Debt`_ (MSPD).
            
    * The price data are from [Razaghain]_ and the `Commercial and Financial Chronicle`_.
      Prices from newspapers may not be the complete set of all securities traded at the time 
      because "inasmuch as the bulk of the business in United States Government bonds is done 
      over the counter,and not on the Stock Exchange" (NY Times June 1916). 
      This fact is also noted on page 109 of [Childs_1947]_.     
    
    * The call data are from various years of the `Annual Reports of the Secretary of Treasury`_.

.. _Commercial and Financial Chronicle: http://en.wikipedia.org/wiki/Commercial_%26_Financial_Chronicle

.. _Monthly Statements of the Public Debt: http://www.savingsbonds.gov/govt/reports/pd/mspd/mspd.htm
.. _MSPD: http://www.savingsbonds.gov/govt/reports/pd/mspd/mspd.htm

.. _Bond_List_1840_1900.xls: http://people.brandeis.edu/~ghall/_build/data/Bond_List_1840_1900.xls

.. _Gov_Bond_Quant_1840_1900.xls: http://people.brandeis.edu/~ghall/_build/data/Gov_Bond_Quant_1840_1900.xls

.. _Gov_Bond_Price_1840_1900.xls: http://people.brandeis.edu/~ghall/_build/data/Gov_Bond_Price_1840_1900.xls

.. _Gov_Bond_Call_1840_1900.xls: http://people.brandeis.edu/~ghall/_build/data/Gov_Bond_Call_1840_1900.xls

.. _bond_load_1840_1900.m: http://people.brandeis.edu/~ghall/_build/data/bond_load_1840_1900.m

1900 to 1918
------------

There are three excel files

    * Bond_List_1900_1918.xls_  -- list and provides basic information (e.g. name, term, coupon rate, ...) for each
      loan in the database
      
    * Gov_Bond_Quant_1900_1918.xls_  -- provides the principal value outstanding for each loan
    
    * Gov_Bond_Price_1900_1927.xlsx_ -- provides the market price for each loan   

The sources for the data are:

    * The description of each bond comes from [Childs_1947]_ and the MSPD_.
        
    * The quantity outstanding data from the MSPD_.
            
    * The price data are from the New York *Times*. January 1900 to March 1917 data are 
      from "Bid and Asked Quotation" and April 1917 to December 1927 data are from 
      "United States Govt. Bonds." From April 1917 to February 1919,
      there appeared a section in the *Times* titled "United States Govt. Bonds" which quoted 
      dealer prices, and these prices differ slightly from our normal source "Bid and Asked Quotation."  
   
The matlab function bond_load_1900_1918.m_ reads in these data from these three excel files and
organizes the data into structures.

.. _Bond_List_1900_1918.xls: http://people.brandeis.edu/~ghall/_build/data/Bond_List_1900_1918.xls

.. _Gov_Bond_Quant_1900_1918.xls: http://people.brandeis.edu/~ghall/_build/data/Gov_Bond_Quant_1900_1918.xls

.. _Gov_Bond_Price_1900_1927.xlsx: http://people.brandeis.edu/~ghall/_build/data/Gov_Bond_Price_1900_1927.xlsx

.. _bond_load_1900_1918.m: http://people.brandeis.edu/~ghall/_build/data/bond_load_1900_1918.m


1919-1941
---------

There are two excel files.

    * Bond_List_1919_1941.xlsx_  -- list and provides basic information (e.g. name, term, coupon rate, ...) for the major
      loans in the database
      
    * Gov_Bond_Quant_1919_1941.xlsx_  -- provides the principal value outstanding for each loan

The matlab function bond_load_1919_1941.m_ reads in just Gov_Bond_Quant_1919_1941.xlsx and
organizes the quantity data into structures.

We collected prices through 1927, which are the price file   Beginning in 1925, prices from the New York *Times* are available 
from the `CRSP US Treasury Database`_. 

Prior to 1940, CRSP does not report the quantity outstanding for many securities.  So 
Gov_Bond_Quant_1919_1941.xlsx_ provides a comprehensive record of the quantity outstanding for each individial security.

.. _Bond_List_1919_1941.xlsx: http://people.brandeis.edu/~ghall/_build/data/Bond_List_1919_1941.xlsx

.. _Gov_Bond_Quant_1919_1941.xlsx: http://people.brandeis.edu/~ghall/_build/data/Gov_Bond_Quant_1919_1941.xlsx

.. _CRSP US Treasury Database: http://www.crsp.com/products/research-products/crsp-us-treasury-database

.. _bond_load_1919_1941.m: http://people.brandeis.edu/~ghall/_build/data/bond_load_1919_1941.m

More than you care to know about Gross Federal Debt
===================================================

The official U.S. Treasury gross federal debt series is available from FRED_ and TreasuryDirect_.  
From 1853 to 1981, gross debt is decomposed into three components: interest bearing, matured, and non-interest bearing.  
See the pages 61 to 63 of the Statistical 
Appendix for the `1980 Annual Report`_ and `Public Debt 1790-1980.xlsx`_. 
 
In the matlab script gross_debt_plot_1776_1941.m_, we attempt to construct this series using our bond-level data.  Overall, the two
series are quite close.  From 1853 to 1917, we can match the interest-bearing component of the debt to the dollar.  However, the following 
discrepancies exist between our series and the Treasury's series:

1.  Prior to 1833, the Treasury's series is from the debt outstanding reported in Annual Reports.  In these reports the quantity
    of foreign debt differs from the quantities outstanding implied by [Bayley1882]_ and reported in [Registers_Office]_.
    Since the Annual Reports state aggregate foreign debt, it is not possible to determine 
    the source of the discrepancy.  

    Prior to 1853, we also report more matured debt than does the Treasury. This is most noticeable in 1835 when the Treasury reports 
    having only \$37,513
    in total debt outstanding.  We were unable reconcile this low figure with the redemption figures and the quantities of pre-1946 
    matured debt reported outstanding decades later.  Consequently, in 1835 we report \$162,648.75 in total debt outstanding.

2.  There are small differences in the timing of issues and redemptions for various loans.  For example, the Treasury 
    records the Louisiana 6 per cent stock, the bond that funded the Louisiana Purchase, on their books beginning in 1803.  
    According to Bayley, this loan was not issued until the first quarter of 1804.

    We suspect that difference in the reported timing of issues explains the discrepencies between the two series between 1918 and 1941.

3.  Certain securities, such as the Bounty Land Script, are not included in the Treasury's debt figures some years but 
    are included in others.
 
4.  From 1868 to 1890 our non-interesting bearing debt series is consistently below the Treasury's.  These dates are intriguing since
    in 1868 [ much happened ]  and in 1890 the Sherman Silver Purchase Act was enacted and a National Bank Notes line 
    item began to show up on the Treasury's monthly statements.  Never the less, we have been unable to track down the difference 
    between the two series for this period.
 
 
.. _FRED: http://research.stlouisfed.org/fred2/series/FYGFD

.. _TreasuryDirect: http://www.treasurydirect.gov/govt/reports/pd/histdebt/histdebt.htm

.. _1980 Annual Report: http://fraser.stlouisfed.org/docs/publications/treasar/AR_TREASURY_1980_2.pdf

.. _Public Debt 1790-1980.xlsx: http://people.brandeis.edu/~ghall/_build/data/Public%20Debt%201790-1980.xlsx

Acknowledgements
================

These databases grew out of joint work with Rose Razaghian.  

We thank the `Becker-Friedman Institute`_ of the University of Chicago and the
National Science Foundation (SES-0417519) for financial support. 
These databases are part of a project on fiscal imbalances sponsored 
by the Becker-Friedman Institute. 

We thank Senior Librarian Andrew Young at the U.S. Department of Treasury for locating and digitizing 
the complete set of the `Monthly Statements of the Public Debt`_ as well 
as pointing us to other useful documents.

We thank Alex Bargar, Jeffrey Cheng, Rahim Damji, Douglas McLaren, James Myatt, 
David Robertson, Ainie Tan, and Robertson Wang for outstanding research assistance.

.. _Becker-Friedman Institute: http://bfi.uchicago.edu/

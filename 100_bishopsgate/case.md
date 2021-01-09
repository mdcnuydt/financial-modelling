--- 
header-includes:
 - \usepackage[margin=0.75in]{geometry}
classoption: "10pt"
---

# Intro

100 Bishopsgate is a development in central London undertaken by a joint-venture between Brookfield Office Properties and Great Portland Estates. This analysis investigates the influence of the 2016 Brexit vote on the returns of this project.

- 90,000 square feet development
- Construction began in May 2015
- Initial completed date in 2018 but delayed to Q2 of 2019

As a result of Brexit, we believe that the rent-free periods, tenant improvements, leasing commissions, and months of downtime between tenants will all be higher than expected. At the same time, passing rents, the lease renewal probability, and annual rent and expenses increases will be lower than expected. We also expect Prime Office Yields in the City to rise from 4.25% currently to the 5.00% range over the next several years.

# Construction, Financing, and Exit Assumptions

- Land Plot Size: 7,500 square metres
- Land Price per Square Metre: £20,000 per square metre
- Floor Area Ratio (FAR): 12.0
- Rentable to Gross Area Ratio: 93.0%
- Hard Costs per Gross Square Metre: £8,000
- Soft Costs per Gross Square Metre: £1,000
- Construction Completion Date: 2019-04-30

The development was funded by a Construction Loan and Investor/Developer Equity with the following terms:
- Loan-to-Cost (LTC) Ratio: 60.0%
- Annual Interest Rate: 5.00% (fixed and capitalised)
- Issuance Fees: 1.00% (capitalised)
- Amortisation Period: N/A – Interest-only (capitalised)
- Loan Draws: Draw on the loan to cover Land Acquisition Costs, Hard Costs, Soft Costs,
- and the Replacement Reserves after the maximum amount of Equity has been drawn
- Maturity: Refinanced upon property completion
- Investor Equity Contribution: 87.5% (remainder from Developer)

We will allow for Exit Dates between May 2021 and April 2022; selling costs will be approximately 1.5% of the property value upon exit. In addition to the Hard Costs, Soft Costs, and Land Acquisition Costs, we will assume initial Replacement Reserves equal to the average years in a new lease times the annual Replacement Reserve amount. When the construction is complete, the Construction Loan will be refinanced with a Senior Loan and Mezzanine with the following terms:

 **Term**                     **Senior Loan**     **Mezzanine** 
 ----------                 ------------     ----------
 LTV ratio                  60%              10%           
 Annual cash interest rate  3.5%             4%            
 Annual PIK interest rate   N/A              4%            
 Amortisation period (yrs)  30               N/A           
 Tenor (yrs)                10               5             
 Equity pct upong exit      N/A              1%            
 Loan issuance fees         1%               1%            
 Prepayment penalty         1%               1%            

The property will not be stabilised upon construction completion, we will use the property’s value two years after construction completion and apply a 20% discount rate to determine the proper loan amounts.

Even one year after construction completion, the property will porbably not be fully stabilised – so we will get better results by going forward two years.

The lenders are seeking a minimum Cash Interest Coverage Ratio of 2.00x, a minimum Debt Service Coverage Ratio (DSCR) of 1.30x, and a minimum Debt Yield of 7.0%.


# Construction Timeline and Equity and Debt Draws

For the Land Acquisition Costs, Hard Costs, Soft Costs, and Replacement Reserves, I have already entered the monthly percentages at the top of the “Monthly” spreadsheet.

We won't factor in expense inflation to calculate the monthly numbers and assume that the totals and percentages have already been adjusted for inflation.

We will assume that Construction Loan Interest and Fees are capitalised during this period.

We will link the monthly interest expense to the beginning loan balance each month, and assume that
loan draws and issuance fees happen on the 1st of each month.

The maximum Debt and Equity amounts should reflect the total capitalised loan fees and interest during the construction period, which will create a circular reference – you can keep it in for now, but you will have to remove it later on.

#  Operating and Rent Roll Assumptions

There are three operational scenarios in this model: Downside (“Hard Brexit”), Base, and Upside (“Soft Brexit”). The scenarios differ as follows:

 **Assuption**                              **Upside**                           **Base**                             **Downside**                              
 -----------                              -----------                        ------------                       ----------------
 Office yield                             3.8% FY19;                         4.4% FY19,                         4.75% FY19,  
                                          3.6% FY20;                         up to 4.9% by FY23                 up to 5.8% by FY21;  
                                          3.1% FY23                                                             5.3% FY23
 Change in market rents                   6% FY19;                           3.5% FY19;                         (7%) FY19;  
                                          3.5% FY22-24                       3% FY22-24                         (1%) FY21; 
                                                                                                                0% FY22; 
                                                                                                                2.5% FY24
 Fixed rental esc                         2.5% FY19;                         2.25% FY19;                        1% FY19               
                                          3% FY20-21;                        up to 2.5% in FY21-24              up to 2.25% by FY24
                                          than 2.75%
 Expense growth rate                      1.5% FY18;                         1.5% FY18;                         1% FY18;                   
                                          2.5% FY22-23                       2% FY22-23                         1.5% by FY22-23
 Renewal probability                      60%                                50%                                40%                                       
 Downtime non-renewal                     6                                  9                                  12                                        
 New - Free rent                          7                                  10                                 13                                        
 Renewal - Free rent                      6                                  8                                  11                                        
 New - TI per sqm                         £10                                £15                                £20                                       
 Renewal - TI per sqm                     £5                                 £7                                 £10                                       
 New - LC % value                         2%                                 2.5%                               3%                                        
 Renewal - LC % value                     1%                                 1.5%                               2%                                        

For the other assumptions, all of which stay the same in different scenarios, we will use:
- Lease Term for New Tenants: 5 years
- Property Management Fees: 3.0% of Effective Gross Income
- Initial Annual Expenses & Taxes per Rentable Square Metre: £320.00
- Initial Annual Replacement Reserves per Rentable Square Metre: £20.00

The property will support three tenants, two of which (RBC and Jefferies) have already signed leases set to begin on 30 April 2019.

There is more uncertainty around the third tenant, we will assume that its lease will begin almost a year later, on 28 February 2020.

Here are the lease terms for each tenant:
- Tenant #1 – 41% of Rentable Square Metres
    * Lease Type: Triple Net (NNN) Lease (Tenant is responsible for Expenses & Taxes, but not
    * Management Fees or Reserves)
    * Lease Start Date: 2019-04-30
    * Lease Expiration Date: 2022-04-30
    * Initial Rent per Square Metre per Year (in April 2015): £850
    * Rent-Free Months on Initial Lease: 6

- Tenant #2 – 29% of Rentable Square Metres
    * Lease Type: Triple Net (NNN) Lease (Tenant is responsible for Expenses & Taxes, but not
    * Management Fees or Reserves)
    * Lease Start Date: 2019-04-30
    * Lease Expiration Date: 2023-04-30
    * Initial Rent per Square Metre per Year (in April 2015): £900
    * Rent-Free Months on Initial Lease: 9

- Tenant #3 – 25% of Rentable Square Metres
    * Lease Type: Gross Lease (Tenant pays no expenses)
    * Lease Start Date: 2020-02-28
    * Lease Expiration Date: 2026-02-28
    * Initial Rent per Square Metre per Year (in April 2015): £1,400
    * Rent-Free Months on Initial Lease: 15

Our formulas for the rental income and expenses for each tenant will be flexible enough to handle different lease start dates and expiration dates. However, we will assume that there is at most one lease expiration for each tenant in the holding period. We will split up the line items for each tenant into “Initial,” “Renewal,” and “Non-Renewal Cases,” and probability-weight the numbers in the last two cases.

# Property Pro-Forma

We will use the figures above to calculate everything down to Adjusted NOI on the Monthly Pro-Forma. We will pay special attention to the Vacancy and Expense Reimbursement assumptions as they relate to the lease start and expiration dates. We will reflect the initial funding for the Replacement Reserves in April 2019 when calculating the annual capital costs.

# Permanent Loan Refinancing and Equity and Mezzanine Returns

We will assume that the Construction Loan is refinanced with the Permanent Loans (the Senior Loan
and Mezzanine) when construction is complete. Our model will be flexible enough to handle different refinancing dates and exit dates. Since this is a monthly model, we will use the XIRR function to calculate the IRR to each investor group.

In the Equity Returns calculations, we will include the full impact of the Permanent Loan refinancing and its repayment upon exit, including any fees associated with these events. We will also include the Replacement Reserve in the calculations.

# Waterfall Returns Schedule with Lookback Provision

Great Portland Estates has contributed 12.5% of the required Equity in this deal, and Brookfield has contributed the remaining 87.5%. Up to a 15% project-level leveraged IRR, the cash flows will be distributed “pari passu” (i.e., in proportion to the initial Equity percentages invested).

When the leveraged IRR exceeds 15%, the Developer will receive a 10% promote. When the Equity multiple exceeds 2.0x, the Developer will receive another 10% promote. There are no catch-up provisions, but Brookfield has a lookback provision based on a 20% IRR target.

This provision states that at the end of the deal, if the Developer has achieved an IRR above 20%, but the Investor’s IRR is below 20%, the Developer will give up its proceeds to the Investor until the Investor achieves a 20% IRR.

We will need to write some VBA code to make the lookback provision work correctly. 

We will end by building some sensitivity tables.


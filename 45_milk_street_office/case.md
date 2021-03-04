# Intro 

Your firm, HYM Investment, is considering the acquisition and renovation of a 61,000 square-
foot mixed-used office/retail property in the Financial District of Boston (45 Milk Street).
The asking price for the property is $20.5 million USD, which represents an approximate 8.0%
Going-In Cap Rate, higher than the prevailing 7.5% Cap Rate for Class-B office properties in the
area due to the property’s age and less competitive amenities.

Your firm plans to spend 15% of the purchase price on major renovations, which are expected
to begin midway through 2019 and last for 2.5 years.
With fees, reserves, and renovation costs included, the effective purchase price will be closer to
$24 million.

45 Milk Street is currently only 82.5% occupied vs. an average 93.0% occupancy rate for similar
office properties in Boston.

Additionally, the property’s 5 current tenants (WeWork, Suffolk Construction, PTC, Safety
Insurance, and Trader Joe’s) are currently paying rent that’s ~10% below market rates due to
the building’s condition.

Your firm plans to boost the occupancy rate to the 90-100% range by attracting 1-2 new
tenants, and it plans to raise in-place rents to market rates when the existing tenants’ leases
expire in 2019 – 2022.
The Boston Office market has seen record rental growth and Cap Rate compression in the past
2 years, but your firm does not believe these growth rates are sustainable. You will create
Upside, Base, and Downside cases to account for the most likely outcomes.

The deal will be financed at a 75% LTV, with 65% for the Senior Loan and 10% for the
Mezzanine. HYM Investment plans to contribute 10% of the required Equity, and its Limited
Partners will contribute the remaining 90%.
The Limited Partners will earn an 8% Preferred Return, and the General Partners (HYM
Investment) will receive a 20% Catch-Up Return; after that, cash flows will be split 80 / 20
between the LPs and GPs.
Your job is to model the acquisition and renovation, calculate the returns to each investor
group, and make an investment recommendation at the end.

# Acquisition, Financing, and Exit Assumptions

Use the following figures to set up the key model assumptions:

- Gross Square Feet of Property: 61,000
- Rentable to Gross Area: 90.0%
- GP / LP Equity Split: 10% / 90%
- Acquisition Date: 2018-12-31
- Acquisition Price: $20.5 million
- Acquisition Costs: 1.0%
- Renovation Costs % Acquisition Price: 15.0%
- Additional Reserves % Acquisition Price: 1.0%

You should allow for Exit Dates of December 2021 and December 2022; selling costs will be
approximately 2.0% of the property value upon exit.

The Senior Loan and Mezzanine used to fund the deal have the following terms:

| Term                      | Senior Loan                                         | Mezzanine |
| ---                       | ---                                                 | ---       |
| Loan-to-Value (LTV) Ratio | 65.0%                                               | 10.0%     |
| Holdback Amount           | Renovation Costs + Additional Reserves              | None      |
| Annual Holdback Release   | $35.00 / RSF / Year (Begins when renovation begins) | N/A       |
| LIBOR Spread              | 3.00%                                               | N/A       |
| LIBOR Floor               | 1.75%                                               | N/A       |
| Fixed Cash Interest Rate  | N/A                                                 | 3.00%     |
| Fixed PIK Interest Rate   | N/A                                                 | 6.00%     |
| Interest-Only Period      | 2 years                                             | N/A       |
| Amortization Period       | 30 years                                            | N/A       |
| Tenor                     | 5 years                                             | 5 years   |
| Loan Issuance Fees        | 1.00%                                               | 1.00%     |
| Prepayment Penalty        | 1.00%                                               | 1.00%     |


The Holdback exists because the renovation funding is not part of the initial acquisition price.
Assume a monthly release into the property’s Replacement Reserve balance until the entire
Holdback has been allocated.

For the Senior Loan, assume that the 3-month LIBOR increases from 2.60% in FY 18 to 3.80% in
FY 22.

The lenders are seeking a minimum Cash Interest Coverage Ratio of 1.50x, a minimum Debt
Service Coverage Ratio (DSCR) of 1.20x, and a minimum Debt Yield of 7.0%.

# Operating and Rent Roll Assumptions

In this model, the Upside case represents strong, continued growth with an eventual 100.0%
occupancy rate, the Base Case represents slightly lower growth with an eventual 92.5%
occupancy rate, and the Downside Case represents a modest recession and recovery, with the
same 82.5% occupancy rate the property currently has.

The scenarios differ as follows:

| Assumption                                            | Upside                        | Base                          | Downside                                       |   |
| ---                                                   | ---                           | ---                           | ---                                            |   |
| Class-B Office/Retail Rap Rates                       | 7.25% in FY 19; 6.75% by FY22 | 7.25% in FY 19; 7.00% by FY22 | 7.25% in FY 19; 8.00% by FY 20; 7.25% by FY 22 |   |
| Change in Market Rents                                | Cfr Excel                     | Cfr Excel                     | Cfr Excel                                      |   |
| Fixed Annual Rental                                   | Cfr Excel                     | Cfr Excel                     | Cfr Excel                                      |   |
| Escalations                                           | Cfr Excel                     | Cfr Excel                     | Cfr Excel                                      |   |
| Expense Growth Rate                                   | Cfr Excel                     | Cfr Excel                     | Cfr Excel                                      |   |
| Retail Sales Growth Rate                              | Cfr Excel                     | Cfr Excel                     | Cfr Excel                                      |   |
| Renewal Probability                                   | 70%                           | 60%                           | 50%                                            |   |
| Nr Downtime Months for Non-Renewal                    | 3                             | 6                             | 9                                              |   |
| New Tenants – Months of Free Rent                     | 2                             | 3                             | 4                                              |   |
| Renewal Tenants – Months of Free Rent                 | 1                             | 2                             | 3                                              |   |
| New Tenants – Tenant Improvements per Rentable SF     | $35.00                        | $45.00                        | $55.00                                         |   |
| Renewal Tenants – Tenant Improvements per Rentable SF | $15.00                        | $20.00                        | $25.00                                         |   |
| New Tenants – Leasing Commissions % Lease Value       | 5%                            | 6%                            | 7%                                             |   |
| Renewal Tenants – Leasing Commissions % Lease Value   | 2%                            | 3%                            | 4%                                             |   |
| Tenant #6 Lease Start Date                            | 2020-01-31                    | 2020-06-30                    | N/A                                            |   |
| Tenant #7 Lease Start Date                            | 2021-01-31                    | N/A                           | N/A                                            |   |

The maximum Cap Rate in this market over the past 4-5 years was 8.0%, and it rose to 9.0% in
the last recession. The other figures above are all in-line with market data.

For the other assumptions, all of which stay the same in different scenarios, please use:

- Lease Term for New Tenants: 5 years
- Property Management Fees: 3% of Effective Gross Income
- Common Area Maintenance (CAM) per RSF per Year: $2.50
- Insurance per RSF per Year: $1.00
- Real Estate Taxes % Property Value: 2.55%
- Replacement Reserves per RSF per Year: $3.00
- Common Area Utilities per RSF per Year: $2.00

Since this is a mixed-use office/retail property, the tenants have primarily Triple Net (NNN)
leases, but a few have variations such as Full Service (FS), Double Net (NN), and Percentage
Rent leases.

Here’s the information for each tenant – note that the Market Rent and “Escalated Rent Paid by
Initial Tenant” figures are as of the start of FY 18, so you should escalate them appropriately in
each month of the model:

| Tenant Name  | % Rentable SQ Occupied | Init Lease Start Date | Init Lease Term | Init Lease Annual Rent Esc | Init Lease RF Months | Market Rent/SF/yr | Init Lease Esc Rent/SF/Yr |
| ---          | ---                    | ---                   | ---             | ---                        | ---                  | ---               | ---                       |
| WeWork       | 25.0%                  | 2015-10-31            | 5 years         | 2.50%                      | 6                    | $47.00            | $43.00                    |
| Suffolk Cons | 15.0%                  | 2017-10-31            | 4 years         | 3.00%                      | 4                    | $49.00            | $45.00                    |
| PTC          | 10.0%                  | 2015-06-30            | 4 years         | 2.50%                      | 4                    | $46.00            | $43.00                    |
| Safety Ins   | 12.5%                  | 2016-12-31            | 6 years         | 2.00%                      | 5                    | $48.00            | $44.00                    |
| Trader Joe's | 20.0%                  | 2016-06-30            | 5 years         | 3.00%                      | 6                    | $48.00            | $42.00                    |
| Tenant #6    | 10.0%                  | Assumptions           | 5 years         | Assumptions                | Assumptions          | $60.00            | $60.00                    |
| Tenant #7    | 7.5%                   | Assumptions           | 5 years         | Assumptions                | Assumptions          | $56.00            | $56.00                    |


And here is the information for each tenant’s lease type:

| Tenant Name      | Lease Type            | Init Retail Sales/SF/yr | Init Breakpoint               | % Rent beyond breakpoint | Monthly Distribution of Retail Sales |
| ---              | ---                   | ---                     | ---                           | ---                      | ---                                  |
| WeWork           | NNN                   | N/A                     | N/A                           | N/A                      | N/A                                  |
| Suffolk Cons     | NNN                   | N/A                     | N/A                           | N/A                      | N/A                                  |
| PTC              | NNN                   | N/A                     | N/A                           | N/A                      | N/A                                  |
| Safety Insurance | NNN                   | N/A                     | N/A                           | N/A                      | N/A                                  |
| Trader Joe's     | NNN + Percentage Rent | $800.00                 | $500,000                      | 4.0%                     | See Excel                            |
| Tenant #6        | FS                    | N/A                     | N/A                           | N/A                      | N/A                                  |
| Tenant #7        | NN + Percentage Rent  | $900.00                 | FY18 Base Rental Income/5%/12 | 5.0%                     | See Excel                            |


With Triple Net (NNN) leases, the tenant is responsible for CAM, Common Area Utilities,
Insurance, and Property Taxes; with Double Net (NN) leases, the tenant is responsible only for
Insurance and Property Taxes.

Assume that Trader Joe’s retail sales grow on an annual basis and that this $500,000 artificial
breakpoint also grows on an annual basis, linked to the retail sales growth rate.

Tenant #7 also pays Percentage Rent; if Tenant #7’s monthly retail sales exceed its “natural
breakpoint” (described above), it will owe 5% of the excess amount.

This natural breakpoint will also increase annually along with retail sales.

Your formulas for each tenant should be flexible enough to handle different lease start dates
and expiration dates, including dates both inside of and outside the holding period.

However, you may assume that there is at most one lease expiration for each tenant in the
holding period – otherwise, it gets very difficult to model without using ARGUS.

# Property Pro-Forma

Use the figures above to calculate everything down to Adjusted NOI on the Monthly Pro-Forma.

Pay special attention to the Replacement Reserves since they work differently in this model –
you must add the TI/LC/CapEx Holdback as it is released.

Once you’ve finished the Monthly Pro-Forma, create the annual summary down to the Adjusted
NOI line.

# Debt Service and Returns to Equity Investors and Lenders

Next, project the property’s Debt Service, including the Cash and PIK Interest, the Principal
Repayments, and the release of the Holdback.

Note that the Senior Loan Interest is based on the ENTIRE amount of the Senior Loan, even
though a significant portion of it is held back when the deal first closes.

The Holdback affects only the Senior Lenders’ basis (and, therefore, their IRR). It does NOT
affect the Interest Expense or the Principal Repayments.

You do not need to project the Debt Service on a monthly basis; annual numbers are fine.

Finally, calculate the returns to Equity Investors, Senior Lenders, and Mezzanine Investors at the
bottom.

Your model should support different exit dates and the possibility that the lenders may not be
repaid in full.

# Waterfall Returns Schedule with Preferred Return and Catch-Up Provisions

The Limited Partners will contribute 90% of the required Equity in this deal, and HYM
Investment (the General Partners) will contribute the remaining 10%.

The Limited Partners receive a Preferred Return up to an 8% IRR, meaning that all cash flows go
to them until they have earned an 8% IRR.

Once the LPs have earned this 8% IRR, the GPs will receive a “Catch-Up Return” up to a 20%
IRR, which means that all cash flows in this next tier will go to the GPs until they have earned a
20% IRR.

After that, the cash flows will be split 80% to the LPs and 20% to the GPs.

Assume that all returns are cumulative and compounded on an annual basis.

Once you’re finished, create sensitivity tables at the bottom that show the IRRs to GPs and LPs
under different scenarios, Exit Cap Rates, and acquisition prices. Use your judgment for the
ranges.


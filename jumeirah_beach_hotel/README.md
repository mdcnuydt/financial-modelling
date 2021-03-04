# Intro

Your firm is considering acquiring and renovating the Jumeirah Beach Hotel, a leading 5-star luxury hotel in Dubai. It may also convert the hotel into a franchise property and pay for it to join a group such as Hilton, Marriott, or InterContinental. 

The hotel has 618 rooms, including both standard-sized rooms and larger villas and suites. It also features 21 on-site restaurants and bars, as well as swimming pools, a fitness center, and free guest access to a nearby water park. 

Your firm is planning to acquire the hotel for approximately $228 million USD, spend $20-25 million on the renovation over two years, and then sell the property after a 3-5-year holding period. 

The initial acquisition will be funded at a 65% LTV Ratio, with an all-PIK loan at an 8% fixed interest rate. No other groups besides your firm will contribute equity. 

The renovation will take place over FY 17 and FY 18, and the costs will be distributed evenly over that time frame. However, 25% of the rooms will be unavailable in FY 17, and 50% will be unavailable in FY 18 due to the order and timing of the project. 

Upon renovation completion, your firm will refinance the Acquisition Loan with a set of Permanent Loans, including a Senior Loan at 75% LTV and Mezzanine at an additional 10% LTV.

The market-wide occupancy rate for 5-star hotels in Dubai is 85%, and the market-wide ADR is $450. Several scenarios are possible, but most observers expect these figures to decline for 1-2 years before increasing in the later years of the holding period. 

Currently, the Jumeirah Beach Hotel’s occupancy rate is 78% with an ADR of $350. Your firm believes it can boost both these numbers with a renovation. 

If your firm keeps the hotel independent, it will pay less for the renovation and incur lower expenses going forward, but the property’s occupancy rate and ADR will be lower. 

If the hotel joins a franchise, your firm will pay more for the renovation and incur higher operating expenses, but the property’s occupancy rate and ADR will be higher. 

The Exit Cap Rate will also be lower in the franchise scenario because franchise hotels can attract repeat customers more easily. 

You plan to hold the hotel for 3-5 years (build in exit options for any of those dates), start the renovation in FY 17, and finish it in FY 18. 

# Acquisition, Financing, and Exit Assumptions

- Acquisition Date: 2016-12-31
- Going-In Cap Rate: 9.5% (assume 3% NOI growth over FY 16 NOI to calculate)
- Acquisition Costs: 4.0% of Acquisition Price

- Renovation Start Date: Immediately following acquisition close
- Nr of Renovation Years: 2
- Renovation Factor: 25% of rooms will be unavailable in Year 1, and 50% in Year 2

For simplicity we will not build in support for a variable renovation start date, # of years, or renovation factor. 

| Term                | Acquisition Loan | Senior Loan | Mezzanine |
| ---                 | ---              | ---         | ---       |
| Loan-to-Value (LTV) | 65.0%            | 75.0%       | 10.0%     |
| Cash Interest Rate  | N/A              | 3.50%       | 4.00%     |
| PIK Interest Rate   | 8.00%            | N/A         | 4.00%     |
| Issuance Fees       | 1.50%            | 1.00%       | 1.00%     |
| Amortization Period | N/A              | 30 yrs      | N/A       |
| Maturity            | 10 yrs           | 10 yrs      | 5 yrs     |

The Permanent Loan investors are seeking a minimum Debt Yield of 10.0%, Interest Coverage Ratio of 2.00x, and Debt Service Coverage Ratio (DSCR) of 1.50x.

We will build in support for variable exit years and assume that the property may be sold at the end of FY 19, FY 20, or FY 21. We will assume Selling Costs of 2.0% and the following trends for Cap Rates, which vary based on the operational scenario (Independent or Franchise):

| Scenario    | FY17  | FY18  | FY19  | FY20  | FY21  |
| ---         | ---   | ---   | ---   | ---   | ---   |
| Independent | 9.70% | 9.40% | 9.25% | 9.10% | 9.00% |
| Franchise   | 9.60% | 9.25% | 8.95% | 8.70% | 8.50% |

These Cap Rates represent a continued recession/downturn in the first year, followed by a recovery after that. Historically, Cap Rates for 5-star hotels in Dubai have ranged between 8.0% and 10.0%.

# Operating Assumptions

The property’s operational performance depends on overall market trends as well as whether it continues to operate independently or becomes part of a franchise. Use the following assumptions for the historical (FY 16) values for each line item:

- Market Average Daily Rate (ADR): $450.00
- Market Occupancy Rate: 85.0%
- Property’s Occupancy Rate: 78.0%
- Property’s ADR: $350.00
- Food & Beverage Revenue per Occupied Room Night: $125.00
- Other Revenue per Occupied Room Night: $25.00

- Utilities per Occupied Room Night: $10.00
- Insurance per Available Room per Year: $1,500
- Property Taxes per Available Room per Year: $0 (There are no property taxes in the
- UAE – just taxes on the initial acquisition)
- Ground Lease: $15,563,120 per year

For the revenue and expense growth rates, the market occupancy rates, and the market ADR growth rates, please follow the assumptions that have already been input into Excel. The market downturn in Dubai is expected to last for another 1-2 years; at that point, growth will resume, and these metrics will return to their normal levels (e.g., 2-3% annual growth). This recovery happens most quickly in the Upside Case, most slowly in the Downside Case, and in between those two in the Base Case. For the assumptions that change based on the operational scenario, please use the following figures:

| Assumption                     | Independent               | Franchise                 |
| ---                            | ---                       | ---                       |
| Property Occupancy             | 95% of Market Occupancy   | 100% of Market Occupancy  |
| Property ADR % Market ADR      | 90% of Market ADR         | 95% of Market ADR         |
| Renovation Costs per Key       | $35,000                   | $40,000                   |
| Management Fee                 | 2.0% of Revenue           | 3.0% of Revenue           |
| franchise Fee                  | N/A                       | 3.0% of Revenue           |
| NOI Margin Hurdle for Mgmt Inc | 20.0%                     | 30.0%                     |
| Incentive Fee                  | 30.0% of NOI Above Hurdle | 20.0% of NOI Above Hurdle |
| Room Margin                    | 81.0%                     | 81.0%                     |
| F&B Margin                     | 25.0%                     | 25.0%                     |
| Other Revenue Margin           | 11.0%                     | 11.0%                     |
| Administrative & General       | 5.0%                      | 6.0%                      |
| Sales & Marketing              | 7.0%                      | 8.0%                      |
| Repairs & Maintenance          | 3.5%                      | 3.5%                      |
| Initial FF&E Reserves          | 2,100 per Available Room  | 2,300 per Available Room  |

Broadly speaking, the hotel will be more expensive to operate in the “Franchise” scenario because it will have to pay additional fees to the franchisor, and it will have to spend extra on sales & marketing, renovations, and other initiatives to comply with the rules. However, it may also attain a higher Occupancy Rate and ADR since the brand association will provide access to a large pool of existing customers.

# Property Pro-Forma

Complete the historical Pro-Forma, which has some of the expenses filled in, down to Adjusted NOI. Pay close to attention to the key drivers for each line item, since they differ substantially, and to whether or not the hotel is currently undergoing renovation. If it is, its revenue should be significantly lower, and items such as the Franchise Fee and Incentive Fee to Management should not exist. It’s easiest to account for this by modifying the “Occupied Room Nights” line item to reflect the Renovation Factor each year. For some of the items, you will have to check the date against the renovation start and end dates.

# Debt Service, Permanent Loan Refinancing, and Equity Returns

Project the interest and principal repayments using the IPMT and PPMT functions, and make sure you account for Cash vs. PIK Interest.Always use the beginning balances to calculate interest so that you avoid circular references. Your model should support different refinancing dates for the Acquisition Loan, and you should check the renovation date before calculating interest and principal repayments. When you’re done, calculate the returns to equity investors, including the leveraged IRR, the cash-on-cash multiple, and the annual yield on initial investment. You do NOT need to calculate the unleveraged (or other) IRR or create a waterfall structure.

# Sensitivities

Finally, create sensitivity tables at the top of the spreadsheet for the equity IRR under different operational and market scenarios and different exit dates. At the bottom, create sensitivity tables for the Acquisition Loan and Senior Loan LTVs vs. the respective interest rates, the Going-In Cap Rate vs. Exit Cap Rate, and the Property Occupancy Rate vs. Property ADR. Pick numerical ranges that make sense based on the assumptions and historical trends described in this document.


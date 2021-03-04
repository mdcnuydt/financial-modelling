# Intro

Cyrela Brazil Realty, a leading property developer, has recently announced plans to develop a
33-floor tower of super-high-end luxury condominiums in São Paulo with a potential sale value
of R$ 538 million ($165 million USD) before inflation.

Your firm, one of the company’s Limited Partners, is considering funding the development as a
3rd party investor.

Each condominium will take up an entire floor of the tower, with an average size of
approximately 582 square meters (6,265 square feet), and all the condo units will take up
19,209 square meters altogether.

The Developers plan to begin pre-construction in January 2018, finish construction in May 2021,
and open the property for move-ins in November 2021.

The land will cost approximately R$ 16 million, with total Hard Costs, Soft Softs, and FF&E and
Move-In Costs of approximately R$ 448 million (before inflation).

The property development will be divided into three phases, and certain percentages of units
must be pre-sold in each phase for construction to begin and for the next phase to begin.

The Equity and Debt draws will be based on the percentage of total units that are pre-sold;
lenders will commit to the deal only after they have seen strong interest from buyers and
significant Equity invested by the Developer and LPs.

Clients will make an upfront deposit for 30% each condo unit’s value, pay 30% when
construction ends, and pay the remaining 40% upon move-in.

The Limited Partners will contribute 80% of the required Equity, with Cyrela contributing the
rest. The LPs will earn a Preferred Return up to 1x invested equity, followed by a Catch-Up
Return of 1x invested equity for the Developer.

Returns will be split pari passu up to a 20% IRR. Between a 20% IRR and a 3.0x equity multiple,
the Developers will receive a 10% promote, with another 10% promote above a 3.0x equity
multiple.

# Construction, Timeline, and Financing Assumptions

Use the following figures to set up the key model assumptions:

|                        | Phase I | Phase II | Phase III |
| ---                    | ---     | ---      | ---       |
| Starting Month #:      | 1       | N/A      | N/A       |
| Nr construction months | 24      | 24       | 24        |
| Units for Sale:        | 10      | 11       | 12        |
| Average Unit Size:     | 565 SqM | 577 SqM  | 601 SqM   |

Following completion of the Phase III construction, the property-wide post-construction phase
will take approximately 6 months to finish. When that phase is done, move-ins will take place.

In each phase, 30% of the units must be pre-sold before construction can begin. For the next
phase to begin, 70% of the units in the phase must be pre-sold.

The Limited Partners will not fund any project that takes more than 6 years to complete.

- Construction Start Month: 2018-01-31
- Condo Unit to Gross Square Meters: 90%
- Floor Area Ratio (FAR): 4.0
- Land Price per Lot Square Meter: R$ 3,000
- Lot Upfront Deposit: 50%, paid in Month #1
- Remaining Lot Payment: Paid in Month #6
- Hard Costs per Gross Square Meter: R$ 15,000
- Soft Costs per Gross Square Meter: R$ 3,500
- FF&E and Move-In Costs % Monthly Sales: 10.0%
- Condo Selling Price per Square Meter: R$ 28,000
- Upfront Client Payment: 30%
- Client Payment Upon Construction End: 30%
- Client Payment Upon Move-In: 40%

These prices and expenses are far above the normal levels for luxury condos in Brazil, but these
units will be the highest-end ones in the country.

Each unit has five rooms, six bathrooms, five suites, and six parking spots, which accounts for
the significantly higher costs.

The Hard Costs will be distributed evenly over the total number of construction months in the
project, while the Soft Costs will follow the fixed percentages that have been entered into
Excel. The final 10% of the Soft Costs will be paid when the post-construction phase ends.

The development will be funded by Investor and Developer Equity and a Construction Loan.
Fifty percent (50%) of the total units in the property must be pre-sold before Construction
Loan draws are allowed.

The Construction Loan will carry a 10% fixed interest rate, and interest will be capitalized when
there is insufficient cash flow to pay for it.

You may assume that positive cash flows generated during the holding period are used to repay
the Construction Loan. The entire remaining Loan balance must be repaid when the property-
wide post-construction phase finishes and move-ins take place.

The luxury condo market, as well as the housing market as a whole, have not performed well in
São Paulo over the past several years due to the recession in Brazil, during which the GDP
contracted by more than 7% over two years.

However, Cyrela believes that the market is now at a turning point, with GDP growth and luxury
home spending both set to increase. To account for the potential outcomes, you will build in
support for the following three scenarios:

| Assumption                   | Upside | Base | Downside |
| ---                          | ---    | ---  | ---      |
| Sales Velocity per Month     | 1.5    | 1.0  | 0.5      |
| Annual Sales Price Inflation | 4.0%   | 2.5% | 1.0%     |
| Annual Expense Inflation     | 3.0%   | 2.5% | 2.0%     |

A Sales Velocity assumption such as 0.5 means that it takes an average of two months to sell a
single unit.

Use the following IRR and equity multiple hurdles to distribute the cash flows:

- Preferred Return: The Investors will earn back 1.0x of their invested equity, based on
- total cash flows to equity investors, before anyone else.
- 
- Catch-Up Return: Next, the Developers will earn back 1.0x of their invested equity
- based on the cash flows remaining after the Preferred Return.
- 
- Equity Multiple Above 1.0x And IRR Below 20%: 80% Investors / 20% Developers.
- 
- Equity IRR Above 20% But Multiple Below 3.0x: 70% Investors / 30% Developers.
- 
- Equity Multiple Above 3.0x: 60% Investors / 40% Developers.

# Monthly Cash Flows

Start by projecting the number of units sold in each month in each phase of the project, as well
as the total value of condo units sold and the construction status.

The trickiest part of this exercise will be determining the start months of Phases II and III. Hint:
You will have to use an INDEX function inside a MATCH function to do this.

Calculate everything down to Gross Income in the Monthly Cash Flows schedule.

# Equity & Debt Draws

Equity will be drawn first because 50% of the total units in the property must be pre-sold
before lenders will fund the Construction Loan.

If any Debt is remaining when the post-construction phase finishes, assume that additional
Equity is drawn to repay it.

Use the monthly interest rate to calculate the interest expense and use the beginning balance
to avoid circular references. “Cash Flow After Interest, Before Draws” should pay for the
monthly interest. Any interest it cannot cover will accrue to the Construction Loan.

No loan draws are allowed in the final month (when the post-construction phase ends).

If “Cash Generated After Equity & Debt Draws” is positive, assume repayment of the
Construction Loan principal.

# Waterfall Returns Schedule

Distribute the cash flows according to the instructions above, and make sure that you use
either IRR hurdles or equity multiple hurdles depending on the tier.

Hint: The “Investor Accruals” formula will change for tiers based on equity multiple hurdles, but
the other formulas will be the same or nearly the same.

The “Investor Injections” line item will also change based on whether you’re in the Preferred
and Catch-Up Distribution tiers or tiers 1-3.

# Annual Summary and Sensitivities

When you’re done with the monthly model, create an annual summary that presents the key
line items over a 7-year period. The last few years will be blank in most cases, but they are
there in case the project takes longer than expected to finish.

Then, create sensitivity tables showing the IRR to the Investors and Developers based on the
Scenario, the Sales Velocity per Month, the Months in the Construction Period, the Condo
Selling Prices, and the Hard Costs.

Use your judgment and the data in this document to pick appropriate ranges for the tables.


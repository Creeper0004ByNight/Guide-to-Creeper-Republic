# Content
- [Banking](https://github.com/Creeper0004ByNight/Guide-to-Creeper-Republic/blob/master/Initiatives.md#banking)
  - [Loans](https://github.com/Creeper0004ByNight/Guide-to-Creeper-Republic/blob/master/Initiatives.md#loans)
  - [Investment banking](https://github.com/Creeper0004ByNight/Guide-to-Creeper-Republic/blob/master/Initiatives.md#investment-banking)
- [National Resources](https://github.com/Creeper0004ByNight/Guide-to-Creeper-Republic/blob/master/Initiatives.md#national-resources)
- [Initiatives](https://github.com/Creeper0004ByNight/Guide-to-Creeper-Republic/blob/master/Initiatives.md#initiatives)
  - [Subsidies](https://github.com/Creeper0004ByNight/Guide-to-Creeper-Republic/blob/master/Initiatives.md#subsidies)
  - [Grants](https://github.com/Creeper0004ByNight/Guide-to-Creeper-Republic/blob/master/Initiatives.md#grants)

# Banking
## Loans

  Ammount | Interest | Minimum Networth (in millions) | Available?
  ------- | -------- | ------------------------------ | ----------
  $100k-$500k | 1% | 50 | Yes
  $500k-$10m | 2% | 100 | Yes 
  $10m-$100m | 5% | 500 | Yes
  $100m-500m | 10% | 2,000 | Citizens only
  500m-1b| 20% | 5,000 | Unvailable
  
  The total accumulated interest plus loan is given by this formular:
  ```
  P' = P(1+i)^t
  ```
  Where:
  - **P** is the original principal sum (the original loan)
  - **P'** is the new principal sum (loan plus interest)
  - **i** is the interest rate coverted to a decimal value (25%=0.25)
  - **t** is the overall length of time in weeks the interest is applied

  For example, a $100 loan for one month with a weekly interest rate of 5%:
  ```
  $121.55 ≈ 100(1+0.05)^4
  ```

## Investment banking

investment time | interest rate
--------------- | -------------
1 week | 1%
2 weeks | 2.5%
3 weeks | 3.5%
1 month | 4.5%
2 months | 9.5%
3 months | 15%
  
# National Resources
National resources are assets produced by state owned companies and sold for a low price or given away for free. Currently the only national resource that is available is oil. In the near future, energy, coal and others will be available as a national resource.

Resource | Weekly limit | Price | available | in reserve
-------- | ------------ | ----- | --------- | ----------
Oil | 1,000,000 | $0 | 1b | 1b
Energy |  | $7.50 | 0 | 0
Coal |  | $0.05 | 0 | 0 | 0

In the event of a crisis, surge in global demmand or other circumstances reserves will be made available and prioritized to citizens and permanet residents.

# Initiatives
## Subsidies

### New Corporation Subsidie
  Rewards:
  - -1% loan interest or less, so that the interest is 0%. 
  - +20 to 40% increase of the sale price when selling to the government.

  Conditions:
  - The Corporation must be, either;
    - at most 1 month old, or
    - have reincorporated less than a week ago and have no sister companies.
  - Cannot be an umbrella company.

## Grants

### Logistics Grant
  Rewards:
  - Compensation for the price of one logistics center upon construction.

  Conditions:
  - Company must have a networth of less than $2,000,000,000.
  - Cannot be an umbrella company.

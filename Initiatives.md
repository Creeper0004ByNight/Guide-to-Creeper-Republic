# Loans

  Ammount | Interest | Minimum Networth (in millions) | Available?
  ------- | -------- | ------------------------------ | ----------
  $100k-$500k | 1% | 50 | Yes
  $500k-$10m | 2% | 100 | Yes 
  $10m-$100m | 5% | 500 | Yes
  $100m-500m | 10% | 2,000 | Citizens only
  500m-1b| 20% | 5,000 | Unvailable
  
### Interest
  The total accumulated amount to repay is given by this formular:
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


# Subsidies

### New Corporation Subsidie
  Rewards:
  - -1% loan interest or less, so that the interest is 0%. 
  - +20 to 40% increase of the sale price when selling to the government.

  Conditions:
  - The Corporation must be, either;
    - at most 1 month old, or
    - have reincorporated less than a week ago and have no sister companies.
  - Cannot be a sister company.

# Grants

### Logistics Grant
  Rewards:
  - Compensation for the price of one logistics center upon construction.

  Conditions:
  - Company must have a networth of less than $2,000,000,000.
  - Cannot be a sister company.


# 1a. Finding Sum Budgets of INR (₹) and USD ($):
=SUMIF(Movies[[#All],[industry]],"Bollywood",Movies[[#All],[budget (INR)]])

=SUMIF(Movies[[#All],[industry]],"Hollywood",Movies[[#All],[budget (USD)]])

# 1b. Finding Sum Revenues of INR (₹) and USD ($):

=SUMIF(Movies[industry],"Bollywood",Movies[revenue (INR)])


=SUMIF(Movies[industry],"Hollywood",Movies[revenue (USD)])

### To compare the financial performance and profitability of Hollywood and Bollywood based on the provided figures, we need to calculate the profitability margins for both. Here’s how we can approach it:

####  **Profitability Formula:**
Profitability can be measured using the **Profit Margin**, which is calculated as:


###  **Calculating Hollywood's Profit Margin (USD):**

- **Budget (Hollywood)** = $3,069.58
- **Revenue (Hollywood)** =  $18,577.90

Profit Margin (Hollywood) = \frac{ $18,577.90 -$3,069.58}{$18,577.90} \times 100


Profit Margin (Hollywood) = \frac{15,508.32}{$18,577.90} \times 100 \approx 83.5\%
\

###  **Calculating Bollywood's Profit Margin (INR):**

- **Budget (Bollywood)** = ₹18,630.00
- **Revenue (Bollywood)** = ₹80,909.00

Profit Margin (Bollywood) = \frac{80,909.00 - 18,630.00}{80,909.00} \times 100



Profit Margin (Bollywood) = \frac{62,279.00}{80,909.00} \times 100 \approx 77.0\%
\

###  **Comparison and Conclusion:**

- **Hollywood Profit Margin:** 83.5%
- **Bollywood Profit Margin:** 77.0%



# 2. MARVEL STUDIOS PRODUCTION
### Here are the formulas used to calculate each of the key metrics from the **Marvel Consolidated P&L**:

| **Key Metric**      | **Formula**                                                                                 | **Value**         |
|---------------------|---------------------------------------------------------------------------------------------|-------------------|
| **Revenue**         | Given (9,054.60 million)                                                                    | **$9,054.60 million** |
| **Budget**          | Given (1,988.70 million)                                                                    | **$1,988.70 million** |
| **Profit/Loss**     | Revenue - Budget = 9,054.60 - 1,988.70                                                      | **$7,065.90 million** |
| **Profit/Loss %**   | (Profit/Loss / Budget) × 100 = (7,065.90 / 1,988.70) × 100                                | **355%**           |
| **Market Share %**  | (Marvel Revenue / Total Hollywood Revenue) × 100 = (9,054.60 / 19,589.26) × 100            | **46%**            |

These formulas show how the **Profit/Loss**, **Profit Margin (Profit/Loss %)**, and **Market Share** are calculated based on the provided figures for Marvel Studios.


# 3. MEAN, MEDIAN & MODE
- Mean (Average)
The mean is calculated by summing all the values in the dataset and dividing by the total number of data points.




- Median (Middle Value)
The median is the middle value when the data is sorted in ascending order. If the dataset has an odd number of values, the median is the middle value. If there is an even number of values, the median is the average of the two middle values.


- Mode (Most Frequent Value)
The mode is the value that occurs most frequently in the dataset.

  - Steps to Calculate Mode:
Step 1: Identify the most frequent value in the dataset.
From the sorted list





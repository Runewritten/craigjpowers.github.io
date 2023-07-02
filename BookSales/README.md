# Analysis: The Impact of Author Gender on Book Sales in Fiction

![](Images/books.jpg)
---

## Introduction
This analysis was performed to determine whether there is any gender bias in fiction book sales that would necessitate the use of pseudonyms. The analysis includes a regression model based on publicly available dataset of bestselling authors.

---

## The Question

Are book sales impacted enough by an author's gender as to demand a psuedonym?


## The Data

Our population of interest is all fiction books sold.

Our sample data includes 50 book listings across five genres, pulled from the quarterly listings on Publisher’s Weekly from October 2020 to Jan 2021. (Publishers Weekly, 2021) This data includes book title, author name (from which we will determine gender assumption), publisher, page count, price, publishing date, and total units sold over the period.

### The Variables

**Dependent Variable**: 
- Total Books Sold

**Independent Variables**:

- Gender
- Price
- Page Count
- Review Rating
- Prior # of Books written by Author
- Genre (Fantasy, Romance, Mystery, Sci-fi, Religious)

---

## Analysis

### T-Test
*We used the separate-variance t-test to test our two sample means of books sold by women versus books sold by non-women, after having failed the F-test to use pooled variance. With an alpha level of .05, the p-value (.1727) for our one-tailed test fails to reject the null hypothesis, H0 = µ1 >= µ2, so we’re left with insufficient evidence to reject the hypothesis that women sell at least as many books as non-women so far.*

### Correlations


## Conclusion

### Recommendations



R Markdown Christmas Cookies
================
Caroline Himbert and Tierney O’Sullivan
Tue Dec 09, 2025 12:48:13

- [R Markdown Christmas Cookies](#r-markdown-christmas-cookies)
  - [Christmas Sugar Cookies](#christmas-sugar-cookies)
    - [Ingredients](#ingredients)
    - [Instructions](#instructions)
  - [R Code Example: Scaling the
    Recipe](#r-code-example-scaling-the-recipe)
  - [Output Table](#output-table)
  - [Final Notes](#final-notes)

# R Markdown Christmas Cookies

This festive R Markdown document demonstrates how you can combine text,
code, and tables — with a Christmas cookie recipe as an example.

## Christmas Sugar Cookies

These classic sugar cookies are simple, delicious, and perfect for
decorating.

### Ingredients

- 2 3/4 cups all-purpose flour
- 1 teaspoon baking soda
- 1/2 teaspoon baking powder
- 1 cup unsalted butter (softened)
- 1 1/2 cups white sugar
- 1 egg
- 1 teaspoon vanilla extract
- 1/2 teaspoon almond extract (optional)
- 3 tablespoons milk
- Sprinkles or colored sugar (optional)

### Instructions

1.  Preheat oven to **375°F (190°C)**.
2.  Cream together butter and sugar until smooth.
3.  Beat in the egg, vanilla, and almond extract.
4.  Mix dry ingredients separately, then slowly combine with wet
    mixture.
5.  Add milk as needed to soften the dough.
6.  Roll into balls, place on an ungreased cookie sheet.
7.  Flatten slightly and decorate if desired.
8.  Bake **8–10 minutes** or until edges are lightly golden.

## R Code Example: Scaling the Recipe

Here’s a simple R code chunk that scales the ingredient quantities if
you want to make more (or fewer!) cookies.

``` r
# Number of cookies the base recipe makes
base_cookies <- 36

# Desired number of cookies
desired_cookies <- 90

# Scaling factor
scale_factor <- desired_cookies / base_cookies
scale_factor
```

    ## [1] 2.5

``` r
# Ingredient quantities (in cups or units)
ingredients <- data.frame(
  ingredient = c("Flour (cups)", "Sugar (cups)", "Butter (cups)", "Eggs (units)"),
  base_amount = c(2.75, 1.5, 1, 1)
)

# Scaled amounts
ingredients$scaled_amount <- round(ingredients$base_amount * scale_factor, 2)
ingredients
```

<div class="kable-table">

| ingredient    | base_amount | scaled_amount |
|:--------------|------------:|--------------:|
| Flour (cups)  |        2.75 |          6.88 |
| Sugar (cups)  |        1.50 |          3.75 |
| Butter (cups) |        1.00 |          2.50 |
| Eggs (units)  |        1.00 |          2.50 |

</div>

## Output Table

The table above shows how much of each ingredient you’d need to make 60
cookies.

## Final Notes

- This example shows how GitHub can version-control reproducible
  documents.
- You can render this file to HTML, Word, or PDF.

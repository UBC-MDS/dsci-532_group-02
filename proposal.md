Proposal: shades of foundation offered by a variety of beauty brands
around the world
================

# Section 1: Motivation and Purpose

**Our role**: Data scientist consultancy firm

**Target audience**: Global cosmetic marketing and consulting companies

Makeup foundation usually comes in many different shades, contributed by
factors such as hue, saturation, brightness, and lightness levels. Each
beauty brand also has its own distribution of makeup foundation products
that have the different shades to meet customer demands. If we could
understand which beauty brands and their foundation products that meet
the specific shades requirements, it could be helpful for cosmetic
marketing and consulting companies to make informed decisions.

To address this objective, we propose building a data visualization
dashboard that allows our target audience to visually and interactively
explore a dataset of makeup foundation shades by different global beauty
products from different brands. Our dashboard will show the distribution
of foundation products by shades and allow users to explore different
aspects of this data by filtering and re-ordering on different variables
such as brands, hue, and saturation in order to compare factors that
contribute to different foundation shades.

# Section 2: Description of the [data](https://github.com/the-pudding/data/tree/master/makeup-shades)

We will be visualizing a dataset of 625 observations. Each observation
has 8 associated relevant variables that describe a particular
foundation `product` from a particular `brand` with a particular shade
(represented as `hex` which stands for *hexadecimal color code* in the
dataset), which has associated hue `H`, saturation `S`, brightness `V`,
and lightness `L` numerical values, and has associated product `group`
(of 7 categories - *0: Fenty Beauty’s PRO FILT’R Foundation Only*; *1:
Make Up For Ever’s Ultra HD Foundation Only*; *2: US Best Sellers*; *3:
BIPOC-recommended Brands with BIPOC Founders*; *4: BIPOC-recommended
Brands with White Founders*; *5: Nigerian Best Sellers*; *6: Japanese
Best Sellers*; *7: Indian Best Sellers*).
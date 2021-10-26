State Crops
================
Mandy Liesch
10/23/2021

-   [USDA NASS Data](#usda-nass-data)
-   [Major Cash Crops](#major-cash-crops)
    -   [Corn](#corn)
    -   [Soybean](#soybean)
    -   [Cotton](#cotton)
    -   [Rice](#rice)
-   [Wheat](#wheat)
    -   [Winter Wheat](#winter-wheat)
    -   [Spring Wheat](#spring-wheat)
    -   [Durum Wheat](#durum-wheat)
-   [Other Grains](#other-grains)
    -   [Oats](#oats)
    -   [Barley](#barley)
    -   [Flaxseed](#flaxseed)
    -   [Sorghum](#sorghum)
-   [Oil Crops](#oil-crops)
    -   [All Sunflower](#all-sunflower)
    -   [Canola](#canola)
-   [Sugar Crops](#sugar-crops)
    -   [Sugar Beets](#sugar-beets)
    -   [Sugarcane (Harvested Sugar and
        Seed)](#sugarcane-harvested-sugar-and-seed)
-   [Potatoes](#potatoes)
    -   [Potatoes](#potatoes-1)
    -   [Sweet Potatoes (No 2021 Data)](#sweet-potatoes-no-2021-data)
-   [Pulses and Beans](#pulses-and-beans)
    -   [Dry Beans](#dry-beans)
    -   [Dry Peas (And Austrian Peas)](#dry-peas-and-austrian-peas)
    -   [Peanuts](#peanuts)
-   [Tobacco (Harvested Acres ONLY)](#tobacco-harvested-acres-only)

## USDA NASS Data

State Crop Production Data from 1990-2021 in acres. The NASS data for
each crop was downloaded by state, and trimmed into three columns in
Microsoft Excel: Year, State, and Acres. The total land area of each
state is noted in the GIS shapefiles. The square meter values were
turned to acreages using the calculate function in an attribute table,
and then the attribute table was exported to a .csv file for use in
calculating the total crop area

Once the file is read in and transformed, with new percentages
calculated, the data is linked to a second function that transforms the
data into a matrix format for use in the creation of heatmaps and plots.

And this function uses the data matrix from the above functions, and
transfers the matrix dataframe to a graphical heat map based on the crop
selected.

## Major Cash Crops

### Corn

<img src="README_files/figure-gfm/unnamed-chunk-32-1.png" style="display: block; margin: auto;" />

### Soybean

<img src="README_files/figure-gfm/unnamed-chunk-33-1.png" style="display: block; margin: auto;" />

### Cotton

<img src="README_files/figure-gfm/unnamed-chunk-34-1.png" style="display: block; margin: auto;" />

### Rice

<img src="README_files/figure-gfm/unnamed-chunk-35-1.png" style="display: block; margin: auto;" />

## Wheat

### Winter Wheat

<img src="README_files/figure-gfm/unnamed-chunk-36-1.png" style="display: block; margin: auto;" />

### Spring Wheat

<img src="README_files/figure-gfm/unnamed-chunk-37-1.png" style="display: block; margin: auto;" />

### Durum Wheat

<img src="README_files/figure-gfm/unnamed-chunk-38-1.png" style="display: block; margin: auto;" />

## Other Grains

### Oats

<img src="README_files/figure-gfm/unnamed-chunk-39-1.png" style="display: block; margin: auto;" />

### Barley

<img src="README_files/figure-gfm/unnamed-chunk-40-1.png" style="display: block; margin: auto;" />

### Flaxseed

<img src="README_files/figure-gfm/unnamed-chunk-41-1.png" style="display: block; margin: auto;" />

### Sorghum

<img src="README_files/figure-gfm/unnamed-chunk-42-1.png" style="display: block; margin: auto;" />

## Oil Crops

### All Sunflower

<img src="README_files/figure-gfm/unnamed-chunk-43-1.png" style="display: block; margin: auto;" />

### Canola

<img src="README_files/figure-gfm/unnamed-chunk-44-1.png" style="display: block; margin: auto;" />

## Sugar Crops

### Sugar Beets

<img src="README_files/figure-gfm/unnamed-chunk-45-1.png" style="display: block; margin: auto;" />

### Sugarcane (Harvested Sugar and Seed)

<img src="README_files/figure-gfm/unnamed-chunk-46-1.png" style="display: block; margin: auto;" />

## Potatoes

### Potatoes

<img src="README_files/figure-gfm/unnamed-chunk-47-1.png" style="display: block; margin: auto;" />

### Sweet Potatoes (No 2021 Data)

<img src="README_files/figure-gfm/unnamed-chunk-48-1.png" style="display: block; margin: auto;" />

## Pulses and Beans

### Dry Beans

<img src="README_files/figure-gfm/unnamed-chunk-49-1.png" style="display: block; margin: auto;" />

### Dry Peas (And Austrian Peas)

### Peanuts

<img src="README_files/figure-gfm/unnamed-chunk-51-1.png" style="display: block; margin: auto;" />

## Tobacco (Harvested Acres ONLY)

<img src="README_files/figure-gfm/unnamed-chunk-52-1.png" style="display: block; margin: auto;" />

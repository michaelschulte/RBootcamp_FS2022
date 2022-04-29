# Recaps

# Session 1 Intro + Data

- vector with numbers and assignment
- calculate mean, sd, sum
- add NA
- calc mean - na.rm()
- character vector
- class()
- load tidyverse 

- generate vector c()
- generate data.frame with tibble()

- show mpg
- extract cyl
- add 10 to cyl

- load dataset Europa.csv

# Session 2 Wrangling 1+2

- load tidyverse
- mpg dataset

- rename displ in Hubraum
- show number of cyl in the mpg dataset
- recode drv into new variable 
- filter all 4-wheel drive
- new dataset only 4-wheel and manufacturer and drive
- get distribution of manufacturers 

- new tibble with 
cyl = 4 5 6 8 
co2 = 2.3 2.8 3 4.5 g/liter

- left_join
- remove one item in co2
- left_join
- right_join / anti_join

- median verbrauch pro manufacturer
- pull()

# Session 3 Plotting

data()
simple geom_bar() with 

star %>% ggplot(aes(x = species)) + 
geom_bar() +

  theme(axis.text.x = element_text(angle = -90, vjust = 0.5, hjust=1))


geom_point(mass / height)
geom_smooth(method = 'lm')
which.max()

library(ggthemes)
 theme_fivethirtyeight()

facet_grid(gender ~ .)
patchwork
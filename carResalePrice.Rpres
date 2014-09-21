Resale Price of Cars
========================================================
author: Daniel Emaasit
date: September 21, 2014


Introduction
========================================================

- Data collected from **Kelly Blue Book** for several hundred 2005 used **General Motors (GM)** cars allows the development a multivariate regression model to determine car values based on a variety of characteristics such as:   
    + mileage, 
    + make, 
    + model, 
    + engine size, 
    + interior style, and 
    + cruise control.  

Objective
========================================================

- To developed a shiny app that creates a multivariate linear regression model using the caret's cars data set.   
- This model can be used predict the resale price of a car based on a variety of characteristics.   
- The shiny app can be accessed using the link below.  
    + <http://emaasit.shinyapps.io/carResalePrice>

Code
========================================================

- The following R expression was evaluated and displayed the predicted value.

```
library(caret)
data(cars)
                
fit <- lm(Price ~ Mileage+Cylinder+Doors+Leather+Buick+Cadillac+
Pontiac+Saab+convertible+hatchback+sedan, data=cars)

summary(fit)
```

Pitch and Conclusion
========================================================

- By using this shiny app, users are able to quickly determine the resale price of their cars
without the hustle of developing a prediction algorithm.  

- Users can simply select the explanatory variables and click the predict button to display
the predicted resale value.  


This repository explores the "Abalone" dataset 

# Key Questions 🤔

### 1. How does age relate to the amount of meat present in an abalone? Does the rate of growth slow after a certain point?  
![growth](/Images/growth_rate.png)

✨ The older the abalones, the more meat they tend to have. However, the rate of growth seems to slow down, especially around its "teen years".  
  
  
### 2. Do the shell and meat grow at different rates?  
![difference](https://user-images.githubusercontent.com/70524391/206378426-55923e08-13e6-44fe-95b1-e59733e843ed.png)

✨ Yes, the shell and meat grow at different rates. The meat grows faster than the shell. There is a huge difference in growth around the teen years of the abalone.

### 3. Which variables have the most impact on the amount of meat present in an abalone?
![features](https://user-images.githubusercontent.com/70524391/206378524-5de9c669-f924-4046-96ae-74120e0f9081.png)


✨ Answer:
1. __Whole weight__ was the most important variable in determining the amount of meat present in an abalone.
2. The second most important variable was the __weight of the shell__  of the abalone.
3. This is followed by:
    - Rings
    - Age
    - Viscera weight
    - Length
    - Diameter
    - Height
    - Female
    - Male
    - Infant  
_Note: Feature importances were derived from a Random Forest Regressor_  
  
Interestingly, even though viscera weight was the 2nd most highly correlated data with meat weight, it was not the 2nd most important variable in determining the amount of meat present in an abalone.

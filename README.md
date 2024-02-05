# Mobile Price Prediction Project

## Overview:

This project focuses on predicting the price range of mobile phones based on various specifications such as battery power, 3G availability, WiFi, Bluetooth, RAM, and more. The goal is to assist companies in estimating mobile prices for competitive positioning in the market and to empower consumers to make informed purchasing decisions.

## Data:

### Columns:

- **id:** ID of the mobile
- **battery_power:** Total energy a battery can store in one time (mAh)
- **blue:** Bluetooth availability (1 if present, 0 if not)
- **clock_speed:** Speed at which the microprocessor executes instructions
- **dual_sim:** Dual SIM support (1 if supported, 0 if not)
- **fc:** Front Camera mega pixels
- **four_g:** 4G availability (1 if present, 0 if not)
- **int_memory:** Internal Memory in Gigabytes
- **m_dep:** Mobile Depth in cm
- **mobile_wt:** Weight of the mobile phone
- **n_cores:** Number of processor cores
- **pc:** Primary Camera mega pixels
- **px_height:** Pixel Resolution Height
- **px_width:** Pixel Resolution Width
- **ram:** Random Access Memory in Megabytes
- **sc_h:** Screen Height of mobile in cm
- **sc_w:** Screen Width of mobile in cm
- **talk_time:** Longest time a single battery charge will last
- **three_g:** 3G availability (1 if present, 0 if not)
- **touch_screen:** Touch screen availability (1 if present, 0 if not)
- **wifi:** WiFi availability (1 if present, 0 if not)

## Use:

Predicting mobile prices based on these specifications provides benefits to both manufacturers and consumers:

- **Manufacturers:** Estimate prices to remain competitive in the market.
- **Consumers:** Verify they are paying the best price for a mobile.

## Applied Models:

The following machine learning models were employed for predicting mobile prices:

1. **Linear Regression:**
   - Utilized for establishing a linear relationship between features and the price range.

2. **K-Nearest Neighbors (KNN):**
   - Employed for predicting prices based on the similarity of mobile specifications.

## Conclusion:

This project offers a practical solution for estimating mobile prices, aiding companies in strategic pricing decisions and empowering consumers to make informed choices. The implemented models provide a reliable foundation for predicting mobile prices based on diverse specifications.

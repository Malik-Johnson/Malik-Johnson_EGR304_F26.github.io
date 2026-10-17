---
title: Component Selection 
---


**Temperature Display**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://github.com/Malik-Johnson/Malik-Johnson_EGR304_F26.github.io/blob/4f361ddb375bfe533aa342fa749cd71daeca9f48/docs/02-Component-Selection/Screenshot%202026-10-16%20201300.png)<br>\* Option 1. <br>\* MDOB064048AV-WI Midas OLED Screen <br>$8.08/each<br>[link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-C160100DIZ-FSW-FBW/1885694)                 | \* Inexpensive[^1]<br>\* Uses a simple 2-Pin I2C Interface <br>\* High Contrast                                               | \* Low Resolution Screen<br>\* Undersized. |
| ![](https://github.com/Malik-Johnson/Malik-Johnson_EGR304_F26.github.io/blob/4f361ddb375bfe533aa342fa749cd71daeca9f48/docs/02-Component-Selection/Screenshot%202026-10-16%20201219.png)<br>\* Option 2. <br>\* NHD-C160100DIZ-FSW-FBW Newhaven LCD Screen <br>\* $23.53/each <br>\* [link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-C160100DIZ-FSW-FBW/1885694) | \* Color Display <br>  | * More expensive <br>\* Complex Interface <br>  \* Low Contrast <br>                                                       |
| ![](https://github.com/Malik-Johnson/Malik-Johnson_EGR304_F26.github.io/blob/9669d95a7cbe4a25266fef32f7eef1af62ab8985/docs/02-Component-Selection/Screenshot%202026-10-16%20201146.png)<br>\* Option 3. <br>\* AES152296A00-2.66ENRS Orient E-Paper Screen <br>\* $10.22/each <br>\* [link to product](https://www.digikey.com/en/products/detail/orient-display/AES152296A00-2-66ENRS/15198689) | \* Low Power <br> \* Perfect Size <br>  | * Complex Interface <br>                                                       |

**Choice:** Option 1: MDOB064048AV-WI Midas OLED Screen

**Rationale:** The choice is really between the first and last options; the LCD screen is simply overkill for the project's needs. And between those two options, while the E-paper display has its appeal especially with its on-component ram, perfect size for the envisioned project, and low power consumption, the OLED screen's simpler control setup and high-contrast screen make for a better tradeoff, especially as its max power draw is lower than the E-paper's (though the E-paper's power draw is intermittent, hence the lower overall consumption). 

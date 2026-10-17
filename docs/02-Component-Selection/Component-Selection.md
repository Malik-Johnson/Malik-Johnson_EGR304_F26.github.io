---
title: Component Selection Example
---

## Examples

### Style 1

> This is the example found in the assignment, uses more html

*Table 1: Example component selection*

**External Clock Module**

| **Solution**                                                                                                                                                                                      | **Pros**                                                                                                                                    | **Cons**                                                                                            |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------- |
| ![](https://github.com/Malik-Johnson/Malik-Johnson_EGR304_F26.github.io/blob/4f361ddb375bfe533aa342fa749cd71daeca9f48/docs/02-Component-Selection/Screenshot%202026-10-16%20201300.png)<br>\* Option 1. <br>\* MDOB064048AV-WI Midas OLED Screen <br>$8.08/each<br>[link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-C160100DIZ-FSW-FBW/1885694)                 | \* Inexpensive[^1]<br>\* Uses a simple 2-Pin I2C Interface <br>\* High Contrast                                               | \* Low Resolution Screen<br>\* Undersized. |
| ![](https://github.com/Malik-Johnson/Malik-Johnson_EGR304_F26.github.io/blob/4f361ddb375bfe533aa342fa749cd71daeca9f48/docs/02-Component-Selection/Screenshot%202026-10-16%20201219.png)<br>\* Option 2. <br>\* NHD-C160100DIZ-FSW-FBW Newhaven LCD Screen <br>\* $23.53/each <br>\* [link to product](https://www.digikey.com/en/products/detail/newhaven-display-intl/NHD-C160100DIZ-FSW-FBW/1885694) | \* Color Display <br>  | * More expensive <br>\* Complex Interface  \* Low Contrast <br>                                                       |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

### Style 2

> Also acceptable, more markdown friendly

**External Clock Module**

1. XC1259TR-ND surface mount crystal

    ![](image1.png)

    * $1/each
    * [link to product](http://www.digikey.com/product-detail/en/ECS-40.3-S-5PX-TR/XC1259TR-ND/827366)

    | Pros                                      | Cons                                                             |
    | ----------------------------------------- | ---------------------------------------------------------------- |
    | Inexpensive                               | Requires external components and support circuitry for interface |
    | Compatible with PSoC                      | Needs special PCB layout.                                        |
    | Meets surface mount constraint of project |

1. CTX936TR-ND surface mount oscillator

    ![](image3.png)

    * $1/each
    * [Link to product](http://www.digikey.com/product-detail/en/636L3I001M84320/CTX936TR-ND/2292940)

    | Pros                                                              | Cons                |
    | ----------------------------------------------------------------- | ------------------- |
    | Outputs a square wave                                             | More expensive      |
    | Stable over operating temperature                                 | Slow shipping speed |
    | Direct interface with PSoC (no external circuitry required) range |

**Choice:** Option 2: CTX936TR-ND surface mount oscillator

**Rationale:** A clock oscillator is easier to work with because it requires no external circuitry in order to interface with the PSoC. This is particularly important because we are not sure of the electrical characteristics of the PCB, which could affect the oscillation of a crystal. While the shipping speed is slow, according to the website if we order this week it will arrive within 3 weeks.

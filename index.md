---
title       : Rent or Buy?
subtitle    : Shiny App for First Time Homebuyers
author      : Michael Seelaus
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Intro & App Description

Thank you for considering the Buy or Rent? App for your first time homebuying needs!  Buying a home 
for the first time can be a very overwelming experience and you've taken a great first step in seeking 
additional guidance.  
  
Armed with some basic information about your local housing market and personal financial preferences, 
this app will help provide you with some basic guidance on renting versus buying.  While the number 
of inputs may seem intimidating to first time buyers, rest assured that you will have everything 
up and running in no time.  
  
The app will take characteristics or your planned home purchase, incorporate information based on your 
local tax situations, and return a recommendation that considers both cash payment and total value 
perspectives.

--- .class #id 

## App Advantages

A quick online search for mortgage calculators will bring up an unending flood of responses.  While there 
are many similar offerings in this space, they rarely offer more than a simple calculation of your monthly 
mortgage payment based soley on the loan amount, loan type, and interest rate.  This is certainly a useful 
piece of information, but it also critically fails to deliver on a variety of other relevant factors.  
  
#### These include:  
1. Property Taxes
2. Mortgage Interest Tax Deduction
3. Private Mortgage Insurance
  
    #### And perhaps most critically...
4. The total value to the buyer (That's You!) of all factors, not just the monthly cash outflow.

---

## Quick Example

To illustrate the added value of this App, let's review a simple example.  
  
<img src="assets/fig/unnamed-chunk-1-1.png" title="plot of chunk unnamed-chunk-1" alt="plot of chunk unnamed-chunk-1" style="display: block; margin: auto;" />

---

## Explanation
So what is causing the determination that total value is lower than cash payment?  There are two reasons 
for this.  
* First, a portion of the monthly mortgage payment goes towards paying down the principal of the loan.  In 
essence, the buyer is purchasing an additional percentage of the home with this money.  You pay cash, but are 
getting an asset in return (an additional percentage of outright ownership in the home).  
* Second, homeowners in the United States can deduct the amount paid as interest on their loans from their 
federal income tax.  
  
So while it is important to know and understand your cash requirements when purchasing a home, don't forget 
to evaluate the total financial picture as well.  
  
[Now get out there and give it a try!](http://michaelseelaus.shinyapps.io/DataProducts_Coursera)

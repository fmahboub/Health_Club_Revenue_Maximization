# Health Club Revenue Maximization
Based on the case "Personel Training at the New York Health Club" by Costis Maglaras

Ney York Health Club (NYHC) has 10,000 clients and 1000 responded to a survey where they specified how much they are willing to pay for various time slots of personel training sessions. The survey data can be found in excel format in this repository. 

The code takes the survey data and calculates the demand for the 5-9pm (D59) time slot (prime time) and the demand for not 5-9pm time slots (D0). It does this for every combination of price for 5-9pm (p59) and price of not 5-9pm (p0). Once the demands for all combinations (prices ranging from 0-$150 for p0 and p59) are calculated, the notebook regresses D0 on p0 and p59 and regresses D59 on p0 and p59. Once the demands functions are produced, we optimize the prices to maximize revenue. 

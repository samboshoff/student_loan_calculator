# student_loan_calculator

Rough and ready calculator used to work out if its better to pay off a lump sum towards your student loan or to invest that instead. 

I verified it using https://www.yourstudentloancalculator.co.uk/ but it's still just a tool to illustrate the benefits of paying the loan off early. 

The first cell has the variables in you can adjust for your scenario.
I've tried to parameterise as much as possible but there is some hardcoded logic in there that I assumed wouldn't change.
  - the repayment threshold (£27000). I think you only repay 9% of salary over this amount. Not 100% sure just worked it out from my payslips.
  - return rate in the loan_payment_calculator. set this at 8% but you can go in and tweak it if you like.

Assumptions: 
 - Repayment Plan 2

Considerations & improvements: 
 - when you use it, the total gain might decrease as you pay it off quicker. Keep in mind that this is because you've had less time investing. You're actually probably better off as you'll have extra years to invest but the outputs don't consider that. 
 - not guaranteed a 8% return each year, not sure how to model if one year is 0% and the next is 16% for example
 - not considered modelling voluntarily increasing the monthly repayment amount (might be useful if you have a high income but not a large amount of savings)

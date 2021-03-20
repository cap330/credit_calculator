# credit_calculator
credit calculator python program from jet brains

# Stage 4/4: Differentiate payment

Description

Finally, let's add to our calculator the capacity to compute differentiated payments. 
We’ll do this for the type of repayment where the loan principal is reduced by a constant amount each month. 
The rest of the monthly payment goes toward interest repayment and it is gradually reduced over the term of the loan. 
This means that the payment is different each month. Let’s look at the formula:


python creditcalc.py --type=diff --principal=1000000 --periods=10 --interest=10

python creditcalc.py --type=annuity --principal=1000000 --periods=60 --interest=10

python creditcalc.py --type=diff --principal=500000 --periods=8 --interest=7.8

python creditcalc.py --type=annuity --payment=8722 --periods=120 --interest=5.6

python creditcalc.py --type=annuity --principal=500000 --payment=23000 --interest=7.8

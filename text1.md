#pip install forex-python

from forex_python.converter import CurrencyRates

c= CurrencyRates() #creating instance

r = c.convert("USD", "INR", 1)

print (r)

#output 72.50
       

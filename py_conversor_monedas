from forex_python.converter import CurrencyRates

c = CurrencyRates()

print("Monedas disponibles: ")
print("EUR, USD, JPY, BGN, CZK, DKK, GBP, HUF, PLN, RON, SEK, CHF, ISK, NOK, "
      "HRJ, TRY, AUD, BRK, CAD, CNY, HKD, IDR, INR, KRW, MXN, MYR, NZD, "
      "PHP, SGD, THB, ZAR")

amount = int(input("Cantidad: "))
from_currency = input("De: ").upper()
to_currency = input("A: ").upper()

print(from_currency, " TO ", to_currency, amount)
result = c.convert(from_currency, to_currency, amount)

print(result, to_currency)

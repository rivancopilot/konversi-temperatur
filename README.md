# konversi-temperatur
def celcius_to_fahrenheit(celcius):
    fahrenheit = (celcius * 9/5) +32
    return fahrenheit

celcius = int(input(("masukkan suhu dalam celcius : ")))
print("suhu dalam Celcius adalah", celcius)
print ("suhu dalam fahrenheit adalah" , celcius_to_fahrenheit(celcius))

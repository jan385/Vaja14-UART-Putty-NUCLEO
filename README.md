# Vaja14-UART-Putty-NUCLEO
2.)

c) katere dva mostička bi morali odspajkati in kateri dve povezavi pospajkati, da bi lahko uporabili pina Tx/D1 in Rx/D0? ____ in ____.

    SB13 in SB14, SB62 in SB63

e) Katera dva pina sta se pobarvala zeleno oz. se aktivirala? ________ in _________.
     
    PA2 in PA3

f) V polju Configuration izbranega serijskega vmesnika pustimo privzeto hitrost, ki znaša ________Bit/s.

115200 Bit/s

3.)

e) Za to funkcijo zapišite ukaz za vklop/izklop zelene LED.

     HAL_GPIO_TogglePin(GPIOA, GPIO_PIN_5);

f) Dodajte še ukaz za zakasnitev s funkcijo Delay iz knjižnice HAL, in sicer 2 sekunde .

     HAL_Delay(1000);

komentar: sprogramirala sma ARM mikroprocesor tako, da bo  preko serijskega vmesnika UART pošiljal podatke (preko USB) računalniku na odjemalec Putty.

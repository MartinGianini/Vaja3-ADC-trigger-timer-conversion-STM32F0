2.)

b)
PC0

e)
GPIO_Analog_ADC_IN10

i)
Timer clocks se ob prvem poizkusu nastavi na 96MHz,
kar je treba še enkrat nastaviti na 16MHz,
perhiperal clocks se pomanjša na 8MHz.

l)
16000


3.)

f)
HAL_GPIO_TogglePin(GPIOC, GPIO_PIN_9);


Delovanje:
Z upravljanjem potenciometra se adcVal spreminja med 0 in 255.

//Manjše težave pri zagonu STMStudija, bilo je treba zagnati java executable, saj bližnjici nista delali.

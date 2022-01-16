# Vaja1-ADC -enojna -pretvorba-STM32F0

b)  Zelena LED je priključena na PA5 pin. Kaj je pa priključeno na pin PA0?    Potenciometer.
d) V Analog razdelku levo od sheme mikroprocesorja ugotovite, koliko ADC pretvornikov ima vaša razvojna ploščica? Razvojna ploščica ima 3 pretvornike. 
e) Izbrani ADC pretvornik(i) ima(jo) oznako s trikotnikom. Kaj to pomeni? To pomeni, da je konflikt z pini-so že zasedeni. Kaj morate storiti, da razrešite to omejitev? Vse zasedene pine moramo postaviti v stanje RESET, zato da ni nobenega konflikta. 
f) Koliko je vseh vhodnih kanalov (seštejte oznake INxx). Skupno je 15 vhodnih kanalov. 
g) Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ADC1_IN3 
i) Preglejte, kakšne so še ostale možne ločljivosti pretvorbe in območja vrednosti? 10bit, od 0 do 1023, 12bit, od 0 do 4095, 14bit, od 0 do 16383.

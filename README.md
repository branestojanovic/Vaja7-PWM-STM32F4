# Vaja7-PWM-STM32F4

Vprašanja in odgovori:

b) Kateri pin ste omogočili? PE9. Kaj se izpiše poleg pina? TIM_CH1.

d) Koliko je vrednost Perscaler (namig; delitelj)? 16.

e) Parameter Counter Period nastavimo na 100 in s tem še dodatno znižamo takt časovnika. Koliko znaša sedaj? 10kHz.

f) V PWM Generation Channel nastavite Pulse (16 bits value) na 50. Kaj pomeni ta parameter? Širina signala (duty cycle).

Poiščite prenastavljeni parameter Pulse (ki je 50) v vaši kodi in prepišite ukaz, ki ga je generiral CubeMX: sConfigOC.Pulse = 50;.

V kodi spremenite vrednost širine pulza na 25 %. Zapišite popravljeni ukaz v kodi: sConfigOC.Pulse = 25;. 

Zapišite kaj počnejo ukazi v  1. 2. in 3. vrstici (v user code begin 3):
1. Nastavi spremenljivko duty cycle.
2. Spremeljivki prišteje 10.
3. Če ima spremenljivka duty cycle vrednost ki je večja od 90, nastavi spremenljivko na 10.

Komentar: Sprva so bile težave z nastavljanjem osiloskopa, ker nam ni zaznal signala. Ko sva priključke zvezala na drugo stran mikrokontrollerja nam je pa delovalo. Na sliki je črta ravna predvsem zaradi tega.

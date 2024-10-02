# Misc Calculations

Gear 1: 12 teeth
Gear 2: 24 teeth

Gear ratio = 24/12 = 2
Force of load: 0.03kg * 9.8 = 0.294 N
Input force needed (min): 0.294/2 = 0.147N
Converting input force to engergy: 0.147*0.15 = 0.02205J

Gear Maximum Load:

Required load = 0.294N
Filament tensile strength = 37000000Pa

Lewis form factor of gear 1 = 0.245
Lewis form factor of gear 2 = 0.337

Face width (both gears) = 8mm

Module (both gears) = 2.5
Module (Meters) = (30/1000) / 12 = 0.025

Max transmitted load = ((1/3 of tensile strength) * Face width * Lewis form factor) / (1 / Module)

Max transmitted load (Gear 1) = ((37000000 / 3) * (8 / 1000) * 0.245) / (1 / ((30/1000) / 12)) = 60.43N

Max transmitted load (Gear 2) = ((37000000 / 3) * (8 / 1000) * 0.337) / (1 / ((30/1000) / 12)) = 41.56N

Written by Thea

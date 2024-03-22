# Description

Voltage Controlled Ring Oscillator

## Schematic

![image](https://github.com/huydo272/PLL_PBKIC/assets/146626889/a2e0c277-ff99-4e6d-864c-fb54abcce965)

## Sizing

|Block|MOS|Size W:L|
|--|--|--|
|Ring Oscillator|PMOS: M2, M3, M5, M7, M9|0.5x3.43|
||NMOS: M1, M4, M6, M8, M10|0.5x1|
|Bias Stage|PMOS: M27|0.5x2.2|
||NMOS: M28|0.75x90​|
||PMOS: M26​|0.5x9​|
||NMOS: M25​|0.5x1.8​|
||Resistor: R2​|90x0.1 (4.338e+04 Ω)|
|Current Source​|PMOS: M16 to M20​|0.5x9​|
||NMOS: M11 to M15​|0.5x1.8​|
|Buffer Inverter​|PMOS: M23, 24​|0.5x15​|
||NMOS: M 21, 22​|0.5x4​|

## Simulation

- DC Sim:

![image](https://github.com/huydo272/PLL_PBKIC/assets/146626889/c4c1f4e5-a0c0-49f3-9c9f-f641aa62f112)


- AC Sim:

![image](https://github.com/huydo272/PLL_PBKIC/assets/146626889/ecdf9ab5-b443-47ee-9544-8de0c72bf973)


- End result

![image](https://github.com/huydo272/PLL_PBKIC/assets/146626889/bdd8194d-2318-4645-89e1-c16553c4b49f)

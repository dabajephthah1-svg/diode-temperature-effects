# diode-temperature-effects
# Effect of Temperature on Diode Behavior

This simulation investigates the behavior of a 1N4148 diode at two temperatures: 25 °C and 75 °C using LTspice.

## Observations

As temperature increases, the forward voltage of the diode decreases. At 25 °C, the diode begins conducting at approximately 0.65–0.7 V, while at 75 °C the turn-on voltage drops to around 0.55–0.6 V. This occurs because higher temperature increases carrier energy, reducing the PN-junction barrier.

Reverse current also increases noticeably at higher temperature. At 75 °C, thermal generation of charge carriers causes significantly higher leakage current compared to 25 °C.

## Why Temperature Affects Diode Behavior

Temperature affects semiconductor materials by increasing carrier concentration and mobility. This reduces the forward voltage required for conduction and increases reverse leakage current due to thermally generated carriers.

## Why This Matters in Real Systems

In real electronic systems, temperature variations can lead to voltage drift, increased power dissipation, and potential thermal runaway. Circuits such as rectifiers, voltage regulators, and protection diodes must account for temperature effects to ensure reliability and safe operation.

This demonstrates why temperature-aware design is essential in practical electronics.

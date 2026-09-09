# EEZ BB3+ STM32H7 CM5 module — EMC Pre-Certification Testing (Summary)

## What we tested

The EEZ test mainboard with installed [EEZ BB3+ STM32H7 CM5 module](https://github.com/eez-open/eez-bb3plus-cm5-mcu) was put through an in-house EMC pre-certification check for **radiated emissions**, covering **30 MHz – 1 GHz** against the **EN 55032 / CISPR 32 Class B** limit (the standard used for multimedia/IT equipment). 
Conducted emissions, wireless-module (RED) compliance, and immunity testing were not part of this round — this was a radiated-emissions check only.

## How we tested it

We don't have access to an accredited far-field chamber, so we used a **substitution (comparison) method** instead of trying to measure absolute levels ourselves:

1. Start from a **known-good reference board** (ULX4M-LS), which already has a real accredited lab report (SiQ Ljubljana, T251-0973/25) with known absolute emission levels.
2. Scan that same reference board in our own DIY shielded chamber (TinySA Ultra spectrum analyzer + custom PCB antenna + LNA), which gives us a "translation factor" between our chamber and the accredited lab.
3. Scaning an empty chamber to know our own background noise floor.
4. Scan the actual device (EEZ BB3+ STM32H7 CM5 module) in the exact same setup.
5. Then we apply the translation factor from step 2 to the CM5H7 scan, giving us an estimated real-world emission curve, which we compare against the Class B limit line.

In short: if the EEZ BB3+ STM32H7 CM5 module stays at or below the reference board's curve, it should behave the same way the reference board did in its accredited test — i.e. pass.

## Result

Based on this measurement campaign, **the EEZ BB3+ STM32H7 CM5 module looks ready to go to formal certification** — no radiated-emission exceedance stood out against the Class B limit in the scanned band. As always with in-house pre-cert work, this is an engineering estimate meant to catch problems *before* paying for an accredited lab, not a substitute for one — but it gives us good confidence going in.

## Full report

Full methodology, equipment list, chamber construction details, calibration data and the measurement charts are in the pre-certification report ([precert_Envox_CM5H7_20260908-181118.pdf](precert_Envox_CM5H7_20260908-181118.pdf))

---
*Intergalaktik d.o.o. — in-house EMC pre-cert workflow, September 2026.*

---
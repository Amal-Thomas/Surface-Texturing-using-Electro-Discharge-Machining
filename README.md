# Surface Texturing Using Electro Discharge Machining (EDM)

## Overview

This project investigates how EDM process parameters — specifically **peak current** and **pulse time** — affect surface texture and material removal rate (MRR) on an aluminium workpiece. A Die-Sinking EDM machine was used to create textured surfaces across 9 experimental configurations, which were then analyzed using a surface profilometer.

## Background

Electro Discharge Machining (EDM) is a non-traditional, thermoelectric manufacturing process that removes material through cycled electrical discharge sparks — no mechanical force is applied. It is well-suited for hard or difficult-to-machine materials and can produce complex geometries. However, the EDM process inherently creates discharge craters, micro-cracks, and pores on the machined surface, making surface roughness characterization an important area of study.

## Objectives

- Study the surface texture produced by Die-Sinking EDM on aluminium
- Measure how Ra (line roughness) and Sa (surface roughness) vary with current and pulse time
- Compare experimental MRR and Ra values against theoretical predictions

## Apparatus

| Item | Details |
|---|---|
| Workpiece | Aluminium (100 × 63 × 10 mm) |
| Electrode (Tool) | Copper, 10 mm diameter |
| EDM Machine | ONA NX3F Die-Sinking EDM |
| Profilometer | Alicona (10 nm resolution) |
| Dielectric Fluid | Light oil |

## Experimental Parameters

**Variable Parameters:**
- Current: 24 A, 48 A, 64 A
- Pulse Period (T = 2·Ton = 2·Toff): 20 µs, 100 µs, 200 µs

**Constant Parameters:**
- Gap Voltage: 120 V
- Duty Cycle: 50%

9 total experiments were run (3 current levels × 3 pulse time levels).

## Key Results

- **Surface roughness (Ra, Sa) increases with pulse time** for a given peak current.
- **The effect of current on roughness is not straightforward** — it depends on the pulse time setting.
- **MRR increases with both higher current and longer pulse time**, consistent with theoretical models.
- Experimental trends for both MRR and Ra agreed qualitatively with theoretical predictions, though absolute values showed significant deviation.

## Theoretical Models Used

$$MRR = (4 \times 10^4) \cdot i \cdot T_W^{-1.23}$$

$$Ra = 0.0225 \cdot i_p^{0.29} \cdot t_p^{0.38}$$

## Applications of EDM Surface Texturing

- Orthopedic implants (reducing bearing surface wear)
- Mill roll texturing (modifying metal microstructure)
- Solar cell texturing (improving light trapping)
- Self-cleaning and anti-fouling surfaces in heat transfer applications

## Acknowledgements

- Prof. Pradeep Dixit
- Prof. Ramesh Singh
- Ratan Ahuja (TA)
- Shashank Shukla (TA)

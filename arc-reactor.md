# ARC REACTOR — MARK III
**Classification:** STARK INDUSTRIES / RESTRICTED
**Document ID:** SI-AR-0003
**Last Modified:** 14 MAY 2011
**Author:** A. E. Stark
**Review Status:** APPROVED — DO NOT DISTRIBUTE

---

## 1. OVERVIEW

The Mark III Arc Reactor is a miniaturised self-sustaining power core
designed for chest-mounted deployment. It replaces the Mark II palladium
core, which suffered from progressive blood toxicity in the operator.

The Mark III uses a synthesised element (designation withheld — see
Appendix C, restricted) which produces no measurable toxic byproduct
under continuous operation.

---

## 2. CORE SPECIFICATIONS

| Parameter | Mark II | Mark III |
|---|---|---|
| Core material | Palladium | New element (classified) |
| Sustained output | 2.1 GJ/s | 3.0 GJ/s |
| Peak burst output | 3.4 GJ/s | 8.7 GJ/s |
| Diameter | 7.2 in | 6.0 in |
| Mass | 1.9 kg | 1.2 kg |
| Operating temperature | 340 K | 291 K |
| Toxicity to operator | SEVERE | NONE DETECTED |
| Continuous runtime | 11 days | Indefinite |

---

## 3. POWER DISTRIBUTION

Output is split across four rails. Priority is enforced in hardware —
life support cannot be starved by combat systems under any condition.

```
RAIL 0  [PRIORITY: ABSOLUTE]   Life support / shrapnel containment
RAIL 1  [PRIORITY: HIGH]       Flight stabilisation
RAIL 2  [PRIORITY: MEDIUM]     Repulsor array
RAIL 3  [PRIORITY: LOW]        Sensors, comms, HUD
```

**Failure behaviour:** on core instability the reactor sheds RAIL 3
first, then RAIL 2, then RAIL 1. RAIL 0 is never shed. If RAIL 0 cannot
be sustained, the core initiates controlled shutdown rather than
brownout.

---

## 4. IGNITION SEQUENCE

Ignition must be performed in this order. Deviation causes a hard fault
and requires a full cold-start cycle.

1. Verify containment ring seated — torque 4.2 Nm, all six bolts
2. Charge primary capacitor bank to 94% minimum
3. Confirm coolant loop pressure between 2.1 and 2.4 bar
4. Engage magnetic confinement field
5. Inject core material
6. Release capacitor bank into confinement field
7. Confirm self-sustaining reaction within 400 ms
8. Disengage external charging line

> **WARNING:** Do not perform step 6 before step 4 has confirmed a stable
> field. Field collapse during injection has produced total assembly loss
> in three of three bench tests.

---

## 5. KNOWN ISSUES

| ID | Severity | Description | Status |
|---|---|---|---|
| AR-114 | HIGH | Harmonic vibration at 4.1 kHz under sustained peak load | OPEN |
| AR-118 | MEDIUM | Coolant loop seal degrades after ~900 hours | OPEN |
| AR-121 | LOW | HUD reports output 0.3% high at low temperature | WONTFIX |
| AR-095 | CRITICAL | Palladium toxicity (Mark II only) | RESOLVED — Mark III |

---

## 6. MAINTENANCE SCHEDULE

- **Every 100 hours** — visual inspection of containment ring
- **Every 500 hours** — coolant loop pressure test
- **Every 900 hours** — mandatory seal replacement (see AR-118)
- **Annually** — full core removal and bench diagnostic

---

## 7. NOTE FROM STARK

> "The Mark II kept me alive and was slowly killing me at the same time.
> That is not engineering. That is a compromise wearing a lab coat.
>
> The Mark III is proof that Stark Industries can build a better future
> instead of selling a more expensive present.
>
> Whoever reads this after me — do not go backwards. Ever."

---

## 8. RECOVERY DATA

```
=================================================
  S.H.I.E.L.D. RECOVERY PROTOCOL
  ARTIFACT RECONSTRUCTION — SOUL STONE

  FRAGMENT 1 OF 3

  CODE: SACRIFICE

  Two more fragments remain in this workshop.
  Assemble all three in order 1 - 2 - 3.
=================================================
```

---
*END OF DOCUMENT — SI-AR-0003*

# CassandraFinger: Parametric Mechanical Prosthetic Finger (V5)

## Overview
This repository contains a **fully parametric model** for an articulating mechanical prosthetic finger, designed entirely in **FreeCAD**. 

Optimized for high durability and daily field use, this project improves upon classic open-source structures (like "Nick's Fingers" or the "K-Nek"). It features **significantly reinforced mechanical hinge points**, streamlined cable channels, and a design optimized to reduce printing failures. 

The latest file is **`CassandraFingerV5.FCStd`**. Some chamfers might break during resizing.  

## Key Features
* **Fully Parametric:** Built using FreeCAD spreadsheets. You can dynamically scale the model constraints to fit custom hand and residual digit measurements.
* **Beefed-Up Hinges:** Interlocking joint columns and pinning tracks are heavily thickened to absorb mechanical stress and prevent shearing.
* **Optimized Printability:** Print layout vectors are optimized to require minimal, clean support structures, ensuring smooth internal channels.

## Required Hardware & Assembly
To assemble the articulating digit, you will need the following standard hardware components:
* **Joint Pins:** Stainless steel pins or rods (cut to size matching your scaled hinge bore diameter) for maximum corrosion resistance and structural shear strength.
* **Tension Lines:** Low-friction tension cables routed through the primary internal channels to pull the finger closed.
* **Return Mechanism:** Heavy-duty elastic cord routed through the secondary channel to act as a spring return, automatically snapping the finger back into an open posture when tension is released.

## Strict Material & Safety Requirements
Because this device is intended for direct, long-term contact with human skin, **standard, brittle modeling resins must never be used.**

* **Material:** Must be printed using a **certified biocompatible engineering resin** capable of handling mechanical stress (such as *Siraya Tech Blu Biocompatible*, *Formlabs BioMed*, or *Loctite 3D Medical* grade polymers). 
* **Post-Processing:** Parts must be **washed and post-cured completely** according to the resin manufacturer's exact technical data sheet (TDS). Proper UV and thermal post-curing are mandatory to fully react any residual toxic monomers, ensuring the final device is completely non-irritating and safe for skin contact.

## File Organization
* `/CassandraFingerV5.FCStd` - The current, stable production model.

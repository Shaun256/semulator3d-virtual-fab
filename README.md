# Virtual Fabrication of a Self-Aligned nMOSFET and PN Diode

Individual course project, EE5312 VLSI Technology, IIT Madras (Oct 2026)

📄 **[Read the full report (PDF)](report.pdf)**

3D process models built in Coventor SEMulator3D at 1 nm voxel resolution.

## Process flows

| Device | Steps | Key steps |
|---|---|---|
| PN diode | 12 | Oxidation, lithography, implantation, metallisation |
| Self-aligned nMOSFET | 14 | Poly gate deposition, gate-masked S/D implant, nitride passivation, lift-off metallisation |

## Self-alignment

The poly gate is used as the implant mask, so the source and drain align to the gate edge without a separate lithography step.

## Validation

Junction depth was derived analytically from a Gaussian implant profile. The simulated doping profile matched it within **0.2 nm (0.5%)**.

## Tools

Coventor SEMulator3D

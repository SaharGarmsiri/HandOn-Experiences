# Summary of Ethernet Twisted Pair Network Cables

This document provides a structured overview of Ethernet twisted pair cables used in Local Area Networks (LANs), focusing on types, wiring standards, cable purposes, and categories.

---

## Key Concepts and Types of Twisted Pair Cables

Twisted Pair Cables are the most common Ethernet cables connecting devices such as computers, routers, switches, and modems.

### Types of Twisted Pair Cables

| Type | Shielding | EMI Protection | Common Usage | Notes |
|------|------------|----------------|--------------|-------|
| UTP (Unshielded Twisted Pair) | None | Reduced via twisting | Homes & businesses | Most widely used |
| STP (Shielded Twisted Pair) | Foil shielding | Higher EMI protection | Industrial environments | Less common in offices |

<p align="center">
  <img src="Pics/understandand_copper_cabling.webp" width="600">
</p>


---

## Cable Preparation and Connectors

| Step | Action |
|------|--------|
| 1 | Cut bulk twisted pair cable |
| 2 | Strip outer sheath using cable stripper |
| 3 | Arrange wires in correct color order |
| 4 | Insert into RJ45 connector |
| 5 | Crimp using wire crimper |

Correct wire ordering is essential before crimping.

---

## Wiring Standards

### General rule: ``one solid-colored wire, followed by one white-striped wire, repeating this pattern along the cable. ‍‍``

<p align="left">
  <img src="Pics/T568A-and-T568B-wiring-spec-standards.webp" alt="T568A and T568B Wiring Standards" width="400">
</p>

| Pin | 568A | 568B |
|-----|------|------|
| 1 | White/Green | White/Orange |
| 2 | Green | Orange |
| 3 | White/Orange | White/Green |
| 4 | Blue | Blue |
| 5 | White/Blue | White/Blue |
| 6 | Orange | Green |
| 7 | White/Brown | White/Brown |
| 8 | Brown | Brown |

**Difference:** The green and orange pairs are swapped.  
568B is more commonly used in the United States.

---

## Cable Types Based on Wiring

| Cable Type | End Configuration | Used For | Common Today |
|------------|-------------------|----------|--------------|
| Straight-through (Patch Cable) | Same standard on both ends (A–A or B–B) | Connecting dissimilar devices (PC → Switch, Router → Modem) | Very common |
| Crossover Cable | One end 568A, other 568B | Connecting similar devices (PC → PC, Switch → Switch) | Less common |

---

## Categories of Twisted Pair Cables

| Category | Maximum Speed | Distance | Notes |
|----------|--------------|----------|-------|
| CAT 3 | 10 Mbps | 100m | Obsolete |
| CAT 5 | Up to 100 Mbps | 100m | Largely obsolete |
| CAT 5e | 1 Gbps | 100m | Minimum modern standard |
| CAT 6 | 1 Gbps (55m), 10 Gbps (short distance) | 55m (10G) | Popular |
| CAT 6a | 10 Gbps | 100m | Improved shielding |
| CAT 7 | 10 Gbps | 100m | Fully shielded, backward compatible |
| CAT 8 | 40 Gbps | 30m | Highest copper speed |

---

## Performance Notes

- Higher category numbers mean tighter twists and reduced crosstalk.
- Most modern networks use at least CAT 5e.
- CAT 6a or CAT 7 is recommended for 10 Gbps.
- CAT 8 supports 40 Gbps over short distances (~30 meters).

---

## Key Insight

Twisted pair cables are essential for wired Ethernet connections and are mainly available as UTP and STP.

---



## Recommended & Sources Videos

https://youtu.be/_NX99ad2FUA?si=41XDL0wrzqqyK1Ll

https://youtu.be/y8h5qY3zwic?si=8Z0PkCR749KkbU-D

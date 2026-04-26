# Modeling the Spread of Misinformation
### MATH 5131 | Desiree DeGennaro | Northeastern University

## Overview
This project builds a compartmental ODE model for how a false rumor spreads
through a population, motivated by the harm that QAnon-style misinformation
causes to anti-trafficking efforts. The model adapts the Daley-Kendall (1964)
ISS framework and extends it with a platform debunking term and a time-delay
component representing deliberation before sharing.

## Main Results
The model produces three actionable numbers:
- **δ* = 0.09**: minimum platform debunking rate to suppress the rumor from the start
- **p* = 0.90**: minimum pre-emptive awareness campaign coverage to prevent spread entirely
- **τ effect**: deliberation delays of τ = 10 and τ = 30 increase total exposure
  from 1% to 21.9% and 27.2% respectively, making real-time platform intervention
  more critical

  ## References
- Daley & Kendall (1964). Epidemics and Rumours. *Nature* 204, 1118.
- Piqueira, Zilbovicius & Batistela (2020). Daley-Kendall models in fake-news scenario. *Physica A* 548.
- Prakash, Erickson & Stoklosa (2022). Human trafficking and the growing malady of disinformation. *Frontiers in Public Health* 10.
- Barnes & Fulford (2015). *Mathematical Modeling with Case Studies*, 3rd ed. CRC Press.

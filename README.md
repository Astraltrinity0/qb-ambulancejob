## Functions
- Adds automatic billing for patient (Configurable)
  - Checks whether patient has enough money in bank. 
- Adds payouts for medics (Configurable)
- Two Variants
  1. Autobilling Only
  2. Autobilling w Payout + [AI Medic](https://github.com/Astraltrinity0/aimedic) Compat

## New Configuration
```lua
Config.AutoBilling = 2500                                    -- Price that players are charged when being revived by a medic (Outside of Hospitals)
Config.CutAmount = 500                                       -- Amount of money awarded to the medic per revive

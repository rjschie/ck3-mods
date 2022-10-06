TODO
===========================
- Test:
  [x] Dracul Trait
  [x] Kingdom title `give_title k_ordinul_dracului`
  [x] Faith `set_faith ordinul_dracului`
    - kind of... crashes, but I think it's due to no head of faith existing
    - check faith_creation event series for how to do this
  [ ] Become Dracul Decision
  [ ] Found Order Event `event found_ordinul_dracului.0001`
  [ ] Found Order Decision
    [ ] Fires Event
+ Update Traits
+ Fix Become Dracul Decision localization

IDEAS
===========================
Create my own "perk" tree
After founding new order: swap "Cynical" with "Zealous"
Add "Cannibal" at some point?

QUESTIONS?
===========================



Potential Graphics
==========================
# Major Religion
picture = "gfx/interface/illustrations/decisions/decision_major_religion.dds"

# Mountains
picture = "gfx/interface/illustrations/event_scenes/mountains.dds"

# Forest Pine
picture = "gfx/interface/illustrations/event_scenes/forest_pine.dds"

# Alley Night
picture = "gfx/interface/illustrations/event_scenes/alley.dds"

# Battlefield
picture = "gfx/interface/illustrations/event_scenes/battlefield.dds"

# Runestone Circle
picture = "gfx/interface/illustrations/event_scenes/fp1_runestone_circle.dds"


TRAITS to add
===========================
Education:
  Insightful Thinker
Personality:
  Wrathful
  Patient
  Ambitious
  Cynical
  Callous
Traits:
  Dracul
  Family Heirarch
  Blademaster
  Master Hunter
  Overseer
  Schemer
  Seducer
  Torturer
  Whole of Body
  Reclusive
  Beautiful
  Intelligent
  Hale
  Peasant Leader
  Flexible Leader
  Rough Terrain Expert
  Winter Soldier

Sum Values of above traits (used to calculate the "Dracul" trait values)
---------=======---------
All combined give:
Diplomacy:   +2  +4 = +6
Martial:     +9  +5 = +14
Stewardship: +5  +3 = +8
Intrigue:    +15 +3 = +18
Learning:    +12 +2 = +14
Prowess:     +19 +8 = +27

Monthly lifestyle gain:  +20% +20%
Learning lifestyle gain: +20%

Health:         +0.75 +5
Disease Res.:   +0.5  +1
Dread:          +20   +20
Dread Gain:     +70%  +50%
Dread Decay:    -25%  -
Fertility:      +90%  -100% = -10%
Stress Gain:    +5%   -
Stress Loss:    +60%  -
Piety Gain:     -20%  -

Hostile Scheme Power:      +25%
Hostile Scheme Resistance: +35%

Vassal opinion:   +5
Liege opinion:    +5
General opinion:  -10
County opinion:   +10
Attraction:       +70
Close Relative:   +10
House Opinion:    +10

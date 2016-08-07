# Squids2
A 2D pond with simple evolving AI life forms.
Pulling ideas from Squids (original) and Pond-Physics. This should end up like ventrella's darwin with any luck. A
See in original Darwin pond  [here](http://www.ventrella.com/Darwin/darwin.html)

# MANUAL

## DNA
Each Squid is born with a digital DNA fingerprint. This is a HEX string with the following form:
- DNA = [N, S, J, A, P, R, C, K ]
  - N = (Mod(0-F,3)) Number of Limbs
  - S = (Mod(0-F,3)) Number of Segments per limb
  - J = (0-F) Joint Angle
  - A = (0-F) Angle (=180/16*A)
  - P1 = (0-F) Period
  - P2 = (0-F) Period2
  - P = (Mod(0-F,2)) Limb Phase (determines how well syncornised the seperate limbs are)
  - C = (0-F) Colour as the Hue (=255/16*C) of HSB
  - K = (0-F) Colour shift

## Food

## Mating

## Thinking

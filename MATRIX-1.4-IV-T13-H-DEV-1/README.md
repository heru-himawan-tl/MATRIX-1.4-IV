# MATRIX 1.4 IV T13 Class-H Development Release I

This is development release I of class-H of MATRIX 1.4 IV T13 audio power
amplifier design. This model designed to yield at least 1400 watts RMS for
4-ohms loudspeaker. It includes the high speed TFF-like stepper, applies
the toggle flip-flop or T-type flip-flop principle.

## Feature: TFF-like Stepper

A TFF-like stepper is a sequential stepper that designed to work like a
toggle flip-flop. It will switch the power supply rails straightforwardly
even if the power amplifier reach 20 kHz signal amplification.

The TFF-like principle application will prevent unexpected drop of the
stepper switching by locking the stepper sensing input with the positive
feedback, like a toggled TFF. The locking will allow the stepper to wait
the power amplifier output amplitude turn back into the level bellow the
designated lower toggle level voltage upon the switching sequence is
occurring.

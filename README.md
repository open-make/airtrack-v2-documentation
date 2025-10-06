# Airtrack - plus maze - Bpod version


# Vision

We want to do electrophysiological recordings (Neuropixel) on mice performing the plus maze behavior experiment in the Airtrack system (Dominiak et al 2018 / Bergmann et al. 2020). The setup should do the behavior while we record electrophysiological data. Video data is used to monitor eye and whiskers movement.


Changes from version without recording: 
- Recording needs better electrical isolation
- Markers for platform tracking are now visible from above


# people involved
 

- Robert Sachdev (supervision)
- Jens Kremkow (supervision)
- Fabio Reeh (master student)


People doing similar things in the lab:

- Moritz (behavior)
- Jelte, Mik (Neuropixel)
- Quon
- Eduardo (lick sensing)


## Research roadmap


### Hardare change (until July): 
    - past: using Arduino, Flashlights from below, UV lamps from above

    - new lick detection system from workshop (dual lick sensor) : used by Eduardo in another experiment.
    - Bpod r2+
    - Lightniing (marker detection needs more light): 
        - LED for mouse feedback (same as before)
        - marker needs light : Infrared lamps (we have experience with it for other behavior).


    - Fix the lick detector: Eduardo asked the workshop already - current power supply to noisy

### Behavior (until September):

- can the animal move the thing - yes, the 100 gramm heavy platform is good moveable by the mouse
- train the animal to get reward

## Experiments (until Feburary 2026)

- 2 batch of 3 animals.

# Design choices


- UV lamps on batteries/plugin (noise if not shielded) may be used if infrared does not work.
- We will try the big platform, a smaller one might be needed to be used later
- Headpost chosen which does not cover brain areas we want to investigate
- Use the multi chain version of Neuropixel


## Eye/whiskers tracking
- Video data
- Post experiment analysis
- ML analysis with sleap
- UV marker at the wisker


## dependencies

Hardware:
    - Bpop
    - neuropixel
Software:
    - Matlab
    - Spikeglx will be used for data analysis
    - video data analysis with sleap

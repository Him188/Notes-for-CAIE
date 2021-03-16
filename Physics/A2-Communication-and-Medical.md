# Table of contents

- [Telecommunication](#telecommunication)
  - [What is meant by `frequency modulation`/`amplitude modulation` \[2\]](#what-is-meant-by-frequency-modulationamplitude-modulation-2)
  - [Why FM costs more than AM \[2\]](#why-fm-costs-more-than-am-2)
  - [What is meant by `noise` \[2\]](#what-is-meant-by-noise-2)
  - [What is meant by `attenuation` of a signal \[1\]](#what-is-meant-by-attenuation-of-a-signal-1)
  - [Why regenerator amplifiers do not amplify the noise \[2\]](#why-regenerator-amplifiers-do-not-amplify-the-noise-2)
  - [Why use infra-red than visible light in optic fibres \[2\]](#why-use-infra-red-than-visible-light-in-optic-fibres-2)
  - [Frequency range of waves \[5\]](#frequency-range-of-waves-5)
  - [What is meant by `cross-talk` \[2\]](#what-is-meant-by-cross-talk-2)
  - [Functions of the copper braid \[2\]](#functions-of-the-copper-braid-2)
  - [Draw a diagram for coaxial cable \[2\]](#draw-a-diagram-for-coaxial-cable-2)
  - [State three advantages of a coaxial cable compared with a wire pair \[2\]](#state-three-advantages-of-a-coaxial-cable-compared-with-a-wire-pair-2)
  - [The principles of the geostationary satellite \[4\]](#the-principles-of-the-geostationary-satellite-4)
  - [Compare ionospheric reflection of radio than satellite communication \[4\]](#compare-ionospheric-reflection-of-radio-than-satellite-communication-4)
  - [Why the uplink and downlink frequencies must be different \[2\]](#why-the-uplink-and-downlink-frequencies-must-be-different-2)
  - [What is meant by an `analogue signal` \[1\]](#what-is-meant-by-an-analogue-signal-1)
  - [What is meant by a `digital signal` \[2\]](#what-is-meant-by-a-digital-signal-2)
  - [Explain two advantages of the transmission of information in digital than analogue \[4\]](#explain-two-advantages-of-the-transmission-of-information-in-digital-than-analogue-4)
  - [Why base stations for mobile phone use high frequency \[2\]](#why-base-stations-for-mobile-phone-use-high-frequency-2)
  - [How to improve the quality of the received analogue signal (ADC-DAC) \[4\]](#how-to-improve-the-quality-of-the-received-analogue-signal-adc-dac-4)
  - [Why neighbouring cells use different carrier frequencies (mobile phone) \[1\]](#why-neighbouring-cells-use-different-carrier-frequencies-mobile-phone-1)
  - [Why each cell has a limited area (mobile phone) \[1\]](#why-each-cell-has-a-limited-area-mobile-phone-1)
  - [Why cellular exchange always operates for the phone \[3\]](#why-cellular-exchange-always-operates-for-the-phone-3)
  - [Explain the purpose of the switch in the mobile phone circuitry \[1\]](#explain-the-purpose-of-the-switch-in-the-mobile-phone-circuitry-1)
  - [Explain the purpose of the parallel-to-serial converter \[2\]](#explain-the-purpose-of-the-parallel-to-serial-converter-2)
- [Medical Physics](#medical-physics)
  - [Describe the functions of the two B-fields in MRI \[4\]](#describe-the-functions-of-the-two-b-fields-in-mri-4)

Telecommunication
-----------------

### What is meant by `frequency modulation`/`amplitude modulation` \[2\]
- frequency/amplifier of carrier wave varies
- ... in synchrony with displacement of information signal.

### Why FM costs more than AM \[2\]
- More complex circuitry
- More stations required (smaller ranges)

### What is meant by `noise` \[2\]
- *random* signal
- that added to transmitted signal.

### What is meant by `attenuation` of a signal \[1\]
- reduction in power of the signal.

### Why regenerator amplifiers do not amplify the noise \[2\]
- For signal only the high and low are necessary.
- Variation between highs and lows caused by noise not required.

### Why use infra-red than visible light in optic fibres \[2\]
- Less attenuation
- Fewer amplifiers

### Frequency range of waves \[5\]

| Type        | Wavelength      | Range         |
|:------------|:----------------|:--------------|
| space wave  | less than 10 m  | line of sight |
| sky wave    | 10 m ~ 100 m    | global        |
| ground wave | more than 100 m | 1000 km       |


### What is meant by `cross-talk` \[2\]
- picking up of signal in one cable
- ... from a second cable.

### Functions of the copper braid \[2\]
- acts as 'return' for the signal.
- shields inner core from noise.

### Draw a diagram for coaxial cable \[2\]

![CoaxialCable](.images/CoaxialCable.png)

### State three advantages of a coaxial cable compared with a wire pair \[2\]
- Less interference
- Less noise
- Greater bandwidth
- Less attenuation *(sometimes this is not in the MS)*

### The principles of the geostationary satellite \[4\]
- Carrier wave transmitted from Earth to satellite.
- Satellite receives greatly attenuated signal.
- Signal amplified and transmitted back to Earth.
- Different frequencies prevent swamping of uplink signal.

### Compare ionospheric reflection of radio than satellite communication \[4\]
- Ion layer varies in height **so unreliable**.
- Bandwidth too low **so cannot carry all information needed**.

### Why the uplink and downlink frequencies must be different \[2\]
- Signal must be amplified before transmission back to Earth.
- Uplink signal would be **swamped** by downlink signal.



### What is meant by an `analogue signal` \[1\]
- Signal has same variation as the data

### What is meant by a `digital signal` \[2\]
- Can be regenerated
- Extra data can be added to check

### Explain two advantages of the transmission of information in digital than analogue \[4\]
- Signal can be regenerated so that minimal noise.
- Extra data can be added so that signal can be checked for errors

### Why base stations for mobile phone use high frequency \[2\]
- Short wavelength
- ... so convenient length aerial.

### How to improve the quality of the received analogue signal (ADC-DAC) \[4\]
- Increase the number of bits used for each sample, to make `step height` smaller.
- Increase frequency of sampling, to make `step width` smaller

### Why neighbouring cells use different carrier frequencies (mobile phone) \[1\]
- No interference **near boundaries**.

### Why each cell has a limited area (mobile phone) \[1\]
- For large area, signal strength would be too large and very damage health.

### Why cellular exchange always operates for the phone \[3\]
- Mobile phone is sending out a signal.
- Computer *continuously* selects cell station
- ... with strongest signal.
- Computer allocates frequency.

### Explain the purpose of the switch in the mobile phone circuitry \[1\]
- Enables one aerial to be used for transmission and receipt of signals

### Explain the purpose of the parallel-to-serial converter \[2\]
- All bits for one number arrive at one time.
- Bits are sent out one after another.

Medical Physics
---------------

### Describe the functions of the two B-fields in MRI \[4\]
- Strong uniform field
- ... aligns nuclei.
- Non-uniform field
- ... locates nuclei.
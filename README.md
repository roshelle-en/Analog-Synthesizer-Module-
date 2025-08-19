# Analog-Synthesizer-Module-
Pure analog circuitry-based synthesizer

The Analog Synthesizer Module is a hardware project that leverages traditional electronic components to generate basic waveforms (sine, square, triangle, and sawtooth) and shape them into musical tones or complex soundscapes. Unlike digital synthesizers, this module emphasizes analog circuitry for authentic, warm sounds characteristic of classic synthesizers. Users can intuitively control parameters like frequency, amplitude, modulation, filter cutoff, and resonance to craft everything from melodic notes to dynamic audio textures.
The module supports a frequency range of 15 Hz to 300 Hz, includes envelope generation for amplitude dynamics, and allows mixing with external audio inputs (e.g., songs or recordings). It's designed for versatility in applications such as live performances, sound design, recording, or educational demonstrations in analog electronics.
Features

Waveform Generation: Produces sine, square, triangle, and sawtooth waveforms in the 15 Hz to 300 Hz range, serving as foundational building blocks for sounds.
Envelope Generation: Controls amplitude dynamics with adjustable attack, sustain, and decay for shaping sound evolution.
Low-Pass Filtering: Variable cutoff frequency and resonance to attenuate high frequencies and emphasize tones, allowing timbre customization.
Amplification: Built-in amplifier stage to boost signals for headphones, speakers, or external systems.
Audio Mixing: Integrates external audio inputs (via 3.5mm jack) with generated waveforms for hybrid sound creation.
User Controls: Potentiometers and switches for real-time adjustments to frequency, waveform selection, filter settings, envelope parameters, and volume.
Input/Output: 3.5mm jacks for audio input/output, ensuring compatibility with standard devices.
Durability and Safety: Enclosure made from high-quality, fire-resistant materials for reliable, user-friendly operation.

System Architecture
The synthesizer follows a modular block diagram architecture:

Voltage-Controlled Oscillator (VCO): Generates core waveforms.
Voltage-Controlled Filter (VCF): Applies low-pass filtering with adjustable cutoff and resonance.
Voltage-Controlled Amplifier (VCA): Manages signal amplification.
Envelope Generator: Shapes amplitude over time.
Power Amplifier: Boosts output for playback.
Controller: Oversees parameter adjustments and integration.

Key equations governing the circuits include RC differentiators/integrators, comparators, Schmitt triggers, op-amp integrators, adders, attenuators, amplifiers, subtractors, and BJT differential amplifiers. For detailed equations, refer to the project report in this repo.
Components
Component selection prioritizes low noise, stability, and audio suitability:

Oscillators and Filters: LM358 op-amps for low offset and high slew rate; 1% tolerance resistors/capacitors for precision.
Waveform Selection: SPDT switches.
Controls: 100 kΩ and 1 MΩ potentiometers for tuning.
Amplifier: LM386 for signal boosting.
I/O: 3.5mm audio jacks.
Other: Resistors, capacitors, and BJTs tailored for frequency response and gain.

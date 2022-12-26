This directory provides some examples for plotting the ADC survey data. The Jupiter notebooks can be opened and run in Google Colab (no local Jupyter installation needed). You can click the examples below to download high-resolution png files.

**Energy plot**: A/D conversion energy (power/sampling rate) versus signal-to-noise and distortion ratio (SNDR). Designs with high SNDR are typically limited by thermal noise. The energy quadruples per bit (6 dB) and a slope with constant Schreier FOM provides a good fit. For low SNDR, the energy tends to plateau at some CV<sup>2</sup>-type energy level (as opposed to energy needed to overcome noise). Process technology scaling can help with lowering the horizontal asymptote.

<img src="energy_plot.png" width="400" />

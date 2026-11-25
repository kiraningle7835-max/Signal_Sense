# Week 1: Python, NumPy, Matplotlib and Signal Basics

## Goals
By the end of this week you should be able to:
1. Use NumPy arrays and Matplotlib to create and plot data
2. Generate sine, square, triangular and sawtooth waveforms
3. Explain amplitude, frequency, period, phase and sampling rate
4. Add Gaussian noise and measure it with SNR

## Concepts in 5 minutes
- **Signal**: a quantity that varies with time (voltage, current, sound).
- **Amplitude**: how large the signal is. **Frequency (Hz)**: how many cycles per second. **Period**: 1 / frequency.
- **Sampling**: a computer stores a signal as points taken `fs` times per second.
- **Nyquist rule**: sample at least 2x the highest frequency, or you get *aliasing*.
- **Noise**: unwanted random variation. **SNR** measures signal power vs noise power.
- India's mains supply is a **50 Hz** sine wave, a good real-life example.

## Resources
**Python / NumPy / Matplotlib**
- NumPy quickstart: https://numpy.org/doc/stable/user/quickstart.html
- Matplotlib tutorials: https://matplotlib.org/stable/tutorials/index.html

**Signal intuition**
- 3Blue1Brown, "But what is the Fourier Transform?" (watch now, it is revisited in Week 2): https://www.youtube.com/watch?v=spUNpyF58BY

**Reference for later weeks**
- SciPy signal processing guide: https://docs.scipy.org/doc/scipy/tutorial/signal.html

## Tasks
1. Work through `01_signal_basics.ipynb` (runs top to bottom).
2. Complete the **Assignment** at the end of the notebook.
3. Push your notebook to your own GitHub repo and share the link in the group.

## Deliverable
A notebook that generates and plots all four waveforms, adds noise at three different levels, and reports the SNR for each.

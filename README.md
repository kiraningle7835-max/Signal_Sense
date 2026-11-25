# Signal Sense: Denoising and Classifying Electrical Waveforms

![Signal Sense banner](images/banner.png)

**WiDS 6.0 | Guided Project | Core Projects (Electrical Engineering + Data Science)**

---

## About the Project

Every electrical system, from power lines and motors to sensors and audio circuits, communicates through signals, and real-world signals are always noisy. This project shows how Data Science can clean, analyze and understand them.

Over 4 weeks, mentees will learn to **generate, denoise and classify electrical waveforms** using Python and machine learning. They will start with sine, square, triangle and sawtooth waves, add realistic noise, use the Fourier Transform to look at signals in the frequency domain, filter out the noise, and finally train ML models to classify the waveforms.

**The pipeline you will build**

```
Generate waveform -> Add noise -> Filter (denoise) -> Extract features -> Classify (ML)
```

**Key concepts:** sampling and aliasing, noise and SNR, Fourier Transform (FFT), filter design, feature engineering, supervised classification, model evaluation.

**Tools:** Python, NumPy, SciPy, Matplotlib, scikit-learn.

**Who is this for?** Beginners, including 1st-year students. No prior Electrical Engineering, Signal Processing or ML knowledge is needed, and all signal concepts are taught from scratch.

**Prerequisites:** basic Python (loops, functions, lists) and high-school trigonometry (sine and cosine).

---

## 4-Week Roadmap

| Week | Topic | Status |
|------|-------|--------|
| 1 | Python, NumPy, Matplotlib and signal basics (sampling, noise, SNR) | Available: [week1](week1/) |
| 2 | Fourier Transform / FFT and filter design with `scipy.signal` | Releasing soon: [week2](week2/) |
| 3 | Feature engineering and classification with scikit-learn | Releasing soon: [week3](week3/) |
| 4 | Final project and presentation | Releasing soon: [week4](week4/) |

**Week 2 - Fourier and Filtering:** time vs frequency domain, `np.fft`, spectrum plots, low-pass, high-pass and band-pass Butterworth filters, removing 50 Hz interference and high-frequency noise.

**Week 3 - Features and Classification:** FFT peaks, RMS, zero-crossing rate and spectral energy as features; Logistic Regression, SVM and Random Forest; accuracy and confusion matrix.

**Week 4 - Final Project:** pick one extension and build the full pipeline, e.g. classify power-quality disturbances (voltage sag, swell, harmonics), denoise a real ECG or audio signal, classify fault signatures in a simulated power line, or propose your own idea. Present your work at the end.

---

## Week 1: Python, NumPy, Matplotlib and Signal Basics

**Folder:** [`week1/`](week1/)

**Goals**
- Use NumPy arrays and Matplotlib to create and plot data
- Generate sine, square, triangle and sawtooth waveforms
- Explain amplitude, frequency, period, phase and sampling rate
- Add Gaussian noise and measure it with SNR (signal-to-noise ratio)

**What is covered**
- Signals, amplitude, frequency (Hz), period and phase
- Sampling and the Nyquist rule (with an aliasing demo)
- Adding noise and measuring SNR in dB
- India's 50 Hz mains supply as a real-life example

**Resources**
- NumPy quickstart: https://numpy.org/doc/stable/user/quickstart.html
- Matplotlib tutorials: https://matplotlib.org/stable/tutorials/index.html
- 3Blue1Brown, "But what is the Fourier Transform?": https://www.youtube.com/watch?v=spUNpyF58BY
- SciPy signal processing guide (for later weeks): https://docs.scipy.org/doc/scipy/tutorial/signal.html

**Tasks**
1. Work through [`week1/01_signal_basics.ipynb`](week1/01_signal_basics.ipynb).
2. Complete the assignment at the end of the notebook: generate a 50 Hz wave, plot all four waveforms, add noise at three levels and report the SNR for each.
3. Push your notebook to your own GitHub repo and share the link.

**Deliverable:** a notebook with all four waveforms, three noise levels and their SNR values.

---

## Getting Started

```bash
git clone https://github.com/<your-username>/signal-sense.git
cd signal-sense
pip install -r requirements.txt
jupyter notebook
```

No local setup? Upload the notebooks to [Google Colab](https://colab.research.google.com/) and run them there.

---

## Outcomes

- A working end-to-end denoise-and-classify pipeline
- A well-documented GitHub notebook
- A short final presentation
- A foundation for projects in power systems, communications, audio and biomedical analytics

---

## Mentor

**[Sai_Ingle]** | [Electrical Engineeering,2nd year, IIT Bombay] | [saiingle7835@gmail.com]

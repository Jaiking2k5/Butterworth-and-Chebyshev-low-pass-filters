# 🌀 Butterworth vs Chebyshev Filter Design (MATLAB)

## 🎯 Objective
The goal of this project was to **design a digital low-pass Butterworth filter** and understand its behavior by visualizing its frequency and step responses. To gain deeper insights, I also implemented a **Chebyshev Type I filter** of the same order and compared the two to observe how ripple and roll-off characteristics differ.

---

## 🛠️ Tools and Concepts Used
- **MATLAB** (core functions: `butter`, `cheby1`, `freqz`, `stepz`)
- **Digital Filter Design**: Butterworth and Chebyshev Type I
- **Visualization**: Frequency response, phase plots, step response
- **Concepts**: Passband flatness, ripple, cutoff frequency, system response

---

## ⚙️ How to Run
1. Open the `butterworth_filter.m` file in MATLAB.
2. Run the script. It will:
   - Design a Butterworth filter and a Chebyshev filter of the same order.
   - Plot magnitude and phase responses for comparison.
   - Plot step response of the Butterworth filter.
   - Print filter coefficients to console for reference.

---

## 📊 What You'll See

| Plot | Description |
|------|-------------|
| 🟦 Magnitude Response | Compares Butterworth (smooth roll-off) and Chebyshev (faster roll-off but ripple) |
| ⚫ Phase Response | Phase shift for Butterworth across frequencies |
| 🟢 Step Response | System’s time-domain behavior for Butterworth |

---

## 🧪 Key Observations
- The **Butterworth filter** had a smooth, ripple-free passband but a slower roll-off near the cutoff.
- The **Chebyshev filter** introduced some ripple (1 dB) in exchange for a sharper transition to the stopband.
- The **step response** showed stable, smooth behavior, as expected from a low-pass system.

---

## ✍️ Takeaways
This project helped me:
- Visualize how abstract filter specs translate into real system behavior.
- Understand the design trade-offs engineers make when choosing filters.
- Practice MATLAB coding in a clean, modular, and analytical way.

---

## 📁 Files Included
- `butterworth_filter.m` – Full script with design, plotting, and comparison
- `magnitude_response.png` – Output of frequency response plot
- `phase_response.png` – Butterworth phase response
- `step_response.png` – Butterworth step response



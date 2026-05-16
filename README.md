# PPG-Based-Heartbeat-Amplifier

A multistage PPG-based heartbeat amplifier designed and simulated using LTspice.  
The circuit filters, amplifies, and buffers low-amplitude heartbeat signals to drive a buzzer output.

---

## Features
- Active Low Pass Filter (LPF)
- Two-stage BJT amplification
- Buffer stage using emitter follower
- Adjustable gain and threshold
- Buzzer driving capability

---

## Components Used
- OP07 Op-Amp
- BC547 Transistor
- BC337 Transistor
- Resistors
- Capacitors
- DC Power Supplies

---

## Circuit Stages

### 1. Active Low Pass Filter
Removes high-frequency noise and motion artifacts from the PPG signal.

### 2. Stage 1 Amplifier
Common emitter amplifier for initial signal amplification.

### 3. Stage 2 Amplifier
Provides further voltage amplification.

### 4. Buffer Stage
Emitter follower used to prevent loading effect and drive the buzzer.

---

## Gain Calculation

| Stage | Gain |
|------|------|
| LPF | 1.47 |
| Stage 1 | -2.15 |
| Stage 2 | -5.3 |
| Buffer | ≈1 |

### Overall Gain
Overall Gain ≈ 16.7

---

## Software Used
- LTspice XVII

---

## Team Members
- Pranav RP
- (Add teammate names)

---

## Output
The circuit successfully amplifies weak heartbeat signals and produces a buzzer output corresponding to pulse peaks.

# Frequency Division Multiplexing


## AIM
To implement Frequency Division Multiplexing (FDM) for six different message signals using Scilab, generate the multiplexed signal, and perform demultiplexing to recover all the original message signals. The experiment also includes plotting the message signals, multiplexed signal, and demultiplexed signals.

## APPARATUS REQUIRED

1.Computer System

2.Scilab Software

3.Basic Signal Processing Commands

4.Plotting Tools (Scilab)

## ALGORITHM

1.Set sampling frequency, time duration, and time vector.

2.Generate six message signals with different frequencies.

3.Assign six different carrier frequencies.

4.Perform DSB-SC modulation by multiplying each message with its carrier.

5.Add all modulated signals to form the multiplexed FDM signal.

6.For each channel, multiply the multiplexed signal with the same carrier (demodulation).

7.Apply a low-pass filter to extract the recovered message.

8.Plot message signals, multiplexed signal, and recovered signals.

## THEORY

Frequency Division Multiplexing (FDM) is a technique in which multiple message signals are transmitted simultaneously over a single communication channel by assigning each signal a different carrier frequency. Each message modulates its own carrier, and all modulated signals are added to form the multiplexed signal. Since the carrier frequencies are well separated, the signals do not overlap in the frequency domain.

At the receiver, each signal is recovered by multiplying the multiplexed signal with the corresponding carrier (coherent demodulation) and passing it through a low-pass filter to extract the original baseband message. FDM is widely used in radio broadcasting, telephone systems, and cable TV.

## PROGRAM


## OUTPUT WAVEFORM


## CALCULATION


## RESULT
Six different message signals were generated and modulated using FDM. All modulated signals were added to form a multiplexed FDM signal. Each message was successfully recovered using coherent demodulation followed by low-pass filtering. The plots confirmed accurate multiplexing and demultiplexing.

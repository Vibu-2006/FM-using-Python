# FM-using-Python

Aim


To implement and analyze frequency modulation (FM) using Python's NumPy and Matplotlib libraries. 

Apparatus Required

1.	Software: Python with NumPy and Matplotlib libraries
2.	Hardware: Personal Computer
  
Theory

Frequency Modulation (FM) is a method of transmitting information over a carrier wave by varying its frequency in accordance with the amplitude of the input signal (message signal). The frequency of the carrier wave is varied according to the instantaneous amplitude of the message signal. The general form of an FM signal is:



Algorithm


1.	Initialize Parameters: Set the values for carrier frequency, message frequency, sampling frequency, and frequency deviation.
2.	Generate Time Axis: Create a time vector for the signal duration.
3.	Generate Message Signal: Define the message signal as a cosine wave.
4.	Compute the Integral of the Message Signal: Calculate the integral of the message signal over time.
5.	Generate FM Signal: Apply the FM modulation formula to obtain the modulated signal.
6.	Plot the Signals: Use Matplotlib to plot the message signal, carrier signal, and modulated signal.

Program
<img width="1216" height="564" alt="Screenshot 2025-10-26 211904" src="https://github.com/user-attachments/assets/e45d84d0-c166-42d0-ae3f-3769c35b0ffa" />


Output Waveform
<img width="941" height="604" alt="Screenshot 2025-10-26 211919" src="https://github.com/user-attachments/assets/cfa39102-2298-4939-b707-682a2e7b2f1d" />


Tabular Column

![WhatsApp Image 2025-10-25 at 22 57 54_6f5ce9c3](https://github.com/user-attachments/assets/ea5be37b-f68d-46bb-8a2a-724d2fc7c3ba)



Result


The message signal, carrier signal, and frequency modulated (FM) signal will be displayed in separate plots. The modulated signal will show frequency variations corresponding to the amplitude of the message signal.

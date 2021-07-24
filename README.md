# Audio-Equalizer
It is required to develop audio equalizer using MATLAB. One common Audio equalizer is the 
winamp program as shown in figure 1. The equalizer function is to vary the gain of each 
specific band as the user prefers. [ i.e. if the user likes base he will increase the gain of low 
frequencies ].
User should input the following:
1) The wave file name.
2) Gain of each of the frequency bands in dB.
3) Type of filters used (FIR-IIR)4) Output sample rate.
You may make use of the following functions: input – menu – uigetfile
Method:
1) Develop the frequency band filters in the following bands
A. ( 0- 170 Hz) - ( 170- 310 Hz) - ( 310- 600 Hz) -( 600- 1000 Hz) -( 1- 3 KHz) - ( 3- 6 KHz) - ( 6-
12 KHz) - ( 12-14 KHz) - ( 14-16 KHz)
2) Analyze and export these outputs (magnitude, phase, impulse and step response, order 
and gain/poles/zeros). 
3) Filter the wave file using the filters developed in step 1.
4) Draw the output signals in Time and frequency domains.
5) Amplify the output signals using the user defined gain.
6) Add the amplified - output signals in time domain to form composite signal.
7) Draw and compare the composite signal with the original signal. (in time and frequency) 
8) Play the output wave signal. (you can use wavwrite-sound) 

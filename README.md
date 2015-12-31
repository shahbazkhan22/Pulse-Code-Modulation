# Pulse Code Modulation MATLAB Code
## Important to note this that this is a function file not script, you need to pass parameters to execute this program.

#### Step 1.  Save "pcm.m" in your current directory of MATLAB

#### Step 2. define parameters  A, fm, fs, n  as rquired e.g. A=2, fm=3, fs=20, n=3

#### Step 3. then write  [y Bitrate MSE Stepsize QNoise]=pcm(A,fm,fs,n)

#### Or After step 1 just write [y Bitrate MSE Stepsize QNoise]=pcm(2,3,20,3) in command window

Explainantion of Parameters is as follow

A  = amplitute of cosine signal

fm = frequency of cosine signal

fs = sampling frequency

n  = number of bits per sample

y = binary output

MSE= Mean Squar error

QNoise = Quantization Noise

##### Example 
[y Bitrate MSE Stepsize QNoise]=pcm(2,3,20,3)
or
y = pcm(2,3,20,3)

####===========================================
###### If any doubt, confusion or feedback please contact
###### Nikesh Bajaj    http://nikeshbajaj.in
###### bajaj.nikkey@gmail.com
###### PhD Scholar, University of Genova and Queen Mary University of London

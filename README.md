# Signals-and-systems-utilities
Basic implementation of concepts used in signals and systems like convolution, Fourier transform etc.


-----------------------------Usage and Description of the Utilities----------------------------

1. convolution_builtInFunction.py

Description : Convolves two given sequences by two methods one of which is using the built-in numpy.convolve function.
Usage : Run the code on your terminal using  "python convolution_builtInFunction.py"
	When prompted to enter two sequences, for example, [2,3,5] and [4,6], just enter the values of the sequences as space separated integers.

2. convolution_newFunction.py

Description : Convolves two given sequences by defining a new function.
Usage : Run the code on your terminal using  "python convolution_newFunction.py"
	First enter the number of non-zero data points in the two sequences.
	Next, enter the x and y indices for every point in each of the two sequences, one-by-one.

3.fourierTransform.py

Description : Calculates Fourier Transform of two given sequences.
Usage : Run the code on your terminal using  "python fourierTransform.py"
	Choose one of the two given options. Further steps are similar to what were done in Utility 2.

4. linearityAndTimeInvariance.py

Description : Checks whether the pre-defined functions are linear and time-invariant or not. The pre-defined functions are described in the source code itself. 
Usage : Run the code on your terminal using  "python fourierTransform.py"
	Enter the values of parametres a, b and t0. Observe the plots that follow.

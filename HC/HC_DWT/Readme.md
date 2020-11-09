DWT data

In matlab:
[C,S] = wavedec2(X,N,wname) returns the wavelet decomposition of the matrix X at level N using the wavelet wname. The output decomposition structure consists of the wavelet decomposition vector C and the bookkeeping matrix S, which contains the number of coefficients by level and orientation.

Here we use two biorthogonal wavelets:bior1.1 and bior1.5 to to DWT. The results of cross-validation show elastic net has a better perfomance on bior1.1 data than bior1.5, We used bior1.1 data to do the following classification.

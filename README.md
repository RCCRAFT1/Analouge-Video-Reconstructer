# Video-Reconstructer
This Neural Network will decode and stitch An analogue video in it's RGB and generate a full color digital video 
It will take me a few weeks to complete, but a test run on a Youtube video every time I make a commit. In the future, this may also encode analouge audio into digital audio.
# How it works
Key: 
A: analouge video
D: Digi out
DE: Deconvolutional filter
DF: Digital Filter
CON: Convolutional Filter
COMB1: Combination Filter
RGB: Red Green and Blue A channels
COMB2: Combination Filter 2
IT: Iterations
FLMF: Function Last Minute Filtering

 A R>2000 IT through CON> 89275734576 IT through DF> 4 IT through COMB1>COMBINED TO G
 
 A G>1000-10000 iterations through CON> 89275734576 IT through DF> 4 IT through COMB1> 7000000 IT through DE> 3 IT through COMB2> 1 IT
 FLMF IF NEEDED> D
 
 A B>3000 IT through CON> 89275734576 IT through DF> 4 IT through COMB1>COMBINED TO G

 

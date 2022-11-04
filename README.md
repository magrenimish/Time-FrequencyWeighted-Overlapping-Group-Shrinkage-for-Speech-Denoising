# Time-FrequencyWeighted-Overlapping-Group-Shrinkage-for-Speech-Denoising </br>
This repository contains a paper and a brief presentation along with the results we obtained while improving upon the results obtained for speech denoising through the OGS-algorithm </br>
Please head to our collaberative repository for the detailed code and experiments (https://github.com/alexanderepstein/tfrogs)</br>
The paper is currently under review at the IEEE-ICASSP (Internation Conference on Acoustics, Speech and Signal Processing). </br>

Following is the abstract to our work </br>
Developing on the idea of using the predetermined structural
knowledge in convex optimization problems, we focus
specifically on the task of denoising speech samples. To this
end, we exploit the grouping/clustering property observed
with speech spectograms to iteratively obtain a sparse clean
speech signal using a mixed norm penalty term. We build
upon the Overlap Group Shrinkage (OGS) algorithm [3]
and introduce time-frequency weighting to the cost function
to rid the sparse clean signal of the residual noise.
This time-frequency weighting also empirically is shown to
extend the algorithm to effectively handle impulsive noise
types whereas the original algorithm was geared towards
white gaussian noise. We also notice that our extensions
for both time & frequency are generic meaning that we can
adapt our frequency weighting for the specific type of target
signal we are attempting to extract or from the inverse perspective
the noise we are trying to suppress. Additionally
depending on how the target or noise varies over time we
are able to focus on certain time slices more heavily than
others and that further improves the performance of the algorithm
in terms of both the SNR and intelligibility.

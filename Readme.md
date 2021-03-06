**Phase Coherence Classification**

The wavelet-based phase coherence classification decomposes signals such as the local field potential in electrophysiological recordings into subsignals depending on the pairwise phase-coherence relations. It then computes the power spectral densities of these subsignals thus allowing a detailed spectral analysis. For a detailed description see

von Papen, M. et al. (2017) *Phase-coherence classification: A new wavelet-based method to separate local field potentials into local (in)coherent and volume-conducted components*, Journal of Neuroscience Methods, 291, pp. 198–212. doi:10.1016/j.jneumeth.2017.08.021.

The wavelet transform is applied using a modified code originally provided by Torrence & Compo (see http://paos.colorado.edu/research/wavelets/). The modified code allows to perform the wavelet analysis for any given frequency instead of a logarithmically equidistant set of frequencies.

![PCC applied to local field potential wothin subthalamic nucleus (von Papen et al., 2017)](https://raw.githubusercontent.com/mvonpapen/PCC/LFP_P03_Ap_subsig.png)

Code at current stage needs some cleaning up and better commenting. This work is in progress. If you have any questions, please feel free to ask.

Language: Matlab

Test example: plot_synth_data.m generates a PCC of synthetic data as presented in Fig. 7 of *von Papen et al.* (2017) [requires mseb plotting function by Andreas Trier Poulsen (https://de.mathworks.com/matlabcentral/fileexchange/47950-mseb-x-y-errbar-lineprops-transparent-?focused=3861325&tab=function)]

Contributors: Michael von Papen (Juelich Research Centre, INM-6), Felix Gerick (University of Cologne, IGM)

License: GNU

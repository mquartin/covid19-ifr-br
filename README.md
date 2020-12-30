# Computation of Covid-19 Infection Fatality Rate from serology surveys

`epidata.nb` runs `epirun1.nb` or `epirun1-ab.nb` in order to obtain the time tau_ad and the number of deaths at the state or country levels. Note that SIVEP-Gripe and Painel Coronavírus data are compressed to save space. 

`epiresults.nb` imports results from the above notebooks in order to make summary tables. The previous notebooks compute the IFRs under the Gaussian approximaiton. 

Both prevalence and IFR values reported in the paper are obtained in `epicovid-ifr-public-v2.nb` by fully taking into account non-Gaussianities. You will need also to download and extract the file results.7z.

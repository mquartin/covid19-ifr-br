# Computation of Covid-19 Infection Fatality Ratio for Brazil

`epidata.nb` runs `epirun.nb` in order to obtain the time tau_ad and the number of deaths at the state or country levels. `epidata.nb` also makes summary tables and plots. Note that the IFRs are computed under the Gaussian approximaiton. Note that SIVEP-Gripe and Painel Coronavírus data are compressed to save space.

Both prevalence and IFR values reported in the paper are obtained in `epicovid-ifr-public-v2.nb` by fully taking into account non-Gaussianities. You will need also to download and extract the file results.7z.

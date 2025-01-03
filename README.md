# MI_secchi_library

Quantifying water clarity in Michigan inland lakes with Landsat-8 & -9 and Sentinel-2 imagery.


Structure:
- gen_rs_data: apply atmospheric correction to imagery and extract spectral reflectances at field sampled points (MISecchi_) or lake centroids (allLakes)
- tidy_rs_data: cleans and reformats Colab exported tables from the previous step

# Fuel-Cell-TomoData
https://tomobank.readthedocs.io/en/latest/source/data/docs.data.dynamic.html

## Dynamic
When setting a tomographic experiment several parameters are adjusted by the instrument operator including X-ray energy, exposure time, frame rate, rotary stage speed, scanning mode (sequential or interlaced angles etc.). Here we include a series of datasets collected at different experimental conditions aiming to capture fast evolving samples in 3D.

## Noisy Data
Sometimes data collection speed requirements, e. g. in evolving samples, impose very short exposure times generating noisy data. Here we include a dataset, Dorthe_F_002, in which the exposure time much shorter than the optimal value. The sample description and the experimental conditions are reported in tables below: and accessible for download under tomo_00031.

To load the data sets and perform a basic reconstruction using tomopy use the tomopy_rec.py python script.

## Lower Resolution
This study was optimized for temporal resolution and less for spatial resolution. The experiment was originally designed to follow the propagation of a Cs solution with time in a rock. The spatial resolution could be relaxed at the time of the experiment to provide sufficient time resolution.

In the second phase of the project, the focus moved however towards the smaller reactive inclusions and complementary techniques (x-ray microprobe and destructive chemical tomography with LA-ICP-MS) have been used to investigate the distribution of different elements and phases in selected regions, with sometimes higher spatial resolution than in the original tomographic dataset (see [gundlach:15], [burger:15]).

To load the data sets and perform a basic reconstruction using tomopy use the tomopy_rec.py python script.

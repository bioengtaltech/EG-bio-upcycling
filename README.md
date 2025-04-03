# EG-bio-upcycling
Metabolic modelling for biological upcycling of ethylene glycol (EG)
## Background
* Polyethylene terephthalate (PET) is a thermoplastic polyester of terephthalic acid (TPA) and ethylene glycol (EG) monomers (Kim and Lee, 2012).
* Sustainable hydrolysis of PET gives TPA and EG that can be used as a carbon source in yeast.
* *Rhodotorula toruloides* is a nonconventional, oleaginous yeast that can naturally accumulate high amounts of lipids and carotenoids, up to 76% as part of its dry biomass (Ageitos et al. 2011), and consume a wide variety of carbon substrates, including complex biomass mixtures (Bonturi et al. 2017).
* The repository contains the development of constraint-based metabolic models for EG utilisation as a carbon source in non-conventional yeast *Rhodotorula toruloides*.
## Installation
1. Create a Conda environment:
`conda create -n jupyter-env python=3.11`
`conda activate jupyter-env`
2. Clone the EG-bio-upcycling repository and avigate to the EG-bio-upcycling directory:
`git clone https://github.com/bioengtaltech/EG-bio-upcycling.git`
`cd EG-bio-upcycling`
3. For the operations, install Jupyter via conda:
`conda install -c conda-forge jupyterlab`
`conda install -c conda-forge notebook` (optional)
4. For Flux Balance Analysis optimizations, install Gurobi license (free for academic use):
`conda install -c gurobi gurobi` (we used gurobi=11.0)
5. Launch Jupyter in your default browser at http://localhost:8888:
`jupyter notebook`
## References
Senatore VG, Reķēna A, Mapelli V, Lahtvee P-J, Branduardi P. Ethylene glycol metabolism in the oleaginous yeast Rhodotorula toruloides. Appl Microbiol Biotechnol. 2025

Last modified: 2025-04-03.

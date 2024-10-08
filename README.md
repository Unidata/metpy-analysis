<div align="center">

<a href="https://www.unidata.ucar.edu/">
<img src="logos/unidata_logo_horizontal.png" width=65% alt="Unidata logo">
</a>

</div>

# MetPy for Quantitative Analysis of Meteorological Data

### ![](logos/metpy-32x32.png "MetPy Logo") Let's talk MetPy!
Here is a collection of notebooks for the MetPy for Quantitative Analysis of Meteorological Data workshop. The focus is primarily designed to show existing geoscientific Python users the capability and convenience MetPy can provide for working with data in meteorology. Topics include working with MetPy constants and units, remote data access using Siphon and THREDDS, and exploring quasi-qeostrophic theory and isentropic analyses using MetPy.

[Click this link to read our designed learning objectives for this material.](https://docs.google.com/document/d/e/2PACX-1vQ2_ekIS6wys69sPo87StV020seg9N2Mah6EKgRRRYotuV5oHzGvFmpWH28FYn8Egl-rLI-Rv1CZw8A/pub "Learning objectives for these course materials")

### :keyboard: Getting set up
For synchronous workshop learners, we have two separate ways you can participate, work ahead, and follow along.
If you've registered to attend, you will be given access to Unidata's Science Gateway to do your work on NSF's Jetstream Cloud.
If you prefer or require doing the work on your own computer, you are welcome to do so as well!

#### :cloud: Using [Science Gateway](https://science-gateway.unidata.ucar.edu/)
If you've registered for this workshop, you can do all of this work on our very own _gateway_ to the NSF Jetstream Cloud!
You have received instructions from Unidata on how to access Science Gateway.
After you are given access, you can sign in to Science Gateway with your provided GitHub username at [pyaos-workshop.unidata.ucar.edu](https://pyaos-workshop.unidata.ucar.edu).

When you first sign in, it may take a few seconds for your personal workspace to populate and your coding environment to be fully set up.
From here you will discover a Jupyter Lab interface pre-populated with these materials and a few tools to enable you to update the materials if needed.
Once you are given access, you will be able to download materials and notebooks from your workspace if you'd like, up until a brief time after the end of the workshop.

#### :computer: Using your computer
**Note that we at Unidata are not able to plan for any hardware limitations your personal computer might have, and we will not have time during the workshop to diagnose issues on personal computers.**
Please plan to use Science Gateway if this is a concern for you.
We will be using and supporting [Conda](https://docs.conda.io/en/latest/) for installing and managing a Python environment from your computer's command line.
Please have this environment prepared ahead of time if you'll be using your own computer.

> 1. [Install Miniconda](https://docs.conda.io/en/latest/miniconda.html#installing) if you don't already have command-line access to `conda`.
> 1. Get a copy of this code!
> You have a few options from the green button above,  
> a. `git clone https://github.com/Unidata/metpy-analysis.git` from your command line, within some directory on your computer.
> [Install git](https://github.com/git-guides/install-git) if necessary.
> If you're comfortable with `git`, we recommend this approach as it will let you keep this code regularly up to date.  
> b. [`Open with GitHub Desktop`](https://desktop.github.com/) if you have and prefer this graphically-focused software.  
> c. [`Download ZIP`]((https://github.com/dcamron/metpy-analysis/releases/refs/heads/main.zip)) if you prefer to get a single snapshot of the code right here and now.
> 1. Wherever you have this code saved, set up your Python environment with `conda env create -f environment.yml` from your command line.  
> 1. Give this some time.
> Once it's done, activate this new environment with `conda activate metpy-analysis`.
> Always do this before starting on work for this workshop!
> 1. Launch Jupyter and get to coding with `jupyter lab`.
> Don't forget to activate your environment first!

### :speech_balloon: Acknowledgements
The JupyterHub for this workshop is part of the [National Science Foundation](https://www.nsf.gov/) (NSF) funded [Unidata Science Gateway](https://doi.org/10.5065/688s-2w73) (doi:10.5065/688s-2w73) (under NSF Award [1901712](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1901712)).
We thank Andrea Zonca (San Diego Supercomputing Center), Jeremy Fischer (Indiana University), the NSF funded [Jetstream](https://dx.doi.org/10.1145/2792745.2792774) team, and the NSF funded XSEDE [Extended Collaborative Support Service](https://doi.org/10.1007/978-3-319-32243-8_1) (ECSS) program for assistance with this JupyterHub.

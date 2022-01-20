# AMS 2022 Student Conference Python Workshop

<div align="center">

<a href="https://www.ametsoc.org/index.cfm/ams/">
<img src ="https://www.ametsoc.org/themes/ametsoc-new/images/AMSlogoFull-web.png" width=65% alt="American Meteorological Society logo">
</a>

<a href="https://www.unidata.ucar.edu/">
<img src="logos/unidata_logo_horizontal.png" width=65% alt="Unidata logo">
</a>

</div>

## ![](logos/metpy-32x32.png "MetPy Logo") Let's talk MetPy!
Here you will find a collection of notebooks we will be demonstrating and working through together for this year's Student Conference Python Workshop. The focus will be on some of [Unidata's Python tools](https://www.unidata.ucar.edu/projects/index.html#python), including [MetPy](https://unidata.github.io/MetPy/latest/) and [Siphon](https://unidata.github.io/siphon/latest/), and the workshop is primarily designed to introduce beginners to the capability and convenience Python can provide for your work in meteorology.

## :arrow_right_hook: Pre-workshop materials
On Sunday, we will be working from `workshop.ipynb` live and synchronously. **Before the workshop**, go to the asynchronous [**pre-workshop**](https://elearning.unidata.ucar.edu/ams2022) from Unidata eLearning. As a minimum requirement, this will make sure your environment is ready for Sunday's activities. We also offer optional additional practice covering the core packages and concepts necessary to complete this workshop. The pre-workshop can help you decide if this practice is necessary for you.

## :keyboard: Getting set up
For this workshop, we have two separate ways you can participate, work ahead, and follow along.
If you've registered to attend, you will be given access to Unidata's Science Gateway to do your work on NSF's Jetstream Cloud.
If you prefer or require doing the work on your own computer, you are welcome to do so as well!

### :cloud: Using [Science Gateway](http://scigw.unidata.ucar.edu/)
If you've registered for this workshop, you can do all of this work on our very own _gateway_ to the NSF Jetstream Cloud!
After registration closes, you will receive instructions to access Jupyter Lab on the cloud.
After signing in with your GitHub account, this only requires a web browser and a stable internet connection.
Get to coding!

When you first sign in, it may take a few seconds for your personal workspace to populate and your coding environment to be fully set up.
From here you will discover a Jupyter Lab interface pre-populated with these materials and a few tools to enable you to update the materials if needed.
Once you are given access, you will be able to download materials and notebooks from your workspace if you'd like, up until a brief time after the end of the workshop.

### :computer: Using your computer
**Note that we at Unidata are not able to plan for any hardware limitations your personal computer might have, and we will not have time during the workshop to diagnose issues on personal computers.**
Please plan to use Science Gateway if this is a concern for you.
We will be using and supporting [Conda](https://docs.conda.io/en/latest/) for installing and managing a Python environment from your computer's command line.
Please have this environment prepared ahead of time if you'll be using your own computer.

> 1. [Install Miniconda](https://docs.conda.io/en/latest/miniconda.html#installing) if you don't already have command-line access to `conda`.
> 1. Get a copy of this code!
> You have a few options from the green button above,  
> a. `git clone https://github.com/Unidata/pyaos-ams-2022.git` from your command line, within some directory on your computer.
> [Install git](https://github.com/git-guides/install-git) if necessary.
> If you're comfortable with `git`, we recommend this approach as it will let you keep this code regularly up to date.  
> b. [`Open with GitHub Desktop`](https://desktop.github.com/) if you have and prefer this graphically-focused software.  
> c. [`Download ZIP`]((https://github.com/dcamron/metpy-workshop/archive/refs/heads/readme.zip)) if you prefer to get a single snapshot of the code right here and now.
> 1. Wherever you have this code saved, set up your Python environment with `conda env create -f environment.yml` from your command line.  
> 1. Give this some time.
> Once it's done, activate this new environment with `conda activate pyaos-ams-2022`.
> Always do this before starting on work for this workshop!
> 1. Launch Jupyter and get to coding with `jupyter lab`.
> Don't forget to activate your environment first!

## :speech_balloon: Acknowledgements
The JupyterHub for this workshop is part of the [National Science Foundation](https://www.nsf.gov/) (NSF) funded [Unidata Science Gateway](https://doi.org/10.5065/688s-2w73) (doi:10.5065/688s-2w73) (under NSF Award [1901712](https://www.nsf.gov/awardsearch/showAward?AWD_ID=1901712)).
We thank Andrea Zonca (San Diego Supercomputing Center), Jeremy Fischer (Indiana University), the NSF funded [Jetstream](https://dx.doi.org/10.1145/2792745.2792774) team, and the NSF funded XSEDE [Extended Collaborative Support Service](https://doi.org/10.1007/978-3-319-32243-8_1) (ECSS) program for assistance with this JupyterHub.

# HPC Documentation
[![Codacy Badge](https://app.codacy.com/project/badge/Grade/371210944a9a4d158aefffdaf6903ced)](https://app.codacy.com/gh/Open-Source-UAI/cluster-hpc/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)


In this repository the offical end user documentation of DaniLO cluster and installation steps

This documentation project makes use of [MkDocs Material Design Theme](https://squidfunk.github.io/mkdocs-material).

## Contributing

Everybody is invited to contribute to the doucmentation. If you find that certain topics
are not sufficiently covered or difficult to understand, you can fork this repository,
fix the respective part and then send us a pull request. Even for such small things like
typos! Yes, really, we appreciate your effort!

To make changes and test it locally, you have to setup mkdocs-material and all
other dependencies. We are delivering a conda environemnt file right within
this repo. A possible installation scenario for macOS using Homebrew might look
like:

```
# Install miniconda using Homebrew: skip if you already installed conda 
  brew install miniconda
  
# Setup conda
  conda init "$(basename "${SHELL}")"
  
# Fetch the documentation repository
  git clone https://github.com/Open-Source-UAI/cluster-hpc.git
  
# Create and activate the environment
  conda create -n hpcdocs python=3.10  
  conda activate hpcdocs
  
# Install required package
  pip install mkdocs-material
  
# Start the local mkdocs webserver that renders and displays all change instantly
  mkdocs serve
  
```
Thank you for your contributions!

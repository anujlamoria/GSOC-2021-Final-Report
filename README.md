# GSOC-2021-Final-Report
## Automatically identify Contributor Aliases (emails, platform user accounts) to Increase Parsimony of Statistics and Metrics With Privacy Enhancement
---
### Project Abstract
Augur is a software suite for collecting and measuring structured data about free and open-source software (FOSS) communities.The aim of my project was to make available a PyPy distributable Python package the core functionality currently within the Augur contributor worker, and envisioned as the next phase of the Augur contributor worker.
---
### Coding Phase 1
I began this phase by understanding the core functionality of augur and the importance of the health of open source community.Then i started to work closely on how the workers work and how augur collects its data.For the next step i moved on to working on the pypi package which introduceed me to some new concepts.For the Pypi package i first deleted all the frontend part that wasn't essential building the pypi package and also limit the number of workers to all that worked solely on python and machine learning workers were discarded.

### Coding Phase 2
This phase was used to deploy the PYPI package and how it might be used and what all steps were required in the installation.The Pypi package included basic packages that are nescessary for building the pypi package such as:
- Setuptools: Setuptools is a package development process library designed for creating and distributing Python packages.
- Wheel: The Wheel package provides a bdist_wheel command for setuptools. It creates .whl file which is directly installable through the pip install command.
- Twine: The Twine package provides a secure, authenticated, and verified connection between your system and PyPi over HTTPS.
---
### Requirements
System:
- Ubuntu 16.04
- macOS X
- Windows 10  
---
### Pull Requests
- [Augur PYPi package](https://github.com/chaoss/augur/pull/1339)
- [Augur PYPi package installation](https://github.com/chaoss/augur/pull/1344)
- [Fixed typo in Broker.py](https://github.com/chaoss/augur/pull/1426)

### Links
- [CHAOSS](https://chaoss.comunity)
- [Augur](https://github.com/chaoss/augur)

### ToDo
-Find ways to map contributors who use multiple email addresses within a platform or across platforms.

-Continue contributing to CHAOSS and improving code.

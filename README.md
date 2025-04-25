# Executable Environment for OSF Project [jpxts](https://osf.io/jpxts/)

This repository was automatically generated as part of a project to test the reproducibility of open science projects hosted on the Open Science Framework (OSF).

**Project Title:** Well-Being in Social Interactions: Examining Personality-Situation Dynamics in Face-to-Face and Computer-Mediated Communication

**Project Description:**
> Here we provide you with supplemental materials (Codebooks, Data, Statistical Code, Supplemental Analyses/Results) to the manuscript "Well-Being in Social Interactions: Examining Personality-Situation Dynamics in Face-to-Face and Computer-Mediated Communication".
Please cite as:
Kroencke, L., Harari, G. M., Back, M. D., &amp; Wagner, J. (2023). Well-being in social interactions: Examining personality-situation dynamics in face-to-face and computer-mediated communication. Journal of Personality and Social Psychology, 124(2), 437–460. https://doi.org/10.1037/pspp0000422

**Original OSF Page:** [https://osf.io/jpxts/](https://osf.io/jpxts/)

---

**Important Note:** The contents of the `jpxts_src` folder were cloned from the OSF project on **12-03-2025**. Any changes made to the original OSF project after this date will not be reflected in this repository.

The `DESCRIPTION` file was automatically added to make this project Binder-ready. For more information on how R-based OSF projects are containerized, please refer to the `osf-to-binder` GitHub repository: [https://github.com/Code-Inspect/osf-to-binder](https://github.com/Code-Inspect/osf-to-binder)

## How to Launch:

**Launch in your Browser:**

🚀 **MyBinder:** [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/code-inspect-binder/osf_jpxts/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment in your web browser.
   * Please note that Binder may take a few minutes to build the environment.

🚀 **NFDI JupyterHub:** [![NFDI](https://nfdi-jupyter.de/images/nfdi_badge.svg)](https://hub.nfdi-jupyter.de/r2d/gh/code-inspect-binder/osf_jpxts/HEAD?urlpath=rstudio)

   * This will launch the project in an interactive RStudio environment on the NFDI JupyterHub platform.

**Access Downloaded Data:**
The downloaded data from the OSF project is located in the `jpxts_src` folder.

## Run via Docker for Long-Term Reproducibility

In addition to launching this project using Binder or NFDI JupyterHub, you can reproduce the environment locally using Docker. This is especially useful for long-term access, offline use, or high-performance computing environments.

**Pull the Docker Image**

```bash
docker pull meet261/repo2docker-jpxts:latest
```

**Launch RStudio Server**

```bash
docker run -e PASSWORD=yourpassword -p 8787:8787 meet261/repo2docker-jpxts
```
Replace `yourpassword` with a secure password of your choice. You will use this to log in to the RStudio web interface.

**Once the container is running, visit `http://localhost:8787` in your browser.**
Use username: `rstudio` and the password you set with `-e PASSWORD=...`.

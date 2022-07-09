<!-- Add banner here -->

![Banner](https://github.com/dioapw/nagel-schreckenberg-model/blob/main/header_git.png)

# The Nagel-Schrekenberg Traffic Model

<!-- Add buttons here -->

![GitHub](https://img.shields.io/github/last-commit/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/contributors/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/commit-activity/y/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/license/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/codefactor/grade/github/dioapw/nagel-schreckenberg-model/main)
![GitHub](https://img.shields.io/github/languages/top/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/languages/count/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/repo-size/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/languages/code-size/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/tokei/lines/github/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/directory-file-count/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/issues/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/issues-closed/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/issues-pr/dioapw/nagel-schreckenberg-model)
![GitHub](https://img.shields.io/github/issues-pr-closed/dioapw/nagel-schreckenberg-model)
[![GitHub Super-Linter](https://github.com/dioapw/nagel-schreckenberg-model/workflows/Lint%20Code%20Base/badge.svg)](https://github.com/marketplace/actions/super-linter)
[![Dependabot auto-approve](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/dependabot-auto-approve.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/dependabot-auto-approve.yml)
[![Dependabot auto-label](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/dependabot-auto-label.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/dependabot-auto-label.yml)
[![Dependabot auto-merge](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/dependabot-auto-merge.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/dependabot-auto-merge.yml)
[![Dependency Review](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/dependency-review.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/dependency-review.yml)
[![DevSkim](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/devskim.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/devskim.yml)
[![Pyre](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/pyre.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/pyre.yml)
[![Python Package using Conda](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/python-package-conda.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/python-package-conda.yml)
[![Python package](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/python_env.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/python_env.yml)
[![auto-commit](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/auto_commit.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/auto_commit.yml)
[![automerge](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/automerge.yml/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/automerge.yml)
[![pages-build-deployment](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/dioapw/nagel-schreckenberg-model/actions/workflows/pages/pages-build-deployment)

<!-- Describe your project in brief -->

Have you ever been stuck in traffic and thought to yourself, "If other people drove better, I wouldn't be here?" Kai Nagel and Michael Schreckenberg, two German physicists, made a fundamental breakthrough in understanding and modeling the emergence of traffic jams. As it turns out, traffic jams are not random occurrences; rather, they are highly predictable.

# Demo-Preview
<!-- Add a demo for your project -->

**Traffic Jams can be Visualized using Space-Time Plots.**.

![image](https://user-images.githubusercontent.com/55073908/178119716-3077ad87-61b1-4205-bf99-dbd13e1972eb.png)
*Skanda Vivek's space-time diagram for the Nagel-Schrekenberg model with density 0.35 and p=0.3*

**What Causes Traffic Congestion?**

![image](https://user-images.githubusercontent.com/55073908/178119724-b9e4b640-1f60-4c70-9e94-812bd3636715.png)
*Velocity vs Density for the Nagel-Schrekenberg model | Skanda Vivek*

![image](https://user-images.githubusercontent.com/55073908/178119728-78b26098-b60a-49b9-ae4e-6c4cd48cb885.png)
*Flux versus density in the Nagel-Schrekenberg model with p=0.3 | Skanda Vivek*

**Simulating Traffic Jam using pyglet Library**

parameters $M$ = 300, $p$ = 33, $v_{0}$ = 0, number of vehicles $N$ = 30, $v_{max}$ = 6
![CarAnimationPygletLocal2](car_animation_pyglet_2.gif "animation_2")

**Simulating Traffic Jam using Turtle Library**

parameters $M$ = 100, $p$ = 0.3, $v_{0}$ = 0, $d$ = 2, number of vehicles $N$ = 20, $t_{max}$ = 1000, $v_{max}$ = 5
![CarAnimationTurtleLocal](car_animation_turtle.gif "animation_3")

# Table of contents

- [The Nagel-Schrekenberg Traffic Model](#the-nagel-schrekenberg-traffic-model)
- [Demo-Preview](#demo-preview)
- [Table of contents](#table-of-contents)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Footer](#footer)

# Installation
[(Back to top)](#table-of-contents)

**To use this project, first clone the repo on your device using the command below:**

```git init```

```git clone https://github.com/dioapw/nagel-schreckenberg-model.git```

```pip install -r requirements.txt```

```cd nagel-schreckenberg-model/```

**For Conda environment use:**

Create new environment using environment.yml

```conda environment create -f <path_to_yaml_file>```

Active the environment

```conda activate <environment_name>```

**You can use jupyter notebook or jupyter lab by using the commands:**

Jupyter Notebook

```jupyter notebook```

Jupyter Lab

```jupyter lab```

**For Non-Conda environment use:**

Make sure you install Python version 3.9

[Download Python 3.9](https://www.python.org/downloads/release/python-390/)

Open up a terminal or a command prompt. Once you are there, type the following command:

```pip install -r requirements.txt```

This installs all of the modules listed in our Python requirements file into our project environment.

> It is a good practice to set a new environment before installing packages with your Python requirements file.

After that you can open it with Jupyter Lab or Jupyter Notebook as described above.

**Or you can use Binder**

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/dioapw/nagel-schreckenberg-model/main?urlpath=tree)

# Usage
[(Back to top)](#table-of-contents)

Use this notebook as a study material, hopefully the readers can benefit from this even though I only collect from various sources.

# License
[(Back to top)](#table-of-contents)

License Copyright: Copyright © 2007 Free Software Foundation, Inc.
License License: "Everyone is permitted to copy and distribute verbatim copies of this license document, but changing it is not allowed." 
(www.gnu.org/licenses/gpl-3.0.en.html).
License Contact: Free Software Foundation (fsf.org).

SPDX short identifier: GPL-3.0-only

[GNU General Public License version 3](https://opensource.org/licenses/GPL-3.0)

The following are other community resources that may be helpful:

- [Choosealicense.com](http://choosealicense.com/) 
- [GNU License List](http://www.gnu.org/licenses/license-list.en.html)
- [OSSWatch License Diff](http://oss-watch.ac.uk/apps/licdiff/)
- [TLDRLegal](https://tldrlegal.com/)
- [Wikipedia License List](https://en.wikipedia.org/wiki/Comparison_of_free_and_open-source_software_licenses)

# Footer
[(Back to top)](#table-of-contents)

<!-- Add the footer here -->

![GitHub](https://img.shields.io/github/followers/dioapw?style=social)
![GitHub](https://img.shields.io/github/forks/dioapw/nagel-schreckenberg-model?style=social)
![GitHub](https://img.shields.io/github/stars/dioapw/nagel-schreckenberg-model?style=social)
![GitHub](https://img.shields.io/github/stars/dioapw?style=social)
![GitHub](https://img.shields.io/github/watchers/dioapw/nagel-schreckenberg-model?style=social)

**References**
- https://alg.manifoldapp.org/read/science-of-everyday-materials-4-4-2022/section/3bc8e64b-ec55-410c-b40b-265c93232f53
- https://towardsdatascience.com/traffic-jam-science-and-visualization-54f79ed006f1
- https://drive.google.com/drive/folders/1MrCf_5VHjTSrHkcEMBjQZBw5NSxlAR5E?usp=sharing
- https://docs.google.com/document/d/1bcfEv7_T0halb7NI6UT9-Jn3O6X-B3mosF7404JK_A0/edit
- https://github.com/rheum/NaSchSim
- https://www.freecodecamp.org/news/how-to-make-racing-game-using-python/
- https://www.lowgif.com/8f5a48839e61c7c7.html
- https://learnpython.com/blog/python-requirements-file/
- PDF Tugas Pemodelan dan Simulasi - Simulasi untuk Trafic Flow - June 7, 2022 (Telkom University)

![Trafficurl](https://alg.manifoldapp.org/api/proxy/ingestion_sources/c40c5285-d279-4085-ac37-fc4eeb9c4b62)
*Simulation of the Nagel-Schrekenberg traffic model at density 0.35 and p=0.3. Colors represent vehicle speed | Vivek Skanda*

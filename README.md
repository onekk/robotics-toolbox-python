# Robotics Toolbox for Python


Forked from 1.1.1 bugfix fork:

<a href="https://github.com/codeFighter2022/robotics-toolbox-python-bugfix">https://github.com/codeFighter2022/robotics-toolbox-python-bugfix</a>

Original work from:

A Python implementation of the <a href="https://github.com/petercorke/robotics-toolbox-matlab">Robotics Toolbox for MATLAB<sup>&reg;</sup></a>
<ul>
<li><a href="https://github.com/petercorke/robotics-toolbox-python">GitHub repository </a></li>
<li><a href="https://petercorke.github.io/robotics-toolbox-python">Documentation</a></li>
<li><a href="#6">ICRA Paper</a></li>
<li><a href="https://github.com/petercorke/robotics-toolbox-python/wiki">Wiki (examples and details)</a></li>
</ul>
</td>
</tr>
</table>

<!-- <br> -->

## Changelog in respect of upstream


Amended some files to make it work correctly:

- pyproject.toml to specify nunmpy and scipy versions that permit to run the code without patching too much the existing sources (to make it more near the upstream version)
- README.md to reflect the actual changes made in this fork and delete the pip way to install it.

Added files:

- rbtb-cd.yaml micromamba yaml file



## Usage


### Clone the repo from GitHub


```shell script
git clone https://github.com/onekk/robotics-toolbox-python
cd robotics-toolbox-python

```

### Use
The most straightforward way is to use micromamba:

See: 

https://mamba.readthedocs.io/en/latest/installation/micromamba-installation.html


and then create an environment using the supplied yaml file:

```shell script
micromamba create -f <robotics-toolbox-python>/rbmm_env.yaml
```

<br>
This will create an environment named <b>rbtb-dev</b>.
<br><br>
Activate this environment using:

```shell script
micromamba activate rbtb-dev

```

<br>

Then go to the <b>robotics-toolbox-python</b> folder and issue:

```shell script
pip install -e .

```

<br>
This will install the required packages with the correct versions in a way that will avoid conflicts keeping things separated from the system installed libraries and programs.

<br>

This will permit to avoid the use of complicated programs, you could issue most of these command on a terminal.

On Windows it is better to use the <b>Git Bash</b> shell that is usually installed when you install <a href="https://gitforwindows.org/"> Git for Windows. </a>



## Contents


# Original documentation

Find it here:

<a href="https://github.com/petercorke/robotics-toolbox-python">Original site </a>

## Notes:

None for now

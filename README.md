# Reproducible Data Visualization in Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/62442katieb/NH19-Visualization/binder-live)

A collection of notebooks demonstrating plotting with matplotlib, Seaborn, and Nilearn. Using these tools is a great way to produce high-quality figures, which can be reproduced using just your code and data.

### Matplotlib and Seaborn Galleries

The greatest part of matplotlib and seaborn are their galleries:

* https://matplotlib.org/3.1.0/gallery/index.html
* https://seaborn.pydata.org/examples/index.html

If you take nothing else from this session, please know that there are amazing examples that you can copy and paste and run for yourself.

These give you a great jumping off point for learning how to visualize your data.

### Installation

Visualisation tools change quite regularly, so the first step is to install an anaconda environment with the correct packages.
Don't forget to type `y` when conda asks you if you want to install some packages :smiley_cat:

```
conda create -n nh19-visualization python=3.7 nb_conda_kernels jupyter
```

Activate that environment and then install all the packages listed in the [requirements.txt](requirements.txt) file in this repository.

*If you don't run this command from inside of the repository then change `requirements.txt` to include the path (relative or absolute) to the file.*

```
conda activate nh19-visualization
pip install -r requirements.txt
```

Finally, make sure you can see this environment in [jupyter lab](https://jupyterlab.readthedocs.io/en/stable/).

```
python -m ipykernel install --user --name nh19-visualization
```

## Other example notebooks

* Tal's Visualization in Python tutorial from last year: https://github.com/neurohackademy/visualization-in-python/blob/master/visualization-in-python.ipynb
* Raincloudplots: https://github.com/RainCloudPlots/RainCloudPlots
  * [Binder link](https://mybinder.org/v2/gh/RainCloudPlots/RainCloudPlots/master?filepath=tutorial_python%2Fraincloud_tutorial_python.ipynb)
* The citation advantage of linking publications to research data:
 https://github.com/alan-turing-institute/das-public
   * [Binder link](https://mybinder.org/v2/gh/kirstiejane/das-public/master?filepath=notebooks%2FDescriptiveFigures.ipynb)

And one of my Google Summer of Code students would love for you to give him feedback on the `scona`🍪 visualizations that he's working on!

* https://github.com/WhitakerLab/scona/pull/145
* https://github.com/WhitakerLab/scona/pull/140
* https://github.com/WhitakerLab/scona/pull/121

# Py-SPHViewer #

Welcome to the main repository of Py-SPHViewer.

Py-SPHViewer is a framework for rendering particle simulations by using an SPH-like scheme on Python. It was started from my interest in making good movies of the evolution of the dark matter and gas in hydrodynamical SPH simulations and I work on it during my spare time. It was a personal tool for me but I think it is mature enough for sharing it. This project is currently under development and anyone that want to use it must be aware from that.

I have to say thanks to my brother Pablo Benitez-Llambay. His suggestions and ideas are helping a lot to the project. Certainly the project would not be what it is at this point without his help.

Maybe a good example of the current power of SPHViewer is the logo of the project:

![https://py-sphviewer.googlecode.com/svn/wiki/pysph-logo_small.png](https://py-sphviewer.googlecode.com/svn/wiki/pysph-logo_small.png)

This image shows the dark matter distribution colored according to the velocity dispersion of a small halo taken from a cosmological simulation. It was rendered (of course) using SPHViewer.

Another example of the power of SPHViewer are the following movies:

<a href='http://www.youtube.com/watch?feature=player_embedded&v=O6Adwk41J58' target='_blank'><img src='http://img.youtube.com/vi/O6Adwk41J58/0.jpg' width='425' height=344 /></a>

This movie shows a 3D rotation around a dark matter halo taken from a cosmological simulations.

Other example is:

<a href='http://www.youtube.com/watch?feature=player_embedded&v=XOcCguGU0cE' target='_blank'><img src='http://img.youtube.com/vi/XOcCguGU0cE/0.jpg' width='425' height=344 /></a>

This movie shows the result of my recent work, where we reported hydrodynamical interactions between dwarf galaxies and the large-scale structure of the Universe.


# Code Licence #

PySPHViewer is under GNU GPL v3 license and was started by Alejandro Benitez-Llambay. It is currently under development and changes everytime. It's your responsibility to be aware from the changes and to check the code for understanding what it does.

## **If you take advantage of PySPHViewer, please acknowledge the project.** ##

I would be glad to add collaborators to the project. If you want to collaborate, to add some feature you need, or just for fun, please let me know. There is a discussion group at http://groups.google.com/group/pysphviewer. This group is intended for
reporting bugs, asking questions, and for getting involved in the project.

# Basic Tutorial #

If you are interested in using PySPHViewer, you should take a look at the little [Tutorial](http://nbviewer.ipython.org/urls/py-sphviewer.googlecode.com/svn/wiki/tutorial_sphviewer.ipynb?create=1):


# Download and Installation #

The easiest way for downloading and installing Py-SPHViewer on your computer is by using easy\_install or pip:

```
easy_install py-sphviewer
```

or

```
pip install py-sphviewer
```

If you do not usually use easy\_install or pip, you can download the last release from the [Python Package Index repository](https://pypi.python.org/pypi/py-sphviewer). For some reason, Google has lost its ability to create new downloads on the download section, so you should not use it anymore. However, the older (and more buggy) versions are still available for downloading.
In case you download the project from Pypi, you should uncompress, build it and install it manually. You can build and install Py-SPHViewer with:

```
python setup.py build
python setup.py install
```

Finally, if you want to download the version under development, you can simply check out the latest project source code with:

```
svn checkout http://py-sphviewer.googlecode.com/svn/sphviewer/ sphviewer  
```

## Important: If you want to become an user of Py-SPHViewer, I strongly encourage you to get involved in the discussion group ##
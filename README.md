Dieses Repository enthält eine schrittweise Erklärung zur Funktionsweise von Entscheidungsbäumen.

Als Technologie wird [Jupyter Notebook](http://jupyter.org/) verwendet. Dieses Notebook kann auf verschiedenen Arten betrachtet werden:

* Unter [Github](https://github.com/the42/jupyter_golf/blob/master/Golf.ipynb)
* Mit dem [NBViewer-Service](http://nbviewer.jupyter.org/github/the42/jupyter_golf/blob/master/Golf.ipynb) von Jupyter

Alternativ gibt es eine Anzahl an Möglichkeiten die Funktionen von Jupyter interaktiv zu erleben, z.B.

* https://try.jupyter.org/
* https://studio.azureml.net/ or

Mit [Mybinder](http://mybinder.org/) existiert auch ein Dienst, welcher Jupyter-Notebooks interaktiv erlebbar macht.

Für lokale Installationen kann auch [RStudio](https://www.rstudio.com/) verwendet werden.

**Start**

    docker run -d -p 8888:8888 -e NB_UID=1000 --user root --name jupyter_golf -v /home/john/src/jupyter/golf:/home/jovyan/work jupyter/datascience-notebook

**Weiterführende Informationen**

* Möglichkeiten der Verwendung von [Data Science Notebooks](https://blog.ouseful.info/2014/12/12/seven-ways-of-running-ipython-notebooks/)
* Hätten Sie das [Titanic-Unglück](http://trevorstephens.com/kaggle-titanic-tutorial/getting-started-with-r/) überlebt?
* Entscheidungsbäume unter Verwendung des [C5.0-Algorithmus](http://www.patricklamle.com/Tutorials/Decision%20tree%20R/Decision%20trees%20in%20R%20using%20C50.html)

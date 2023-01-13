# List of various useful resources around Matplotlib 
This list is curated by [Teresa Kubacka](http://www.teresa-kubacka.com/) ([pythonviz.blog](https://www.pythonviz.blog/)). If you think a resource should be added, open an issue with your proposal! 

TOC: 
- [List of various useful resources around Matplotlib](#list-of-various-useful-resources-around-matplotlib)
  * [Cheat sheets](#cheat-sheets)
  * [Books](#books)
  * [Courses and workshops](#courses-and-workshops)
  * [Repositories with examples of complex visualizations](#repositories-with-examples-of-complex-visualizations)
  * [Tutorials](#tutorials)
    + [Community tutorials](#community-tutorials)
    + [Official tutorials you may have missed](#official-tutorials-you-may-have-missed)
  * [Resources using the plt-API, but still useful](#resources-using-the-plt-api-but-still-useful)
  * [MPL-lore, history and other meta-level material](#mpl-lore-history-and-other-meta-level-material)
- [MPL-compatible modules and extensions](#mpl-compatible-modules-and-extensions)
  * [Colors](#colors)
  * [Fun](#fun)

___ 

## Cheat sheets 
- [Official Cheat Sheets](https://github.com/matplotlib/cheatsheets)
- [E2ML chapter by Brandon Rohrer](https://e2eml.school/blog.html#131) 
- [How to cite Matplotlib (incl. Bibtex entry)](https://matplotlib.org/stable/users/project/citing.html)

## Books 
- [Scientific Visualization: Python + Matplotlib by Nicolas P. Rougier](https://github.com/rougier/scientific-visualization-book)
- [Coding for Economists by Arthur Turrell](https://aeturrell.github.io/coding-for-economists/vis-intro.html)
- [Python Data Science Handbook by Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/04.00-introduction-to-matplotlib.html)

## Courses and workshops 
- NumFocus Academy - Matplotlib course (beginner) by Nicolas P. Rougier [code](https://github.com/NFAcademy/2021_course_dev-rougier/tree/main/notebooks)
- Beyond the Basics: Data Visualization in Python by Stefanie Molin [code](https://github.com/stefmolin/python-data-viz-workshop)
- PythonMaps Scipy 2022 by Adam Symington [code](https://github.com/symmy596/PythonMaps-Scipy-2022) [video](https://www.youtube.com/watch?v=cjfqCHHp-AE&list=PLYx7XA2nY5Gfxu98P_HL1MnFb_BSkpxLV&index=5)
- Ipywidgets and MPL interactions Scipy 2022 [code](https://github.com/jupyter-widgets/tutorial) [video](https://www.youtube.com/watch?v=1vuI22MkkrY&list=PLYx7XA2nY5Gfxu98P_HL1MnFb_BSkpxLV&index=12) 
- Neural Network Visualization by Brandon Rohrer [code](https://github.com/brohrer/autoencoder_visualization) [video](https://end-to-end-machine-learning.teachable.com/p/neural-network-visualization) 

## Repositories with examples of complex visualizations 
- [Lisa-Ho](https://github.com/Lisa-Ho)
- [diego-gonher](https://github.com/diego-gonher/divulgacion/tree/main/visualizaciones)
- [symmy596](https://github.com/symmy596) - geoviz 
- [Kaggle: A story told through a heatmap](https://www.kaggle.com/code/tkubacka/a-story-told-through-a-heatmap)
- [sonofacorner](https://github.com/sonofacorner/soc-viz-of-the-week) - sport viz 
- [asongtoruin](https://github.com/asongtoruin)
- [rnckp](https://github.com/rnckp) - [SNSF-Data-Starter](https://github.com/rnckp/opendata_snsf-startercode), [Thematic Mapping Switzerland](https://github.com/rnckp/opendata_thematic-mapping)

## Tutorials

### Community tutorials 
- [Engineering for data science - Blog](https://engineeringfordatascience.com/tags/matplotlib/)
  - [Plotting subplots in a loop](https://engineeringfordatascience.com/posts/matplotlib_subplots/)
  - [Using plt.suptitle](https://engineeringfordatascience.com/posts/matplotlib_subtitles/) 
- DataFantic - Blog 
  - [Stylesheets](https://www.datafantic.com/the-magic-of-matplotlib-stylesheets/) 
  - [Reproducing The Economist style](https://www.datafantic.com/making-economist-style-plots-in-matplotlib-2/)
- [Blog of Gianluca Rigoletti](https://grigolet.github.io/index.html#category=matplotlib): 
  - ridgeplots 
  - reproducing CERN ROOT stylesheet
  - multiple Y axes 
- Pythonviz.blog: 
  - [Various useful snippets](https://www.pythonviz.blog/all_posts_categorized.html#category=matplotlib) 
  - [Small-multiples charts from scratch](https://www.pythonviz.blog/posts/mpl/mpl_small-multiples_ziplongest.html) 
- [Change font family](https://datascienceparichay.com/article/change-font-type-in-matplotlib-plots/)
- How to create custom hatches: [example 1](https://stackoverflow.com/questions/17285154/how-to-fill-a-polygon-with-a-custom-hatch-in-matplotlib) [example 2](https://stackoverflow.com/questions/4745937/how-to-decrease-hatch-density-in-matplotlib?rq=1) [example 3](https://malithjayaweera.com/2020/06/matplotlib-hatch-patterns/). In future releases of Matplotlib there will be a different API to create custom hatches [see discussion](https://github.com/matplotlib/matplotlib/issues/20690)
- [Son of a corner blog](https://www.sonofacorner.com/): 
  - [Create pretty tables from scratch](https://www.sonofacorner.com/beautiful-tables/)
  - [Coordinate systems](https://www.sonofacorner.com/figuring-figures-out/)
  - [Rolling average xG charts from scratch](https://www.sonofacorner.com/xg-rolling-plots/) 
  - [Stacked bars with annotations and icons from scratch](https://www.sonofacorner.com/effective-bar-charts-a-matplotlib-tutorial/) 
  - [Footbal shot maps](https://www.sonofacorner.com/shot-maps-a-matplotlib-tutorial/)
- [Practical Business Python](https://pbpython.com/): 
  - [Effectively Using Matplotlib](https://pbpython.com/effective-matplotlib.html)
- [Adam Ruszkowski's blog](https://ruszkow.ski/graphs/)
  - [Basic matplotlib Bar Plot Styling](https://ruszkow.ski/graphs/2022-11-01-basic-matplotlib-bar-plot-styling/)
- ["Artist" in Matplotlib - something I wanted to know before spending tremendous hours on googling how-tos](https://dev.to/skotaro/artist-in-matplotlib---something-i-wanted-to-know-before-spending-tremendous-hours-on-googling-how-tos--31oo)
- [plt.xxx(), or ax.xxx(), That Is The Question In Matplotlib](https://junye0798.com/post/plt-xxx-or-ax-xxx-that-is-the-question-in-matplotlib/)
- [Christian Hill's blog](https://scipython.com/blog/) - scientific visualizations and simulations with code examples 

### Official tutorials you may have missed 
- [How to create custom tables by Tim Bayer](https://matplotlib.org/matplotblog/posts/how-to-create-custom-tables/) 
- [Battery Charts by Rithwik Rajendran](https://matplotlib.org/matplotblog/posts/visualising-usage-using-batteries/) - create custom shapes, make them data driven 
- [Packed-bubble chart](https://matplotlib.org/devdocs/gallery/misc/packed_bubbles.html) - chart as a class; more circle packing chart than bubble chart 
- [Tips on structuring your MPL code by the MPL Project Lead Thomas A Caswell](https://github.com/NFAcademy/2021_course_dev-tacaswell/blob/main/notebooks/01_try_a_function_on.ipynb)
- [yourplotlib - Best practices for domain-specific matplotlib libraries by Colin Carroll, Hannah Aizenman, and Thomas Caswell](https://colcarroll.github.io/yourplotlib/)

## Resources using the plt-API, but still useful 
- [Matplot GIF on Calmcode](https://calmcode.io/matplot-gif/introduction.html) 
- [Matplotlib 3.0 Cookbook by Srinivasa Rao Poladi](https://github.com/PacktPublishing/Matplotlib-3.0-Cookbook) 
- [Python Graph Gallery](https://www.python-graph-gallery.com/) - a treasure of visualizations, but unfortunately the APIs used are not consistent 
- [Learning Scientific Programming with Python](https://scipython.com/book2/chapter-7-matplotlib/) - contains many interesting examples of mathematical visualizations with accompanying numpy/scipy algorithms, however the MPL API is sometimes inconsistent

## MPL-lore, history and other meta-level material 
- [John Hunter and Michael Droettboom explain the design choices they made](https://www.aosabook.org/en/matplotlib.html)
- [Matplotlib Lead Developer Explains Why He Can’t Fix the Docs—But You Can](https://numfocus.org/blog/matplotlib-lead-developer-explains-why-he-cant-fix-the-docs-but-you-can)
- [John Hunter's talk "matplotlib: Lessons from middle age"](https://www.youtube.com/watch?v=e3lTby5RI54)
- [Thoughts on how the MPL API could be more pythonic](https://ryxcommar.com/2020/04/11/why-you-hate-matplotlib/)
- my own NormConf Lightning Talk [How to stop crying when using Matplotlib](https://www.youtube.com/watch?v=vjQIaepijbE)

# MPL-compatible modules and extensions 

## Colors 
- [glasbey](https://github.com/lmcinnes/glasbey) - Algorithmically create or extend categorical colour palettes

## Fun 
- [ridge_map](https://github.com/ColCarroll/ridge_map) - A library for making ridge plots of... ridges. Choose a location, get an elevation map, and tinker with it to make something beautiful. 

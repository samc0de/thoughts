## Data visualization toolkits explored

Below are the python plotting libraries/toolkits I've found interesting:


- [Bokeh](https://bokeh.pydata.org/en/latest/) Still v < 1, Good for [contribution](https://bokeh.pydata.org/en/latest/docs/dev_guide.html#devguide). [Code](https://github.com/bokeh/bokeh).
- [Plotly](https://plot.ly/python/)
- [Mayavi](http://docs.enthought.com/mayavi/mayavi/index.html). [Code](https://github.com/enthought/mayavi)<sup>3</sup>
- [bqplot](https://github.com/bloomberg/bqplot)<sup>2</sup>
- [pygal](http://pygal.org/en/stable/). [This](https://pythonprogramming.net/pygal-tutorial/) maybe a useful resource to start with. [Code](https://github.com/Kozea/pygal/tree/7a556a2ef2640b2698480577959d1a9809673ae5).<sup>1</sup>
- [Altair](https://altair-viz.github.io/)
- [ipyvolume](https://ipyvolume.readthedocs.io/en/latest/) One of the few supporting 3d!<sup>1</sup>
- [vaex](http://vaex.astro.rug.nl/). [Github](https://github.com/maartenbreddels/vaex). By the same guy as ipyvolume.<sup>1</sup>


Till now I've played, very little, with the first 3 only. Some of the notes:

- Mayavi
  - Mayavi was the only candidate used for 3d plotting, Bokeh needs an extension for 3d. Plotly does support it.
  - It seemed quite slow in generating glyph as well as in interaction with o/p. Can only compare after I test with other plotting libs for 3d graphs.
  - By default it o/p's in it's own VTK window, so need to think/research for using or embedding it in applications.
  
- Bokeh and plotly look surprisingly similar in terms of behaviour in IPython and the generated o/p. A not-so-deep search didn't show any obvious relationsship though.
- Bokeh seems poorly documented, though its examples can act as documentation well.
- Plotly OTOH seems to have good documentation due to being a part of commercially supported package.

- The most interesting candidate atm is a new one though, `bqplot`. Looks very rich in the first glance.

In addition to these, another good (or at least possible) approach is using rendering tools (blender or any open source CAD from below list).
- Blender. * Links:
  - [1](https://docs.blender.org/api/2.78b/)
  - [2](https://docs.blender.org/api/blender_python_api_2_77_0/info_overview.html)
  - [3](https://docs.blender.org/manual/en/dev/game_engine/python_api/index.html)
  - [4](https://docs.blender.org/manual/ja/dev/advanced/scripting/introduction.html)
  - [5](https://medium.com/3d-printing-stories/why-i-use-and-recommend-blender-a15a6c80cb05#.mcxziqdql). [Related](https://medium.com/these-little-thoughts/am-i-talking-to-the-right-users-691d8bd65b36#.s9g4vlsq5).

- [FreeCAD](http://www.freecadweb.org/) *
- [OpenSCAD](http://www.openscad.org/) *
- [Autodesk 360](http://www.autodesk.com/products/fusion-360/students-teachers-educators). (free for personal/stud/teacher license)(lyk solidworks?)
- [OnShape](https://www.onshape.com/) Not free. Runs in browser, weak comps.
- [Leopard](http://projectleopard.com/) (autodesk, beta?)
- [CadQuery](https://github.com/dcowden/cadquery)*. Can be used as a plugin for FreeCad. Programmatic, 100% is done in programs. Some GUIs exist.
- [Sketchup make](http://www.sketchup.com/3Dfor/education-educators) Free [conditionally]( http://www.sketchup.com/license/c/sketchup).
- [Antimony](http://www.mattkeeter.com/projects/antimony/3/)*. See [this](https://github.com/mkeeter/antimony) too. 
- [ImplicitCad](http://www.implicitcad.org/). Also see [this](http://hackaday.com/2015/05/29/otherworldy-cad-software-hails-from-a-parallel-universe/)
- [Libre Cad](http://librecad.org/cms/home.html)* (Free but seems new)
- meshlab and netfabb seem useful.*

Some of these are extracted from my doc, and in turn from [a reddit discussion]( https://www.reddit.com/r/3Dprinting/comments/2nnjwg/whats_everyones_favourite_free_cad_software/).

<hr>

1. Code build breaking.
1. Docs breaking.
1. Code poor (test) coverage.

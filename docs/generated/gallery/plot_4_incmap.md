
<!--
 DO NOT EDIT.
 THIS FILE WAS AUTOMATICALLY GENERATED BY mkdocs-gallery.
 TO MAKE CHANGES, EDIT THE SOURCE PYTHON FILE:
 "docs/examples/plot_4_incmap.py"
 LINE NUMBERS ARE GIVEN BELOW.
-->

!!! note

    Click [here](#download_links)
    to download the full example code or to run this example in your browser via Binder


IncomingMap
=================================
> Combined WaferMap for Wafer Incoming Data

This example demonstrates how to import a local module and how images are
stacked when two plots are created in one code block. The variable ``N`` from
the example 'Local module' (file ``local_module.py``) is imported in the code
below. Further, note that when there is only one code block in an example, the
output appears before the code block.

<!-- GENERATED FROM PYTHON SOURCE LINES 12-18 -->


![None, MR, HDI](./images/mkd_glr_plot_4_incmap_001.png){: .mkd-glr-single-img srcset="/generated/gallery/images/mkd_glr_plot_4_incmap_001.png, /generated/gallery/images/mkd_glr_plot_4_incmap_001_2_0x.png 2.0x"}





```{.python }

from wfmap.data import load_data
from wfmap import create_incmap

data = load_data()
fig = create_incmap(data, vsigmas={'MR': 10, 'HDI': 1})
```


**Total running time of the script:** ( 0 minutes  2.385 seconds)

<div id="download_links"></div>

[![Launch binder](./images/binder_badge_logo.svg)](https://mybinder.org/v2/gh/smarie/mkdocs-gallery/gh-pages?urlpath=lab/tree/notebooks/generated/gallery/plot_4_incmap.ipynb){ .center}

[:fontawesome-solid-download: Download Python source code: plot_4_incmap.py](./plot_4_incmap.py){ .md-button .center}

[:fontawesome-solid-download: Download Jupyter notebook: plot_4_incmap.ipynb](./plot_4_incmap.ipynb){ .md-button .center}


[Gallery generated by mkdocs-gallery](https://mkdocs-gallery.github.io){: .mkd-glr-signature }
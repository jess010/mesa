# Basic Grid with two agents

## Summary

A very basic example model to showcase the visulaization on web browser.

A simple grid is dispalyed on browesr with two agents. The example does not
have any agent motion involved. This example does not have any movenment of
agents so as to keep it to the simplest of level possible.

This model showcases following features:

* A rectangular grid
* Text Overlay on the agent's shape on CanvasGrid
* ArrowHead shaped agent for displaying heading of the agent on CanvasGrid

## Installation

To install the dependencies use pip and the requirements.txt in this directory.
e.g.

```
    $ pip install -r requirements.txt
```

## How to Run

To run the model interactively, run ``run.py`` in this directory. e.g.

```
    $ python shapes_viz.py
```

Then open your browser to [http://127.0.0.1:8888/](http://127.0.0.1:8888/) and
press Reset, then Run.

## Files

* ``basic/model.py: Defines the Basic model and agents.
* ``basic/server.py``: Sets up the interactive visualization server.
* ``run.py``: Launches a model visualization server.

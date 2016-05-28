
#H2020 Deliverable LaTeX Template

This template was adapted from the netCommons project template [🔗](http://www.netcommons.eu).

## Usage

The file **main.tex** should be your master document, where you can include/remove chapters in your document.

You should also edit the file **title.tex** for defining deliverable specific options. In particular:

1. the deliverable title (`\newcommand{\DelTitle}{Title of this deliverable}`)
2. the deliverable number  (`\newcommand{\DelNumber}{DX.X}`)
3. and, the deliverable version (`\newcommand{\DelVersion}{0.X/1.0}`)

The project logo in the footer can be changed by editing the following line:

```
\newcommand{\footerlogo}{\raisebox{3mm}{\leavevmode\includegraphics[width=2cm]{SINet}}}
```

## License

Distributed under a Creative Commons license. See ``LICENSE`` for more information.

## About

This template results from the work conducted in the Software-defined Intermittent Networking [SINet](http://sinet.dpalma.eu) project.

The aim of this project is to define a networking solution for heterogeneous intermittent networks. The focus is on challenging environments such as the Arctic, addressing multi-disciplinary fields beyond surface communications, including space, airborne and underwater systems.

This project is funded by the European Union’s Horizon 2020 research and innovation programme under the Marie Sklodowska-Curie Grant Agreement No. 699924. The Individual Fellowship is hosted by NTNU, the Norwegian University of Science and Technology, including a secondment at BitReactive.


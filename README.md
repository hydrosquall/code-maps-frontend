# code-maps-frontend

Exploring the idea of using interactive auto-generated diagrams to make frontend code more understandable.

## Presentations

- [October 2019] React Conf: [Slides](https://slides.com/cameronyick/frontend-maps-react-conf-2019) / [Video](https://www.youtube.com/watch?v=SbreAPNmZOk) / [Transcript](https://www.datadoghq.com/videos/2020-auto-viz-of-the-frontend/)
- [September 2019] React Boston : [Slides](https://slides.com/cameronyick/frontend-code-maps) / [Video](https://www.youtube.com/watch?v=iS3BNfbDXzE)

Please feel welcome to send me maps of code that you have made or find elsewhere.

## Readings

- Mentioned
  - Papers
    - [Software Reflexion Models: Bridging the Gap Between Source & High Level Models](https://www.cs.ubc.ca/~murphy/papers/rm/fse95.html) - Gail C. Murphy, Kevin Sullivan, David Notkin (1995)
    - [The Eyes Have It: A Taxonomy for Information Visualization](https://www.cs.umd.edu/~ben/papers/Shneiderman1996eyes.pdf) - Ben Schneiderman (1996)
  - Articles
    - [How Graphic Design Legend Massimo Vignelli Cracked the NYC Subway System](https://www.ceros.com/originals/massimo-vignelli-nyc-subway/)
  - Books
    - [How to Lie With Maps](https://www.amazon.com/How-Lie-Maps-Mark-Monmonier/dp/0226534219) - Mark Monmonier
    - [History of the World in 12 Maps](https://www.amazon.com/History-World-12-Maps/dp/0143126024)
- Influenced but not directly quoted
  - [Questions Developers Ask During Change Tasks](http://pages.cpsc.ucalgary.ca/~sillito/work/fse2006.pdf) - Sillito (2006)
  - [Developers Ask Reachability Questions](https://dl.acm.org/citation.cfm?id=1806829) - Thomas LaToza & Brad Myers (2012)

## Tools

- Visual + Node Based Programming (not necessarily JS)
  - [Visual Programming Codex](https://github.com/ivanreese/visual-programming-codex)
  - Collections on are.na such as [Frederic Brodbeck's](https://www.are.na/frederic-brodbeck/dataflow-programming) or [@round](https://www.are.na/maxim-leyzerovich/visual-programming-aedh3fsg8nm)'s. Still working on curating my own.

- JS+TS Exploration
  - Files as Nodes
    - [ARKit](https://github.com/dyatko/arkit)
    - [Dependency-Cruiser](https://github.com/sverweij/dependency-cruiser)
    - [Madge](https://github.com/pahen/madge)
  - Functions as Nodes
    - Dynamic Callgraphs (Browser Devtools, [Flamebearer](https://github.com/mapbox/flamebearer))
    - Python/C Tools: [Pyan](https://github.com/davidfraser/pyan)
    - Static Callgraphs: [js-callgraph](https://github.com/Persper/js-callgraph)
  - Variables as Nodes
    - [Observable Debugger](https://observablehq.com/@mbostock/notebook-visualizer)
    - [Reselect Devtools](https://github.com/skortchmark9/reselect-tools)
  - State Machines
    - [XState](https://github.com/davidkpiano/xstate)
    - [Sketch.systems](https://sketch.systems/)

- Miscellaneous
  - [Python Callgraph](http://pycallgraph.slowchop.com/en/master/)
  - Data Engineering DAGs: Airflow and Dagster UI ([Compound nodes](https://dagster.readthedocs.io/en/0.5.9/sections/reference/reference.html#composite-solids))
  - Visualizing Audio Transformation DAGs: [NFGrapherJS](https://github.com/spotify/NFGrapher/issues/5)

- Influenced but not directly mentioned
  - Alternate network layouts (Hive plots, biofabric)
    - [The State of the Art in Visualizing Multivariate Networks](https://vdl.sci.utah.edu/publications/2019_eurovis_mvn/)
  - Generic graph analysis tools (Cytoscape + Gephi + Neo4j viewer)
  - Codecrumbs / Structuralizr TS / Dependo
  - Visual tools for performance/bundle optimization / code growth
    - Gource, Codeflower, hercules, git-of-theseus, bundlebuddy, etc
  - Bret Victor / Mindstorms (Papert) on tangible computing
  - Susie Lu's Keynote at Visfest Unconf 2019 - [Data Visualization Retrospective and Abstractions](https://www.susielu.com/data-viz/abstractions)

## Demos

- [Electron Demos from Section 3](https://github.com/hydrosquall/interactive-js-map)
- [Historical Train Schedule Remake](https://slides.com/cameronyick/metronorth-train-viz)
- [Github Radial Repository](https://github.com/hydrosquall/untitled-code-map) - An Electron version of an demo by Amelia Wattenberger. Not from the presentation, but explores related ideas.

## Related Readings / Watches

If you're read this far, you might also like these non-frontend specific resources:

- [Visualizing The Architecture](https://www.youtube.com/watch?v=zcmU-OE452k) - Simon Brown, Devternity 2016. See also his site [codingthearchitecture.com](http://www.codingthearchitecture.com/)
- [One-Page Design Docs](https://www.gdcvault.com/play/1012356/One-Page) - Stone Librande
- Readings on Wayfinding
- [Ruth Malan](https://www.ruthmalan.com/)'s public work on software architecture
- [Your Code as a Crime Scene](https://www.youtube.com/watch?v=qJ_hplxTYJw) - Adam Tornhill (TED 2016) - Applying forensic psychology to understanding code
- Trying out any GIS software (ArcGIS, ESRI, QGis) to get a feel for the potential of data-map overlays

## Contributing

If you see a resource that you think would be appropriate to include in this list, I welcome pull requests/issues.

In the future, the "recommended/cut for time" sections might split into a separate list of curated resources. In that case, this document will be limited to items specifically mentioned in the talk.

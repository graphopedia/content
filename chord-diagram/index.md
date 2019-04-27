---
title:  chord diagram

tags:

related:
  - sankey-chart
  - arc-diagram
  - hive-plot

tools:
  - name:   Circos
    link:   http://circos.ca/images/samples
    
  - name:   Flourish
    link:   https://flourish.studio/2018/07/25/how-to-make-a-chord-diagram/

  - name:   D3 Chord Diagram
    link:   https://beta.observablehq.com/@mbostock/d3-chord-diagram
    
  - name:   ZingChart
    link:   https://www.zingchart.com/gallery/#Chord
    
  - name:  amCharts
    link:  https://www.amcharts.com/demos/chord-diagram/
    
examples:
  - title:  Close-Ups of the Genome
    author: The New York Times
    link:   https://archive.nytimes.com/www.nytimes.com/imagepages/2007/01/22/science/20070123_SCI_ILLO.html
    image:  genome.jpg
    

  - title:  Leading Exporters and Their Trade With Each Other
    author:  Euromonitor International
    link:   https://blog.euromonitor.com/the-patterns-of-world-trade/
    image:  international-trade.png
    
  - title:  Impact of Major on Career Path
    author:  Hayley Brooks, Scott Sanderson, and Kaison Tanabe
    link:   https://web.williams.edu/Mathematics/devadoss/careerpath.html
    image:  college-majors.png
  
  - title: Harry Potter Relations Network
    author:  Nicole Mannell
    link:  https://www.behance.net/gallery/24910555/Harry-Potter-relations-network
    image:  harry-potter-relations-network.jpg
  
  - title:  C-Suite Gigs - A Web of Mad Skills
    author:  Vallerio Pellegrini
    link:  https://www.behance.net/gallery/58023115/WIRED-US-C-Suite-Gigs
    image:  c-suite-skills.jpg

    
synonyms:
  - radial network diagram
  - network chord diagram
  
---

shows flows between nodes in a network. The flows are represented by arcs the width of which represents values that describe the connection between any two nodes.

<!--more-->

The chord diagram was first used by The New York Times in [this genome chart](https://archive.nytimes.com/www.nytimes.com/imagepages/2007/01/22/science/20070123_SCI_ILLO.html); however, the use of chord diagrams has since extended beyond genomics.

## Purpose
The main feature on an chord diagram is its ability to show relationships between entities of the same type. These relationships are quantified which is represented by the thickness of the arc connecting them. They relationships can also show a direction.

## Usage
A chord diagram is similar to a [Sankey chart](/sankey-chart) in that both represent the strength of a connection between any two nodes as the thickness of a line. Unlike the Sankey chart, chord diagrams can only show relationships between nodes at the same level of hierarchy.

The nodes are located around the perimeter of the circle. They can be shown either individually or grouped into sectors, each sectors representing part of the whole, the whole being the circle, similar to a pie chart.

Clutter, also known as "hairballs" or overplotting is a known problem with chord diagrams. A way of grouping nodes into categories called hierarchical edge bundling [^holten] addresses this problem. 

Chord diagrams are sometimes mistakenly referred to as [arc diagrams](/arc-diagram). [^kirk]

## Alternatives

1. [*Sankey diagram*](/sankey-diagram) represents a flow of any kind, where the width of each arrow corresponds to the quantity of the flow. Sankey diagrams represent hierarchical data.

2. *Node-and-link diagram* displays connections between nodes of teh same level of hierarchy not does not show the numeric values representing the strengths of their connections.



## Sources

[^kirk]: ["Data Visualisation: A Handbook for Data Driven Design" by Andy Kirk, p. 189](https://books.google.com/books?id=ZrCJDAAAQBAJ&pg=PT295&lpg=PT295&dq=%22radial+network+diagram%22&source=bl&ots=aO2AtxUx3r&sig=ACfU3U3Fk3k7Via9TpgoSqwuUHPzcCl2oA&hl=en&sa=X&ved=2ahUKEwjY74LC4srhAhVi5eAKHf-2BbwQ6AEwCXoECAgQAQ#v=onepage&q=%22chord%20diagram%22&f=false)
[^holten]: ["Hierarchical Edge Bundles: Visualization of Adjacency Relations in Hierarchical Data" by Danny Holten, IEEE TRANSACTIONS ON VISUALIZATION AND COMPUTER GRAPHICS, VOL. 12, NO. 5, SEPTEMBER/OCTOBER 2006](https://aviz.fr/wiki/uploads/Teaching2014/bundles_infovis.pdf)


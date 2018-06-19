---
title: Talk of Talks
author: Talky Talker
date: Day of the Talk
sansfont: Gill Sans
output:
  scuro::scuro_md:
    highlight: zenburn
    highlight_paper: monochrome
    slide_level: 1.0
routput: yes
scuro: yes

...




# an example text slide


> - with an incremental
> - build

\note{<1>}{

And different notes on the first

}

\note{<2>}{

and second increments.

}

# an example table


Table: Something about cars

                      mpg   cyl   disp    hp   drat
------------------  -----  ----  -----  ----  -----
Mazda RX4            21.0     6    160   110   3.90
Mazda RX4 Wag        21.0     6    160   110   3.90
Datsun 710           22.8     4    108    93   3.85
Hornet 4 Drive       21.4     6    258   110   3.08
Hornet Sportabout    18.7     8    360   175   3.15

<!-- # an example graphic -->

<!-- ```{r graph, fig.cap="I think that I shall never see"} -->
<!-- ggplot(trees, aes(Girth, Height)) + -->
<!--     geom_point(color="white") -->
<!-- ``` -->

<!-- # ugly examples of custom placement and sizing -->

<!-- ```{r displaced, textblock_width=2.75, textblock_pos=c(0, 1), fig.height=3, fig.width=2, out.height=4, center=T} -->
<!-- p <- ggplot(mtcars, aes(factor(cyl))) + -->
<!--     geom_bar(color="white", fill="grey40") + -->
<!--     xlab("Another car thing") -->
<!-- p -->
<!-- ``` -->

<!-- \begin{textblock}{2.75}(3,2) -->

<!-- Look! a dodgy three-column layout! -->

<!-- With great layout power comes great, etc., etc. -->
<!-- \end{textblock} -->

<!-- \begin{textblock}{2.75}(6,1) -->
<!-- ```{r displaced-over, inside_textblock=T, center=T, out.width=2.75} -->
<!-- p -->
<!-- ``` -->

<!-- Text scaling: \\ -->
<!-- a cautionary tale. -->
<!-- \end{textblock} -->

<!-- # example code display -->

<!-- ```{r code, echo=T} -->
<!-- cor(anscombe$x1, anscombe$y1) -->
<!-- cor(anscombe$x2, anscombe$y2) -->
<!-- ``` -->

Definitely don't need to visualize.

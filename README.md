**Bandlines** were invented by Stephen Few as background for sparklines to aid quick interpretation, crucial on dashboards: *"Bandlines use horizontal bands of color in the background of the plot area to display information about the distribution of values. This information is similar to that found in a box plot.  To do this you must gather information about how values related to the measure that will be featured in the sparkline are distributed during a period of history that usually extends further into the past than the values that will appear in the sparkline itself. [...] Bandlines may be modified to represent other meaningful ranges besides quartile-based distributions."*.

The design document also describes glyphs for identifying **outliers**, as well as a complementary **sparkstrip** to show the value range bar, optionally with **strip plots** - transparent circles that show individual points and reveal their distribution (all shown), as well as other options. 

Stephen Few provides an exceptionally detailed and pertinent guide to show how to make, as well as **how to use** this specific type of visualization:

[**Introducing Bandlines by Stephen Few**](https://www.perceptualedge.com/articles/visual_business_intelligence/introducing_bandlines.pdf)

[Interactive example](http://bl.ocks.org/monfera/8dbaabf493fbc0c4ae0c)

[Larger dashboard example with article](https://www.perceptualedge.com/blog/?p=2138)

The example tser sampler generates a lot of outliers on purpose - to make them appear regularly, and to illustrate how outliers effect the bands.

[Source code](https://github.com/monfera/bandlines)

[License](https://opensource.org/licenses/BSD-3-Clause)

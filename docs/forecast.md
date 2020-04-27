## Coronavirus projections

Here is graph of approximated curves for the total number of daily reported cases of coronavirus cases (per 100k of population) for selected countries and their projections.

![](plotdump/scprojplots.png)

More details for each of these countries can be found below. Projections for some other countries can be found under [list of countries](list.md). 

It should be emphasized that **the only numbers used in the computations are daily reported cases (and for the case of Slovenia also the daily number of tests performed).** No other information of any kind, however relevant, is used. No estimates, assumptions, simulations, comparisons with other outbreaks etc for any epidemiological parameters are accounted for, let alone the changing effects of countermeasures or other dynamic factors.

These are therefore **not** scientific forecasts since we are not pretending we know of any credible way of estimating all the relevant parameters, and should be viewed simply as projections based only on available imperfect and often unreliable data.

The main projections we give uses only data from the past 3 weeks. The assumption here is that after three weeks people are no longer infectious and the dynamics of the early stages of the epidemic should not effect the future, so older data can be discarded.
For most countries and most of time, the best fit estimate has a tedency to underestimate actual daily rises, especially when the data is very noisy (for instance, when countries report no increase for several days and then report an extroardinary jump in one day). In order to correct this we also include a 'boostrap' estimate which at least partially compensates for this bias in the errors.

The basic the theory used to obtain these estimates is explained under [theory](theory.md). 

### Slovenia

The following graph shows the current (as of **{% include_relative plotdump/slodate.txt %}**) best fit for total number of cases. For the case of Slovenia the numbers of daily confirmed cases are normalised with respect to the number of daily tests, so these are not the raw daily numbers. As a result the fit has been tighter and estimates have been more accurate than for other countries.

![](plotdump/slologgraf.png)

This next plot shows the daily increases and daily increase estimates (together with rough expected error estimates) and the current projected curve. For Slovenia this bootstrap projection differs only slightly from the best fit projection. This means that on average the best fit has been a been a good estimate the number of daily cases, at least for now.

![](plotdump/slograf.png)

The next graph shows the estimated number of days since the peak of the outbreak, computed on the given date. If the projection is stable, the estimated distance from the peak should progress by 1 for each day that passes.

![](plotdump/slodfgraf.png) 

The last plot shows how the estimates for the total number of reported cases that will occur during the outbreak have changed with time. As we see, for Slovenia none of the projections have changed significantly for several weeks. 

![](plotdump/slofinalplot.png)

### Italy

The current (as of **{% include_relative plotdump/italydate.txt %}**) best fits for Italy.

![](plotdump/italyloggraf.png) 

![](plotdump/italygraf.png)

The large error estimates mean the new numbers are deviating from the current computed projection. This could indicate an actual change of dynamic of the epidemic or simply changes in the testing regime.

![](plotdump/italydfgraf.png)

Both estimates for the final number of cases for Italy have consistentently risen throughout the epidemic but the bias in the best fit projection has recently begun to fall and the two estimates seem to be converging.

![](plotdump/italyfinalplot.png)

### Austria

The current (as of **{% include_relative plotdump/austriadate.txt %}**) best fits for Austria.

![](plotdump/austrialoggraf.png)

![](plotdump/austriagraf.png)

After a period of fairly stable projections for Austria, the error estimates increased considerably in the second week of April when the numbers began overshooting the projection by much more than expected.

![](plotdump/austriadfgraf.png)

![](plotdump/austriafinalplot.png)

### Germany

The current (as of **{% include_relative plotdump/germandate.txt %}**) best 3-week data fit for Germany.

![](plotdump/germanloggraf.png)

![](plotdump/germangraf.png)

![](plotdump/germandfgraf.png)

As in the case for Italy, the best fit estimate for the total number of cases has risen through time, but the bootstrap estimate has been reasonably consistent.

![](plotdump/germanfinalplot.png)

### USA

The current (as of **{% include_relative plotdump/usadate.txt %}**) best fits for America.

![](plotdump/usaloggraf.png)

The best fit and bootstrap projections differ significantly and both estimates for the USA are still rising quickly (see below). This would suggest an unstable situation. It is not even certain that the peak is actually over. The large error estimates also imply that obtaining reliable estimates for the final outcome using just available data is difficult at the moment.

![](plotdump/usagraf.png)

![](plotdump/usadfgraf.png)

![](plotdump/usafinalplot.png)

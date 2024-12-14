<h1 align="center">Socioeconomic Effects on Health and Well-being Using U.S. County Level Data</h1>
*Note: This repo is not actively maintained - for any questions, please contact one of us through our email.*

<h2>Project Contributers</h2>
<table align="center">
<tr>
  <td align ="center">Lily Shaw</br>Angelo State University</br>Dept of Computer Science</br>lilyshaw861@gmail.com</td>
  <td align ="center">Steven Womack</br>Angelo State University</br>Dept of Computer Science</br>womack.st9@gmail.com</td>
  <td align ="center">Minh Le</br>Angelo State University</br>Dept of Computer Science</br>hle2@angelo.edu</td>
</tr>
</table>

<h2>Faculty Advisor</h2>
<table align="center">
<tr>
  <td align ="center">Erdogan Dogdu</br>Angelo State University</br>Professor/Department Chair</br>Dept of Computer Science</br>erdogandogdu@gmail.com</td>
</tr>
</table>

<h2>Abstract</h2>
<p>Using publicly available, county-level data on
social demographics, behaviors and health outcomes, we
explore select questions and correlations between factors.
The questions focus on the possible correlations between
socioeconomic factors, race/ethnicity, and health outcomes
for counties in which data was provided. Findings are
presented with correlational matrices and heatmaps of the
US counties for visualizations.</p>
<p>We attempt to answer questions like: Do areas
with higher negative economic factors have worse health
outcomes than areas with better economic factors? Is there
a correlation between educational attainment and health
outcomes? How does income inequality, childhood poverty,
affect health behaviors such as smoking, alcohol intake,
etc.? How do unemployment and lower insurance rates
affect mental health versus physical health outcomes? Do
areas with higher ratios of primary care physicians and
mental health providers have larger amounts of teen births?
As unemployment and educational attainment rise or fall,
do health outcomes change as a result? How does the
physical environment of an area (county) affect the health
outcomes of the population?</p>
<h2>Dataset</h2>
<p>For this study and project, we used <a href="https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation">County Health
  Rankings</a>. The data is collected and collated by the
University of Wisconsin. The data set is publicly available
and has been collected yearly since roughly 2004. It
includes all +3000 counties in the United States with the
majority reporting on most categories.</p>
<p>The dataset includes statistics on the health,
well-being, economics, and social factors of a county.
Many of these factors provide racial and ethnic
backgrounds for the factors chosen and collected. The
primary driver for the collection of data was to initiate
competition between regions and counties about improving
the lives of their citizens. This data is very comprehensive
in the collection of various types of factors.</p>
<h2>Results Synopsis</h2>
<p>Overall, our results were very interesting in a number of ways. Particularly in our lack of results in some areas of our focus. While we did find some interesting correlations between certain economic variables and health outcomes. Correlations appear to be very heavily regionalized throughout much of the United States. With as much data as was provided, the correlations appeared weaker than they actually were in some regions of the country. The geomaps of the United States and the scatterplots in our report show this very well.</p>
<p>Our predictive modeling was very hit or miss also. For our first question, we found that we could reliably generate a model for certain socioeconomic variables and health outcomes. With the strongest being educational attainment levels and the lowering of rates of poor health. Data on pollution surprisingly could not be used to generate a reliable model with health outcomes. Overall our lack of results in some areas was very surprising. For more detailed analysis, our full report with descriptions and our python notebook is available for viewing. 
</p>
<h2>References</h2>
<ul>
  <li>County Health Rankings. 2022. <a href="https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation">https://www.countyhealthrankings.org/explore-health-rankings/rankings-data-documentation</a></li>
  <li>Vega Datasets - County FIPS Code and Shape. 2022. <a href="https://github.com/vega/vega-datasets">https://github.com/vega/vega-datasets</a></li>
  <li>Numpy Documentation. 2022. <a href="https://numpy.org/doc/">https://numpy.org/doc/</a></li>
  <li>Pandas Documentation. 2022. <a href="https://pandas.pydata.org/docs/">https://pandas.pydata.org/docs/</a></li>
  <li>Seaborn Documentation. 2022. <a href="https://seaborn.pydata.org/">https://seaborn.pydata.org/</a></li>
  <li>Altair Documentation. 2022. <a href="https://altair-viz.github.io/getting_started/overview.html">https://altair-viz.github.io/getting_started/overview.html</a></li>
  <li>XGBoost Documentation. 2022. <a href="https://xgboost.readthedocs.io/en/stable/">https://xgboost.readthedocs.io/en/stable/</a></li>
  <li>SKLearn Documentation. 2023. <a href="https://scikit-learn.org/stable/">https://scikit-learn.org/stable/</a></li>
  <li>Arndt, Stephan, et al. "How reliable are county and regional health rankings?." Prevention Science 14 (2013): 497-502.</li>
  <li>Chen, Tianqi, et al. "Xgboost: extreme gradient boosting." R package version 0.4-2 1.4 (2015): 1-4.</li>
  <li>Govindarajulu, Z. "Rank correlation methods." (1992): 108-108.</li>
  <li>Kotsiantis, Sotiris B. "Decision trees: a recent overview." Artificial Intelligence Review 39 (2013): 261-283.</li>
  <li>McLeod, A. Ian. "Kendall rank correlation and Mann-Kendall trend test." R Package Kendall 602 (2005): 1-10.</li>
  <li>Montgomery, Douglas C., Elizabeth A. Peck, and G. Geoffrey Vining. Introduction to linear regression analysis. John Wiley & Sons, 2021.</li>
  <li>Peppard, Paul E., et al. "Ranking community health status to stimulate discussion of local public health issues: the Wisconsin County Health Rankings." American Journal of Public Health 98.2 (2008): 209-212.</li>
  <li>Remington, Patrick L., Bridget B. Catlin, and Keith P. Gennuso. "The county health rankings: rationale and methods." Population health metrics 13.1 (2015): 1-12.</li>
</ul>

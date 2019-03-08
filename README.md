# Analyzing and Visualizing School Shootings 1970 - Present 
By Lois Rosenbloom and Judah Esses

Packages & Libraries:

NumPy
Pandas
Matplotlib
Seaborn
Statsmodels
BeautifulSoup
Requests
For our mod-2 project, we used a School Shooting database we got from k-12 that goes all the way back to 1970.

We wanted to see how gun laws in different states effecting the count of school shootings per state so for the 2012-2016 gun law data, we manually put into excel due to it being a PDF file, and the 2017-2018 gun laws, we web-scraped the data from 'https://lawcenter.giffords.org/scorecard/#rankings' which was directly on their website.

We also wanted to see how population per state effects the count of school shooting so we downloaded those files as csv and xls that was from 2010-2017. This data was taken from 'https://www.census.gov/data/datasets/2017/demo/popest/state-total.html', 'https://web.archive.org/web/20180820005818/', and 'https://www2.census.gov/programs-surveys/popest/tables/2010-2017/state/totals/nst-est2017-01.xlsx'.

We then created DataFrames for all of the above and combined them into one DataFrame. From here, we were able to clearly view each incident of school shooting by state, population, and state gun law grade, as well as much more other data.

Our main goal was to see the relationship between gun control law grades and the number of incidents per state, seeing the effect it had on the number of gun incidents that occured at any given school in that particular state.

We made some visual representations, showing the amount of incidents per year, showing the amount of school shooting in a given state, the amount of mass shootings that occured in a given year, the amount of mass shootings that occured in a given state, correlation heatmap, how the number of shots fired correlated with number of victims wounded or/and killed, the amount of states per given gun law grade, number of incidents per year by state, as well as a few other tests.

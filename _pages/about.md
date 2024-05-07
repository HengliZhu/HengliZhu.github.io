---
permalink: /
title: "ABOUT ME"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! My name is Hengli Zhu, and I am pursuing a Master of Engineering in Financial Engineering at Cornell University. I have maintained an impressive GPA of 3.9/4.0, reflecting my strong academic performance and research capabilities in a challenging environment. Previously, I earned my undergraduate degree in Financial Engineering from Nanjing University, graduating with a notable GPA of 3.8/4.0 and receiving multiple scholarships and honors.

Throughout my academic journey, I have delved into core subjects such as machine learning, Monte Carlo simulation, operations research optimization, and big data technologies, building essential skills in financial engineering. My passion for financial markets has been further nurtured through internships at Haitong Securities and Huatai Securities. These experiences honed my market analysis abilities and equipped me to tackle challenges in high-pressure settings, emphasizing effective teamwork.

At Haitong Securities, I spearheaded the development of a multi-asset allocation strategy that incorporated treasury and corporate bonds, adapting to economic cycles. At Huatai Securities, I was involved in strategy development and backtesting using RSRS indicators, and I employed clustering and filtering algorithms like K-Means, DBSCAN, and Kalman to devise successful pair trading strategies.

I am proficient in Python, R, and Matlab and adept at using various financial and statistical analysis tools. My bilingual proficiency in Chinese and English enhances my communication capabilities. I am eager to bring my expertise to your team and explore new opportunities in the field of financial engineering. 



Professional Experience
======
Haitong Securities (2023.02 - 2023.06)
Research Institute, Financial Engineering Intern, Shanghai
·Constructed Global Risk Appetite Cycle Index (GRACI) through Python to identify macroeconomic cycles, analyzed the correlation between equity risk premium, credit risk premium, term premium and economic cycles, and established a strategic asset allocation strategy based on economic cycles
·Integrated inflation indicators to optimize strategies, tested with stock, government bond, corporate bond and bank loan data to build multi-asset and fixed income portfolios, achieving annualized returns of 17.04% and 15.67% with Sharpe ratios of 1.50 and 1.88, respectively
·Monitored the performance of quantitative stock portfolios and various stock selection factors, writing 8 weekly reports on fund performance and factor analysis


Huatai Securities (2022.06 – 2023.01)
Huatai Innovation Investment Co., Ltd, Equity Investment Intern, Beijing
·Participated in front-end research and due diligence for projects related to corporate financial services, conducted company research and product experience on more than 20 companies, conducted management and user interviews for three selected teams to support investment decisions
·Assisted in analyzing target companies' financial data and in the selection process, applied P-MAU and DCF models for valuation
·Utilized Python crawler to scrape investment data and compile daily reports, analyzed capital market financing trends and industrial policies, helped complete three research reports, and assisted in organizing three technology expert interviews, producing two reports in areas including blockchain finance and cloud computing


Huatai Securities (2021.06 – 2021.10)
Equity Investment Department, Equity Quantitative Strategy Intern, Nanjing
·Developed Resistance Support Relative Strength (RSRS) indicator with the slope standard score of a bilinear regression model using Python, optimizing the timing strategy by using the CSI 300 Index and the CSI 500 Index for parameter optimization
·Improved the RSRS timing strategy by incorporating the judgment of historical market price trends into the strategy to avoid building positions during market downtrends
·Drew net asset value charts for different parameter RSRS strategies, utilized grid search to find the best parameters for high-frequency trading, and conducted back testing with 5-minute data, achieving an annualized return rate of 24.54%, a Sharpe ratio of 1.76, and an annual excess return rate of 10.45%


Fuju Investment and Consulting Co., Ltd (2020.06 – 2020.09)
Strategy Research Department, Quantitative Strategy Intern, Shanghai
·Collect and process the fundamental factor data of the constituents of the CSI 800 Index, use the PCA algorithm to reduce the dimensionality of stock features, and identify stock correlations through K-Means clustering and the DBSCAN algorithm.
·Use the Ornstein-Uhlenbeck process to calculate price differentials and model stock relationships, conducting ADF tests on each cluster to find cointegrated stock pairs.
·Establish a LASSO regression model using the Kalman filter to predict the stock portfolio spread, build a pair trading strategy, and achieve an annualized excess return of 6.37%, a Sharpe ratio of 1.19, and a Sortino ratio of 1.72.


Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

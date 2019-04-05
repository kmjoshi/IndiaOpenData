## India Open Data

When I moved to India (Jan '19) I wanted to make a catalogue of _all_ open data sources, and folks working on cool, effective data-viz. Since then I learned about DataMeet and many of the links posted below. 

So here is a list of few useful links and notes, hope it is helpful!
Feel free to suggest additions to list (fork, PR etc.)

### The beginning
[National Data Sharing and Accesibility Policy](http://www.dst.gov.in/national-data-sharing-and-accessibility-policy-0)

### Data sources [[analyticsindiamag](https://www.analyticsindiamag.com/top-10-indian-government-datasets-that-you-can-use-for-analytics-projects/)]    [[datameet](http://datameet.org/wiki/catalog)]
- [RBI database of Indian Economy](https://dbie.rbi.org.in/DBIE/dbie.rbi?site=home)
- [Ministry of Statistics and Programme Implementation Dataset](http://mospi.nic.in/data) (large-scale sample surveys)
- Gateway to Indian Earth Observation (ISRO satellite data)
- National Portal of India (database of govt. services)
- Survey of India (geospatial data)
- India Weather Data
- Aadhaar Metadata
- Import Exports Datasets
- [Open Government Data (OGD) Platform India | data.gov.in](https://data.gov.in/)
    - [wiki](https://en.wikipedia.org/wiki/Data.gov.in)
    - [basic info](http://meity.gov.in/open-data)
    - Built on [Open Government Platform](https://github.com/opengovplatform/opengovplatform-beta) ?? Last commit was in 2013
- Wildlife Institute of India 
- Lots more [data](https://guides.library.columbia.edu/sasia-india/data
) sources curated by library of Columbia: 
- Public Data on all countries by [knoema](https://knoema.com/atlas/India)
- India Water Portal [data](https://www.indiawaterportal.org/data)


### DataViz
- Datameet founder thejesh's spinoff: http://opencity.in/
- IIT Bombay's Information Design Lab: http://info-design-lab.github.io/
- [HowIndiaLives](https://howindialives.com)
- [Jaano India](https://jaanoindia.swaniti.org): Constituency level data on a number of metrics
- Data Journalism (more numbers less visualization)
    - [IndiaSpend](https://indiaspend.com): | [factchecker](https://factchecker.in)
    - [livemint](https://livemint.com)
- [Factly](https://factly.in)
- [India Night Lights](http://india.nightlights.io/#/nation/2007/12): satellite data of Indian villages at night from 1993-2013, a proxy for electrification

### Nifty tools
- [Cheat Sheet](./Franconeri_ExperCeptionDotNet_ChartChooser.pdf) on which charts to use/when
- Great slider: https://refreshless.com/nouislider/

### Open Data Questions
- Who are the stakeholders of data-viz created from open-data? People who are data-literate and with access to large viewing screens? How to make data visualizations available to ```everyone?```
- ...

### All things air pollution
- [UrbanEmissions](urbanemmissions.info) is all and everything you need for air pollution in India | [@UrbanEmissions](https://twitter.com/UrbanEmissions)
    - Monitoring, health effects, forecasting etc.
- How to personally deal with air pollution [source](https://www.firstpost.com/tech/news-analysis/delhi-air-pollution-six-smart-ways-to-deal-with-bad-air-in-your-city-and-home-5480791.html)
    - outdoor pollution sensor
    - mask
    - air purifier
    - exercise indoors
- mapping of air pollution:
    - https://aqicn.org/city/india/up/noida/sector-125/#s:7024
    - https://en.wikipedia.org/wiki/Air_pollution_in_Delhi#cite_note-Monitoring_Stations-34
    - http://safar.tropmet.res.in/
    - https://www.airvisual.com/
        - AirVisual uses US AQI algo, different ranges than Indian AQI
    - http://cpcb.nic.in/
        - https://app.cpcbccr.com/ccr/#/caaqm-dashboard-all/caaqm-landing/caaqm-data-availability
    - global AQI: https://openaq.org/#/map?_k=f5qyta
        - https://github.com/openaq/openaq-api
        - have a python wrapper for delhi pollution
        - https://medium.com/@openaq/why-looking-beyond-air-quality-index-values-matters-d903bf773e1
- Simple viz that makes the case: https://graphics.reuters.com/INDIA-POLLUTION/01008173281/index.html
- solutions:
    - https://timesofindia.indiatimes.com/india/pan-india-clean-air-programme-set-to-roll-out-with-rs-300-crore-initial-support-and-a-mid-term-target/articleshow/67246741.cms
- health effects of pollution: 
    - [mortality in india](https://agupubs.onlinelibrary.wiley.com/doi/full/10.1002/2016GL068949)
    - [general epidemiology](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4740125/)
- https://smartairfilters.com/en/knowledge-base/
- https://scroll.in/pulse/909340/indias-environment-ministry-once-again-downplays-the-effects-of-air-pollution-on-human-health
    - https://twitter.com/CareForAirIndia/
- [Other air toxins](https://timesofindia.indiatimes.com/city/delhi/delhi-air-rich-in-3-toxins-that-can-cause-brain-damage-study/articleshow/67579984.cms)
    - Lung Care Foundation seems sketch?
- [WHO general advisory](https://www.who.int/news-room/fact-sheets/detail/ambient-(outdoor)-air-quality-and-health?fbclid=IwAR16qHodpLTeOCBZ2nd6QkVOyocq-Li8MDKXOa22mrFvwRSsgzOAn9fNEmM)
- Other important Twitterati to follow:
    - [@rsutaria](https://twitter.com/rsutaria)
    - [@pallavipnt](https://twitter.com/pallavipnt)

<!-- ### AI/ML evangelism
    - Data is your friend
    - AI is a buzzword and will always have funding! Cite McKinsey and other reports on state of AI funding
    - Do you want to forecast anything you want?
        - then collect the right data
        - and ask the right questions
    - Human capital | social capital | and .... Data capital
        - start collecting data now 
    - Easy ML workflow
        - good data collection
        - ensuring data integrity
        - hiring a data guy
        - asking the right questions
        - creating views mini DBs that can facilitate insight discovery
        - hiring a analyst
        - plugging into easy-to-use ML models
            - tensorflow | scikit-learn | keras
            - easy-to-use parameter tuner | auto-ml
    - primer by data.world and @dataliteracycom
        - https://datapractices.org/courseware/
        - on all aspects of a data organization

### But AI is also bad
Every functional superhuman AI model is powered by tons of data generated by unpaid, or at most woefully underpaid human labour. Any domain which relies on human expert identification will have flawed AI models, with a trail of human labour that has been cheated. I am not aware of any proposed regulatory frameworks that aim to curb this. But as they say ```All models are wrong but some are useful```. Let us see how use we can make of these. -->


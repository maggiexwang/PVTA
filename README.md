# On the Wrong Side of the River?
An Analysis of Smith College and the Five College Consortium.

Final project for [Data Journalism](http://www.science.smith.edu/~amcnamara/sds236/) (SDS236, Fall 2018) with Natalia Kreciglowa, Margaret Perry, and Maggie Wang.

For Smith College, the Five College Consortium is a big sell to prospective students: what this small liberal arts institution lacks in size, it makes up with a network of over 30,000 undergraduate students in UMass Amherst, Amherst College, Mount Holyoke College, and Hampshire College, along with free bus service between the colleges that comes with a Five College student ID. The Consortium website proudly advertises this free service run by the PVTA as a way to incentivize students into participating in the Five College community and into taking courses off-campus. Yet this mode of transit has its drawbacks: scheduling inconveniences and long commutes, issues that are especially present for buses connecting Smith to the other four campuses across the Connecticut River. A comparison between the mobility among different colleges reveals that while these inconveniences are not disabling to connectivity between the institutions, they can cause time management difficulties for students when it comes to planning for off-campus classes and other activities.

## Findings in Graphs

* The number of incoming Five College cross-registering guest students differs between campuses, so does the students willingness to take classes off-campus. Patters are evidenced in the two gifs below, with PVTA routes marked in dark blue in the first gif. Our analysis, backed by interviews of students across the Five Colleges, show that despite most students take classes off-campus out of necessity and are generally satisfied with their off-campus academic experiences, geographical proximity also serves as a determining factor for which classes or which campuses students choose to take. Taking classes at Smith College, for this latter reason, is usually more costly for guest students' schedules for the longer commute across the Charles River.  

![graph1](https://github.com/wxiaonanw/PVTA/blob/master/graphs-collab/graph1.gif)

![graph2](https://github.com/wxiaonanw/PVTA/blob/master/graphs-collab/graph2.gif)

* PVTA services is therefore crucial to most students exchanging to and from Smith College. Among the buslines, the B43 and the B39 connect Smith with the other four colleges. Yet the commute, which can take anywhere between 30 to over 60 minutes, is much longer, especially compared to the B38 that connects Mount Holyoke, Hampshire, Amherst, and UMass with less than 20-minute rides between the latter three colleges.   

* At the same time, the PVTA buslines owe the majority of its ridership to Five College students. As demonstrated in the graphics below, the stops directly or closely affiliated with the Five Colleges are those that are the busiest. In fact, the ridership data of these buslines is rather representative of the distribution of students attending classes across the institutions. For these reasons, we conclude that the PVTA service changes have great effects on both the Five College student body and on its own services.  

![graph3](https://github.com/wxiaonanw/PVTA/blob/master/graphs-collab/graph3.png)

For the complete write-out, please download and read [fivecollege.html](https://github.com/wxiaonanw/PVTA/blob/master/fivecollege.html), or refer to the source code file [fivecollege.Rmd](https://github.com/wxiaonanw/PVTA/blob/master/fivecollege.Rmd).


## Sources

Raw data files can be found in [data-raw](https://github.com/wxiaonanw/PVTA/tree/master/data-raw). Please see [data-cleaned](https://github.com/wxiaonanw/PVTA/tree/master/data-cleaned) with manually cleaned data that the source code file refers to. Paths to files in the source code file may be different.

We would like to thank the registrar offices of the colleges as well as the Five College Consortium for the exchange data, along with special thanks to Krystal Oldread, Director of Operations & Planning of the Pioneer Valley Transit Authority, for her support in pulling the ridership data.

* Five College Exchange Numbers and Enrollment Totals: University of Massachusetts Fact Book, Smith College Registrar, Five College Consortium website, and websites of each of the colleges.

* PVTA Ridership Data: initial data request put through the [PVTA Records Request website](http://www.pvta.com/publicRecords.php). 

* PVTA route data: [MassDOT Open Data Portal](https://geo-massdot.opendata.arcgis.com/datasets/pvta-routes?selectedAttribute=BUS_), Massachusetts Department of Transportation. 

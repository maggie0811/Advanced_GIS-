| [home page](https://maggie0811.github.io/Advanced_GIS-/) | [Homework 1](hw1) | [Homework 2](hw2) | [Felt Demo](felt_demo) | [Final Project](final_project)

# Final Project: Analysis of Bridge Infrastructure in Pennsylvania

American infrastructure is aging rapidly, especially bridges. In order to maintain and upkeep these structures, states must be sure to successfully track the conditions of their bridges. Additionally, it is important for jurisdictions within states to be aware of funding sources to repair these bridges, especially new revenue streams from the Bipartisan Infrastructure Law. In total, Pennsylvania has 713 bridges older than 50 years old and rated as being in poor condition. The full dataset of bridge with condition information can be found [here](https://www.pasda.psu.edu/uci/DataSummary.aspx?dataset=35)

The following ArcGIS insights page will help people involved with bridge repair across the state understand areas in the state with high need across a variety of categories.

<iframe src="https://insights.arcgis.com/#/embed/761cd3ea49094a0b83347da4f7acb339" width="1500" height="1300" frameborder="0"></iframe>

The above visualizations can be used primarily for understaning which counties or areas of Pennsylvania have a need for bridge repairs, or targeted funding. The **Pennsylvania Bridges 50+ Years Old and Poor Condition** card can be used to understand which areas have a high density of aging bridges. Not surprisingly, these tended to be areas with higher populations and urban areas. The calculate density tool in Insights was used to create this card.

Next, the **Counties with Most Aging Bridges in Poor Condition** card can be used to see which counties have bridges that are specifically rated as being in poor condition. Clearfield and Centre County were at the top of the list, likely because they have population centers but also might not have the funding sources that can be found in areas with larger cities. 

**Location of Bridges with Poor Condition Rating** simply shows the location of each bridge as detailed in the other cards.

**Counties with High Rates of Aging Bridges per Capita** uses a spatial aggregation of aging brigdes in each county, then enriches the data with population information. This population information is then used to find out which counties have the most aging bridges per capita. Again, these areas are largely clustered around the middle of the state.

**Areas with High Density of Poor Bridges & Low Income Communities** aggregates the bridge density map and low income communities dataset to discover areas which are both low income and have a high density of low quality bridges. This information can be used to equitably target bridge improvement projects.

Finally, **Bridges with High Average Daily Traffic in Poor Condition** symbolizes the bridge points based on the average daily traffic field associated with them. High useage is another factor that may prioritize a brdige for repair over another, so understanding where these sorts of bridges are will be useful for planners.

Once a bridge has been identified as in high need of funding for repairs, then an applicable funding source should be identified. THe state of Pennsylvania generally has limited funds due to a variety of factors. For one, the sheer number of aging bridges in the state makes it difficult to keep up with maintenance and repairs. Additionally, fund sources such as tolls have been fought by local municipalities, making them difficult to implement. 

The Pennsylvania Department of Transportation (PennDOT) has proposed a [variety of ways](https://www.penndot.pa.gov/about-us/funding/solutions/Pages/default.aspx) to supplement fund sources, including tolls, mileage based user fees, congestion pricing, corridor tolling and additonal fees ant taxes.

In addition to proposed funding sources, there are a number of current sources, both federal and state-specific that interested parties can utilize. 

| Name | Jurisdiction | Description | Link |
-------|--------------|-------------|------|
|(MBP3) Major Bridge Public-Private Partnership |	Statewide |	Basically a bridge tolling program, the Major Bridge Public-Private Partnership (MBP3) was established to accelerate the replacement and rehabilitation of major Interstate bridges. | [link](https://www.penndot.pa.gov/about-us/funding/solutions/MBP3I/Pages/default.aspx) |
|(BIL) Infrastructure Bill Formula Funds | Statewide	| 5 Year Bridge Formula Program Funding totals $1.8B for the state | [link](https://usdot.maps.arcgis.com/apps/dashboards/59b9b3d2fe9640f5bc54660342435655) |
|PA Municipal Bridge Retro-Reimbursement Program |	Bucks, Chester, Delaware, and Montgomery counties |	State bridge funds of the PA Transportation Improvement Program (TIP) are available for selected municipal bridge projects with existing deck spans of 20 feet (20') in length or greater. | [link](https://www.dvrpc.org/mbrp/) |
|(STBP) Surface transportation block program	| Statewide |	Provides flexible funding that may be used by States and localities for projects to preserve and improve the conditions and performance on any Federal-aid highway, bridge and tunnel projects on any public road, pedestrian and bicycle infrastructure, and transit capital projects, including intercity bus terminals.	| [link](https://www.fhwa.dot.gov/specialfunding/stp/) |
|(TIP) Transportation Improvement Program funds |	Lawrence, Butler, Armstrong, Indiana, Beaver, Allegheny, Westmoreland, Washington, Greene, and Fayette	counties | Candidate bridge projects are evaluated utilizing bridge asset management systems that consider current bridge conditions and recommended treatment options	| [link](https://www.spcregion.org/wp-content/uploads/2020/03/Local-Bridge-Funding-Guidebook.pdf)|
|(TIP) Transportation Improvement Program funds | Centre County	| Same as other TIP funding but for Centre County area |	[link](https://www.crcog.net/index.asp?SEC=8DCFD95E-8D77-40B0-BA32-D804BEFC3CDE) |
|(BIP) Bridge Investment Program |	Nationwide |	Discretionary grant funding available on a competitive basis | [link](https://www.fhwa.dot.gov/bipartisan-infrastructure-law/bip_factsheet.cfm) |
|Bridge Off the Federal-Aid System Program Funds |	Nationwide	| Federal funding to bridges that are located off the Federal-Aid Network and meeting the National Bridge Inventory (NBI) Length Criterion of 20 feet. |	[link](https://www.fhwa.dot.gov/specialfunding/stp/160307.cfm#g) |
|Historic Metal Truss Bridge Capital Rehabilitation Program	| Statewide, must be historic bridges |	The Program is primarily focused on county and municipally owned historic metal truss bridges where owners desire to work collaboratively with PennDOT, MPO/RPOs, the SHPO and historic preservation interest groups and individuals to rehabilitate their resources for continuous vehicular transportation use.	| [link](https://www.penndot.pa.gov/ProjectAndPrograms/Cultural%20Resources/Pages/Historic%20Truss%20Bridge%20Management%20Plan.aspx) |


## [Link to Final Project Materials](https://drive.google.com/drive/folders/1L-ka7KU71LFKjJFcZ8-pPuHAZXaiHJ2T?usp=sharing)








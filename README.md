# Mind Health Network(Team Kalolo): ECCE App Challenge 2018

![Mental Health Logo](brandinglogo.png)

**Team Members**: 
---
* Alice Naphtali 
* Cinye Li
* Kevin Chau
* Alexandar Ristic

**Our team name is derived from the Hawaiian word for brain.**

## Accessing resources:
* Click [here](https://mcmaster.maps.arcgis.com/apps/webappviewer/index.html?id=bed0783fe480486eb928bfa6f2ed9366) for the application.
* Click [here](https://www.youtube.com/watch?v=wn_w3Duw07k&feature=youtu.be) for a video demonstration.
* Click [here](https://drive.google.com/drive/folders/1Rc_ykU-xArIh4TP_mc1Rl8S7Vb9oLP69) to download associated files for this project.

## Mind Health Network App
## Team Kalolo | ESRI 2018 ECCE App Challenge

**Mission Statement**

Mental illness is exceptionally common in Canada, with 1 in 5 Canadians experiencing a mental issue every year <sup>1</sup>. Such illnesses predominantly affect adolescents between 15-24, with about a quarter of such individuals taking their own lives <sup>2</sup>. In the majority of such cases, assistance from health professionals and community-based services can have profound benefits on mental wellbeing,yet roughly 75% of the individuals affected have not visited such services <sup>3</sup>. This is principally due to the confusing nature of mental health services available to individuals in Ontario, with many unsure where to begin searching for help, where to go for a particular type of problem, and what types of services are available to them. 

Thus, it is of paramount importance to simplify the process of seeking and receiving mental health support. By providing a free and open service that informs members of the public, especially vulnerable youths, of local mental health services in an accessible and intuitive manner, we can help build effective support networks for those in need. However;as it stands, there is no centralized platform that provides such information. Furthermore, there are no existing services that categorize a given facility by urgency of the demand (e.g simply seeking information or requiring urgent care) or provide valuable and consistent feedback on the performance of facilities, facility staff, and overall patient satisfaction of the treatments received.

Our application seeks to satisfy these needs by alleviating the burdens of untreated mental illnesses. The Mind Health Network provides the public a centralized means of locating mental health services in close proximity to the downtown Toronto core, as well as organizing such locations by urgency. Furthermore, we allow users to rate the quality of their experiences with a particular service utilizing a short, 12 question Survey123 form embedded in our application. We hope that this "proof of concept" application can be scaled to the provincial level, and even the national level in the future, to extend our platform and mission for a more integrated system of mental health support.

**Our Goals**

The Mind Health Network app strives to connect the citizens of central Toronto to the medical and mental health establishments that best suit their needs, when and where they need them. Towards this end, the three main objectives we hope to fulfill are:
 
1.) To improve awareness and promote public education of existing types of mental health facilities, professionals, and services in central Toronto, depending on the urgency level of their mental health condition(s);
 
2.) To connect Torontonians to an extensive network of available mental health professionals and services in the downtown core of the city (encompassing 8 adjacent wards);
 
3.) To provides users with an anonymous platform to inform one another of the quality of a given healthcare service through the completion of a 12-question, 123 Survey.

---
**Using the Mind Health Network App**

Preamble

  As alluded to earlier,  our app aims to easily inform central Toronto residents of nearby mental health facilities. To facilitate this goal, we have crafted an easy, clear, and intuitive user interface powered by ESRI's Web AppBuilder. We chose this platform as it leverages responsive web design and widget functionality to allow users to easily find the services they are looking for alongside all relevant information by the selected urgency of their mental health needs or by providing their location. Using our app, users can find relevant information in 2 minutes or less, dramtically expediating their process towards receiving the care they need. 


---
# Steps to Use the App

## Accessing the App and Widget Details

* View the live web app by clicking on the following the link: https://arcg.is/1ubq55 
* View a video demoing how to work with the app here: https://www.youtube.com/watch?v=wn_w3Duw07k&feature=youtu.be

## About and How-To Widget Documentation

When users first open the Mind Health Network app, they will be greeted by a message box that will inform them to seek immediate help in the event of a personal crisis and an unfurled About widget panel on the right. Users may scroll down the panel to read more about the urgency level parameters and specific definitions used to group facilities in each category. 

  The About widget panel will also include a link to the optional 12 question 123 Survey at the end, which helps to gauge community comments on the quality of mental health services used. There is also another link to the completely confidential and anonymous results of the community-collected information on said mental health services to provide future reference for interested patients or medical providers. If the user is still confused or wants further detail about widget functionality, they can click on the How-To widget located, which is located next to the About widget. Here, they will be provided with a detailed breakdown of the functionality of each of the widgets they can use.

## Search for Mental Health Services by Urgency Level

With the search widget, users can filter the service they’re looking for by urgency level (Need Help, Need Support, Need Information), the type of service (e.g. Pharmacy, Community Centre etc.) and available days with the provided dropdowns. After submitting their search criteria, the interactive results pane will display a list of relevant locations that meet users’ requirements, and allow users to zoom in and view detailed information on a location-by-location basis.

## Search for Mental Health Services Near You

Using a modified version of the Near Me widget, users can find locations within a specified radius (1-5 kilometers) of their current location. Users can edit such distances as they desire using an interactive slider and then see a drop-down of all the locations that meet the specified distance criteria.

## Find Directions to Your Chosen Mental Health Facility

Using the directions, or Where To widget, a user can specify an origin and destination for a trip, such as to a mental health service, a mode of transportation (car or walking), and time or distance impedance parameters to create a shortest route path between these two points. As well, users have the option to insert waypoints with the add dialog to factor in brief stops towards their final destination. 

## Navigating the Mental Facilities Layers and Sharing!

If a user desires to look at all available, top-rated mental health facilities in central Toronto, they may click on the Layer List widget and toggle on and off different types of mental health services available in the region. Users may also look to the Legend widget so that they are able to distinguish between the different types of mental health providers, facilities, and services

---

# Attributions

## Data Sources

The Mind Health Network relies on only free and open data sources that are available online for public use, such as:

* www.ementalhealth.ca
* www.ratemd.com
* www.torontocentralhealthline.ca
* www.yelp.ca/toronto
* www.yellowpages.ca/search/si/1/Telephone+Directories/Toronto+ON
* www.ontario.ca/search/data-catalogue
* www.toronto.ca/city-government/data-research-maps/open-data/
* www.211toronto.ca

As an additional side note, the primary sources of information on pharmacies and other healthcare facilities, such as emergency departments and crisis centres, were taken from the City of Toronto and Province of Ontario’s open databases, as listed above. However, additional information on the top-rated psychologists, therapists, psychiatrists, family doctors, community groups were based off of free, community resources. The above resources were geocoded using ArcGIS Pro and ESRI's world geocoder. 


## Video Development

PACIFIC SUN by Nicolai Heidlas Music https://soundcloud.com/nicolai-heidlas Creative Commons — Attribution 3.0 Unported— CC BY 3.0 

Music promoted by Audio Library https://youtu.be/kbqmEJTr3nU

## Limitations

* Due to an open data constraint and irregular update schedules, data is current only upto 2016.
* The data only cover 8 central Toronto wards and thus does not fully represent all services in the city.
* The 123 Survey is provided as an optional service with its usefulness varying due to subjective experiences. 

## References

1.  Smetanin et al. (2011). [The life and economic impact of major mental illnesses in Canada: 2011-2041](https://www.mentalhealthcommission.ca/sites/default/files/MHCC_Report_Base_Case_FINAL_ENG_0_0.pdf). Prepared for the Mental Health Commission of Canada. Toronto: RiskAnalytica. 

2.  Pearson, Janz and Ali (2013). [Health at a glance: Mental and substance use disorders in Canada](https://www150.statcan.gc.ca/n1/en/pub/82-624-x/2013001/article/11855-eng.pdf?st=bXtDfKvV). Statistics Canada Catalogue no. 82-624-X.

3.  Waddell et al. (2005). [A public health strategy to improve the mental health of Canadian children](https://journals.sagepub.com/doi/pdf/10.1177/070674370505000406). Canadian Journal of Psychiatry, 50: 226-33.


# UFOs
Are we alone in the universe? This exciting question has intrigued folks for centuries and across cultures. Whether or not you believe, it is true that a very large amount of people have claimed to have observed unidentified crafts in the skies... the concept is equally thrilling and terrifying to think about. 
## Purpose
The purpose of this body of work is to create a webpage that will interact with a database containing details of several UFO sightings. The page initially displays the entirety of the data set in an easy-to-read table which lists the parameters of each siting. The page also allows a user to filter the data based upon one or  more of the criteria included in the set (date of siting, city, state, country and shape of the UFO). Thus, the page allows a user to draw conclusions based upon the data set according to their desired set of filters. For example, someone may want to look up sightings on a specific day, or of a certain shape, and would be able to do so much more efficiently using our tool as opposed to simply scanning the data set. An image of the page is shown below in Figure 1.

![alt text](https://github.com/aamotz001/UFOs/blob/main/figures/fig1.png)
__Figure 1: Image of HTML Page__

## Instructions for Search
The data base search is designed to be straightforward for the user. There are five windows corresponding to different types of filters (city, state, country, date and shape) and the user simply enters one or more of the desired parameters by which to filter the database results. An example is shown below in Figure 2.

![alt text](https://github.com/aamotz001/UFOs/blob/main/figures/fig2a.png)
__Figure 2: Database Filter Input Set__

As an example, here is the data base when searched by a single parameter (city). As can be seen below in Figure 3, an input of the name "Bonita" to the city parameter returns exactly one result. 


![alt text](https://github.com/aamotz001/UFOs/blob/main/figures/fig2b.png)
__Figure 3: Filter by City__

For a more advanced search, the user may alternately include multiple filters. An example of this is shown below in Figure 4, where the user has specified both the city (El Cajon) and UFO shape (light). 

![alt text](https://github.com/aamotz001/UFOs/blob/main/figures/fig3.png)
__Figure 4: Multiple Filters__

## Summary

In summary, the tool we have created provides a convenient shortcut around searching through a bulky database, providing a user a straightforward way to quickly obtain specific information. The page is also aesthetically pleasing, with a theme to match the topic of the database. 

### Drawbacks

Despite the clear advantages of being able to filter the database, there are some drawbacks to the tool which has been created. First, one major drawback is that the applied filter must be an exact match to an entry in the database in order to obtain a result, as shown below in Figure 5.


![alt text](https://github.com/aamotz001/UFOs/blob/main/figures/fig4.png)
__Figure 5: Drawback: Null Result__

Another clear drawback is that the filter by date is very restrictive. For example, the user is not able to search by a given year, or range of dates. Having the filter only return a result on a specific date is ultimately not as useful as it could be if the parameter space were more general. 

![alt text](https://github.com/aamotz001/UFOs/blob/main/figures/fig5.png)
__Figure 6: Drawback: Date Specificity__

### Future Suggestions

In future iterations of this tool, it would be better to expand the capability of the filtering process. For example, one could enter a radius of interest about a specific location, and return results fitting within that area. Another suggested capability would be to search by a given year, or within a range of dates. Adding this could be straightforward given the architecture already in place.

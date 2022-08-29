# Case-1---Cyclistic (Last Update : 2022-08-29)

Welcome to my Case Study about Cyclistic (with Divvy's Dataset) 
the impressions that i have and the conclutions that I have made.

I'll add all the code and the process that I made, you are more than welcome to ask questions and to use chuncks of the code (will appreciate a mention or a high five on linkedin if you do)

As I am trying to get strain to other case studies I will update this readme and repository as I go so just look at the latest update date on the top of this readme.


# My takeaways from the project.
If you want my main takeaways from this project as I know each one of us try to bring his or hers unique perspective.


## If you have any un-knowenes - contact the data provider.
I E-mailed Divvy with the E-mail supplied in their company's website about all the questions I had about the Dataset.
did you know that "Docked_bike" and "Classic_bike" under Rideable_type - are the same ? 

unfortunatly I couldn't get a catalog number for each user as privecy restrictions prevent.
but let me leave you with a question only the company can answer, 
look at your ggplot of number of uses per day per type of user.
lets take the weekend where the uses are almost identicle per hour of the day.
how do I know if 100 members use Divvy's bike as a Uber-eats \ grub hub transportation... basically giving a single user get 10's of rides per day so 100 users are in the thousands of rides per day, while the casual users are just a single ride per day per user.
why does it matter you ask ?
Marketing's main goal is to increase revenue by converting casual user into a member, in the case I just described, 100 casual single ride users create 2 times the revenue a day then 100 users a year.
It is an importand detail I would have liked to know.

my third takeaway is also good for anyone who analyze businesses.
in this case I removed all the data the is not interquartile range a function a happly learned on codecademy.com
in short it take around 25% lower cases and 25% upper cases (uses per station \ per distance... ) and gives you the main uses in the center of the Gauss Bell
why ?
example : 
Lets take use per station, we have no need to persue clients that use the stations once a year, they are not the targeted crowd for marketing, they use this station 1000 times a year (irrelevant to 5.9 Mill uses a year)
but at the same time, the people that uses the 25% busiest stations, the are not a target for the marketing team as well... why ? they already use the stations, marketing or not ... (casual users even vreate a higher revenue per year just by not commiting to a membership) let them be, vonverting them will cause damage to the company.
but the venter of our dataset is the goal we need to focus on.
***** Important - it is not an accurate 25% as every Gauss Bell is different. use function IQR() to aggragate the numbers.

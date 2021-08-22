## Presentation link: https://docs.google.com/presentation/d/1sm7wlc8bZVtYHaXsrnpew_1lfN20yCyRBYqpo1Z_wH4/1
## Tableau link:  https://public.tableau.com/app/profile/anthony.amp/viz/TheFishingProject/PeakDB_1

# Self-Assessment

*Presents a cohesive written analysis that describes the role(s) they played over the course of the project and their contribution to the project in that role.*

Originally, our team consisted of five members.  Four were active participants in the final project, and while the module outlined the rotation of duties, each member of our team found themselves specializing in certain kinds of tasks.  I started in the circle role, and while I kept that role throughout the project, my particular area of focus was our database.  Throughout the last six months, I've found my greatest strength to be big data management in the Python programming language and its associated libraries.  I love Python--it has changed the way I work and think--and I put myself forward early on to handle "all things data."  While the team selected our subject cooperatively, individually I: 1) performed troubleshooting on the original dataset, 2) assembled a comprehensive working dataframe, 3) cleaned and processed that dataframe, 4) divided it into dependent dataframes containing keys (for graphs and charts) and values (for the machine learning model). 5) sent dataframes to CSV/Github for use by other team members, 6) performed exploratory analysis using matplotlib, 7) joined dependent dataframes into a comprehensive database in SQL, and 8) sent the comprehensive database to an S3 bucket for pickup by Amazon Web Services.

*Presents a cohesive written summary of how they contributed to each of the roles they did not take on via team discussions, peer reviews, or other means.*

Our team was incredibly supportive of each other, and I hope I gave as much energy and enthusiasm as I got, which was plenty.  We had fascinating discussions around this dataset, some of which wandered off into the (always informative) weeds.  I certainly hope I helped my teammates as much as they supported me, and I'd say my main contributions to each of them were as follows.  To support the team member handling the machine learning portion, I processed and cleaned the dataset extensively, cutting it down based on a variety of factors, filtering out unhelpful variables and columns, passing values and keys between each other as needed.  I provided the comprehensive database and its component datasets in multiple formats and via multiple platforms, and attempted to make data "machine ready" by the time it passed to him.  For the team member handling Tableau, I performed exploratory analysis of the data in our .ipynb files, in the hopes of giving him at lease a few starting directions for the dashboard and final visualizations.  Following initial exploratory analysis, I did final cleaning and made add'l dataframes to support easy feeding of data into Tableau.  For the team member handling Github, I helped in the creation of new branches, summarizing/describing my work for translation into the project README, and troubleshooting code.

*Additionally, the analysis should describe their greatest personal challenge over the course of the project, and how they overcame that challenge.*

I’m happy to report that this project went incredibly smoothly for me.  For the sake of this question, I wish a great personal challenge would come to mind, but I did not encounter a significant one.  There were modules that I found significantly more difficult than the final project.  If I had to identify one challenge, however, I’d say that simply working in a group—and working so incredibly well, in the end—was a challenge for me.  I’m a lone wolf at heart, and my standards can be incredibly high.  My team members and I were also necessarily at different skill levels with regard to what we’ve covered over the last six months.  In the beginning of the project, I had high aspirations—my team members talked me down to more manageable goals when I started to branch in too many directions, and I think that very much challenges: 1) my desire for control of the ultimate product, and 2) my perfectionist tendencies.  Hardest for me—letting go and trusting these people to pull their weight.  They came through in spades.  I was perpetually impressed with their commitment, their work ethic, their enthusiasm, and the deliverables they produced.  Working with a group like this required a “lean in” from me—in the end, this group project was a highlight of this entire experience.

# Team Assessment

*Presents a cohesive written analysis that describes their teamwork, including all of the following:*

*Their communication protocol, including any challenges, how they were resolved, and what they would do differently next time*

My team communicated regularly and incredibly well.  We used our in-class time primarily to hash out new directions and everyone’s “assignments” and due dates.  After we’d all gone off to work in our “separate corners,” we’d come back with our individual products and edit together toward the next drafts and toward ultimate cohesion.  We leaned heavily on Slack, sharing files, code, articles, miscellany, encouragement, and personal roadblocks as we worked through this project.  My only regret—and it’s not one that could have been ameliorated given this timeline—is that we didn’t have more time to get to know each other before selecting our topic.  About halfway thru our workflow, we found some interesting and unusual shared interests between us, and if I could work with these three people again, we would address a stranger and more offbeat topic.  That said, I can’t think of one significant problem any single one of us presented that the others couldn’t and didn’t help solve.

*Their strengths as a team, including tips and tricks they would want to share with a new cohort kicking off the project*

My team’s greatest strength was our personal chemistry.  I messaged Raina prior to group work and told her what I thought my strengths were, and her team selections seemed intentional and well-made.  My two primary pieces of advice to a future cohort are as follows: 1) when you find a niche and an area of specialty, take it for your team and RUN, and become the “go-to” expert in at least one topic for your team, and 2) take at least one entire working meeting (maybe two?) and simply chat with each other before choosing a dataset.  Loved my team, loved my topic—but if we’d had some of the discussions we had in the middle of the project earlier on, we’d have chosen a much different topic and, although we were quite enthusiastic about this one, we’d have been even more so about something more unusual.

# Summary of Project

*Presents a cohesive, three- to four-sentence summary of the project that could be used on a LinkedIn profile, in an interview or cover letter, or as an elevator pitch, including all of the following:*

*Topic addressed*

We aim to answer the following question: when you’re planning a fishing trip, how do you maximize your catch and, more importantly, get the biggest bang for your buck when it comes to renting a charter fishing expedition?

*Machine module used*

Using coastal data from NOAA, a balanced random forest classifier, and a comprehensive primary component analysis, we conclude that you absolutely can increase your take by planning your trip at the right time of year, the right time of day, using the right tackle in the right location.  Furthermore, our model is not only 83% accurate in predicting your catch, we address a question that cultures have been mythmaking about for millennia:  are sea turtles good luck for the angler, and if so (or if not), what’s the material statistical impact of this superstition?

*Results of the analysis*

Turns out that you’re lucky either way.  While sighting a live (or dead) sea turtle is incredibly rare (and, therefore, something to write home about), not sighting one at all leads to more fish per angler—more than a silver lining on a fishing trip.  Our other major conclusion was this:  peak catches occur on charter trips of approx. 4 hours and approx. 9 hours—so if you don’t want to break the bank, a half-day trip will likely be just as productive as a full day.

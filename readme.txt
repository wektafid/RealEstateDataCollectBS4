From the biggest Hungarian real estate site (ingatlan.com) the data is downloaded with BS4 and formatted in pandas DF for later DataScience purposes
The site is mostly Hungarian, a slight translation is added to the code, like "tégla építésű" wich means "the building is made from bricks" etc
Error handling built in, because some of the ad are out of date in the minute of the code running. 

Because parsing such big ammount of data could cause some problems on the site, sleep timers are added to the code.

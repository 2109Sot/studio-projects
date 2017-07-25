# WHO SAMPLED THE AMEN BREAK BY THE WINSTONS

----------------------

## 07/24

### INSPIRATION: https://www.youtube.com/watch?v=5SaFTm2bcac&t=754s

Scraped whosampled.com (http://www.whosampled.com/The-Winstons/Amen,-Brother/sampled/)
and got my results into a pandas data-frame. The data-frame's columns are:
Artist | Genre | Title | Year.

Because of a rather tricky html formatting of the site, in the beginning my 'Year'
column also contained the artist name. Using '.str.extract(r"(\d\d\d\d)")'
I managed to extract just the year each song was produced. The results are gold, like
hip hop's golden era in early 90s. Interestingly enough, the sample comes back around 2011. In contrast with my initial assumption, though, the 6-seconds drum sample of
'Amen Brother' has been mostly used by 'electronic / dance' music artists, and not so much by hip hop artists. It has been used in many soundtracks too.

Finding the base of each artist would be a good addition to my story, especially
when considering the birthplaces of the two major sub-cultures the Amen Break gave
birth to, that is hip-hop in the States and drum-n-base in Europe (The UK).

Saved my pandas data-frame into a .csv file entitled 'who_sampled_amen_break.csv'

Got my first plots done (1. 'year ditribution, 2. 'Genres', 3. 'Artists that used the sample more than 10 times').

Started working on visualizations in illustrator ('top 30 artists who used the sample more than 10 times')

------------------

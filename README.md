# Movies-ETL
## Extract, Transfrom, Load Movie Data
 ![img](https://github.com/Edgarhv/Movies-ETL/blob/eab556497a8a56b0acc129e61a28c924a9741b02/InsistentComplicatedArrowworm-mobile%20(1).gif)

Source: https://gfycat.com/insistentcomplicatedarrowworm-michael-emerson-jim-caviezel

### Overview

This project aimed to gather movie data from both Wikipedia and kaggle and then create a database that we used to perform our own analysis.Also,I extracted the necessary data from Wikipedia and Kaggle, used python's pandas library to transform the data into a working dataframe, and then loaded it to PostgreSQL for a better purpose.

## Results
![img](movies_query.png)
![img](ratings_query.png)

-After many hours of extract, transform, and load process, I had a database clean. This database contains two tables: one for movies and one for ratings. The movies table consists of 31 columns holding a range of information for 6052 different movies like the image above.

-On the other side, The rating table consists of 5 different columns holding a range of information on over 26 million individual user ratings. Finally, these clean data make it easy if someone wants to do a different analysis.

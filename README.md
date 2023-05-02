# Mid-bootcamp project

**DESCRIPTION:**
TikTok is here to change the way themusic industry delivers new products to the customers.
We were used to having other platforms to stream music to get possible listeners’ attention like series or movies. For example, Kate Bush returns to life with her song appearance on the Netflix series Stranger Things. Because of this, I decided to investigate if the same phenomenon could happen with some unpopular songs already released, so I led my studies on the hypothesis:

**HYPOTESIS**: Could unpopular Spotify songs become TikTok songs? 

- **DATASETS (from kaggle):**
[Tiktok popular songs 2022](https://www.kaggle.com/datasets/sveta151/tiktok-popular-songs-2022) || 
[Unpopular songs Spotify](https://www.kaggle.com/datasets/estienneggx/spotify-unpopular-songs)

- **FINAL VARIABLES USED ON THE MODELS:**
    - **Accousticness -** 0 = less | 1 = more -  acoustic the song is
    - **Energy** **-** 0 = less | 1 = more -  energetic the song is
    - **Instrumentalness** - 0 = lesser likelihood | 1 =  greater likelihood  - the track contains no vocal content.
    - **Key:** the note or chord the music is centered around, the tonic | 0-11
    - **Liveness**: detects the presence of an audience in the recording  | ****< 0.8 weak likelihood | > 0.8  strong likelihood  - that the track is live.
    - **Speechiness**: detects the presence of spoken words in a track | > 0.66 probably made of spoken works,  0.33 - 0.66 may contain both music and words,  < 0.33 does not have any speech
    - **Popularity -** The higher the value the more popular the song is **(the analyzed variable)**

During the process I perfomed some Featrure Extraction, Logistic Regression model and KNN model. 
I also applied a hypotesis testing using both datasets (used t-test). The result of the study are not statistically significant and there is not enough evidence to reject the null hypothesis.  This means that the results of the study are not reliable and may have been obtained due to chance. 

**TABLEAU DASHBOARD**: https://public.tableau.com/views/Mid-bootcampproject_16824462791190/Dashboard3?:language=en-GB&publish=yes&:display_count=n&:origin=viz_share_link

With my study We can tell that If we give a spotify song to this trained model, we can predict with 65% of accuracy if it could become a tiktok song/popular



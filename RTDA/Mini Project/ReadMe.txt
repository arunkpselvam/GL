Dear Participant,

Please find below the Mini Project for Real-Time Data Analytics. Kindly submit your assignment before the deadline.

Sentiment Analysis on Twitter in Real Time -

Problem Summary: On the real time tweets streams data apply Sentiment Analysis to get the opinion & trends on different topics in real time. Also find influential people or POI (person of Interest) from the twitter data.

Analysis to be done on the Twitter streaming data is:  (Take time interval to be 10 seconds.)

Steps to be followed :                                                                

Find Influential people in twitter:
Hint - For simplicity assume the algorithm to find influential person is directly proportional to followers.
Find top 10 Influential personalities from the twitter across the globe. (In an interval of 10 seconds).
 

Get trending Topics in twitter right now:
Find the word from the tweet which is occurring most of the times in the whole tweets corpus.
Top 10 trending topic (In an interval of 10 seconds).
 

Sentiment Analysis:
Filter tweets & take tweets which has mention of “iphone”.
Get sentiments about iphone. (ie. In an interval of 10 seconds) - [positive, negative or neutral]
 

 

Optional (For practice) :

Geo based analysis:
Find the country based tweets count.
Find Top tweeting user:
Find User who is tweeting a lot.
Find top 50 across the world.
Language based analysis:
Find counts of tweets in different languages.
Get top 7 languages in terms of volume.
Most popular tweets:
Most popular tweets means here is the tweet which has been re-tweeted maximum number of times.
Get top 100 most re-tweeted tweets in last 1 hour related to “iphone”.
Plot all above analysis (in bar chart or for Geo analysis heat map). It totally depends on your creativity to get some interesting insights & visualization plots from all above analysis.
 

Hints:

Attaching library to do sentiment analysis: (optional)
from textblob import TextBlob
sentiment_details = TextBlob(tweet_text)
sentiment_polarity = sentiment_details.sentiment.polarity
For plot the graphs & charts, you can use matplotlib.
You can create server in your local machine(cloud lab).
For any doubt, please refer to the code which I had shared in the classroom while showing Live Twitter Demo.
In case of any doubt, please reach out to us.
 

Twitter Fields of json object:

Can access from:  https://dev.twitter.com/overview/api/tweets (Links to an external site.)Links to an external site. (Links to an external site.)Links to an external site.

If you are not able to find anything, Please find below a sample tweet json:

{

            "text": "RT @PostGradProblem: In preparation for the NFL lockout, I will be spending twice as much time analyzing my fantasy baseball team during ...",

            "truncated": true,

            "in_reply_to_user_id": null,

            "in_reply_to_status_id": null,

            "favorited": false,

            "source": "<a href=\"http://twitter.com/\" rel=\"nofollow\">Twitter for iPhone</a>",

            "in_reply_to_screen_name": null,

            "in_reply_to_status_id_str": null,

            "id_str": "54691802283900928",

            "entities": {

            "user_mentions": [

                        {

                        "indices": [

                                    3,

                                    19

                        ],

                        "screen_name": "PostGradProblem",

                            "id_str": "271572434",

                        "name": "PostGradProblems",

                        "id": 271572434

                        }

            ],

            "urls": [ ],

            "hashtags": [ ]

            },

            "contributors": null,

            "retweeted": false,

            "in_reply_to_user_id_str": null,

            "place": null,

            "retweet_count": 4,

            "created_at": "Sun Apr 03 23:48:36 +0000 2011",

            "retweeted_status": {

            "text": "In preparation for the NFL lockout, I will be spending twice as much time analyzing my fantasy baseball team during company time. #PGP",

            "truncated": false,

            "in_reply_to_user_id": null,

            "in_reply_to_status_id": null,

            "favorited": false,

            "source": "<a href=\"http://www.hootsuite.com\" rel=\"nofollow\">HootSuite</a>",

            "in_reply_to_screen_name": null,

            "in_reply_to_status_id_str": null,

            "id_str": "54640519019642881",

            "entities": {

                        "user_mentions": [ ],

                        "urls": [ ],

                        "hashtags": [

                        {

                                    "text": "PGP",

                                "indices": [

                                    130,

                                    134

                                    ]

                        }

                        ]

            },

            "contributors": null,

            "retweeted": false,

            "in_reply_to_user_id_str": null,

            "place": null,

            "retweet_count": 4,

            "created_at": "Sun Apr 03 20:24:49 +0000 2011",

            "user": {

                        "notifications": null,

                        "profile_use_background_image": true,

                        "statuses_count": 31,

                        "profile_background_color": "C0DEED",

                        "followers_count": 3066,

                        "profile_image_url": "http://a2.twimg.com/profile_images/1285770264/PGP_normal.jpg",

                        "listed_count": 6,

                        "profile_background_image_url": "http://a3.twimg.com/a/1301071706/images/themes/theme1/bg.png",

                        "description": "",

                     "screen_name": "PostGradProblem",

                        "default_profile": true,

                        "verified": false,

                        "time_zone": null,

                        "profile_text_color": "333333",

                        "is_translator": false,

                        "profile_sidebar_fill_color": "DDEEF6",

                        "location": "",

                        "id_str": "271572434",

                        "default_profile_image": false,

                        "profile_background_tile": false,

                        "lang": "en",

                        "friends_count": 21,

                        "protected": false,

                        "favourites_count": 0,

                        "created_at": "Thu Mar 24 19:45:44 +0000 2011",

                        "profile_link_color": "0084B4",

                        "name": "PostGradProblems",

                        "show_all_inline_media": false,

                        "follow_request_sent": null,

                        "geo_enabled": false,

                        "profile_sidebar_border_color": "C0DEED",

                        "url": null,

                        "id": 271572434,

                        "contributors_enabled": false,

                        "following": null,

                        "utc_offset": null

            },

            "id": 54640519019642880,

            "coordinates": null,

            "geo": null

            },

            "user": {

            "notifications": null,

            "profile_use_background_image": true,

            "statuses_count": 351,

            "profile_background_color": "C0DEED",

            "followers_count": 48,

            "profile_image_url": "http://a1.twimg.com/profile_images/455128973/gCsVUnofNqqyd6tdOGevROvko1_500_normal.jpg",

            "listed_count": 0,

            "profile_background_image_url": "http://a3.twimg.com/a/1300479984/images/themes/theme1/bg.png",

            "description": "watcha doin in my waters?",

            "screen_name": "OldGREG85",

            "default_profile": true,

             "verified": false,

            "time_zone": "Hawaii",

            "profile_text_color": "333333",

            "is_translator": false,

            "profile_sidebar_fill_color": "DDEEF6",

            "location": "Texas",

            "id_str": "80177619",

            "default_profile_image": false,

            "profile_background_tile": false,

            "lang": "en",

            "friends_count": 81,

            "protected": false,

            "favourites_count": 0,

            "created_at": "Tue Oct 06 01:13:17 +0000 2009",

            "profile_link_color": "0084B4",

            "name": "GG",

            "show_all_inline_media": false,

            "follow_request_sent": null,

            "geo_enabled": false,

            "profile_sidebar_border_color": "C0DEED",

            "url": null,

            "id": 80177619,

            "contributors_enabled": false,

            "following": null,

            "utc_offset": -36000

            },

            "id": 54691802283900930,

            "coordinates": null,

            "geo": null

}

 
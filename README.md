# vChallenge
Case Study provided by Alex Nastetsky from Verve Group

I had some fun this weekend working with this. :)
Mainly Programmed with Jupyter Notebook - Anaconda3-2020.02-Windows-x86_64.exe
vChallenge5.ipynb has all the intenal documents inside.
I joined two Dataframes(impressions,clicks) with dfinal_dupId = df_Im.merge(df_Ck, how='inner', left_on='id', right_on='impression_id') 
Because this columns are common - Joint Key.
For the spark, I downloaded - spark-3.1.2-bin-hadoop3.2.tgz

Questions 1,2 used mainly used Python in Jupyter - Output file - Answer-1-2.json
Questinn 3, Used Spark and had difficulty with setting up Environment(Spark,winUtils.exe...) - Answer-3.json
You can view formatted json file with https://jsonformatter.org/, I used  this 

I could not get the top 5 advertiser_id, only the max one. - Did not have enough time for this. 

Spark-testing.txt file is my worklog for Troubleshooting issues.

I did my best to guess the problems , so hopefully my guess is not off the chart.

Thanks a lot , hoping to talk to you guys soon


# Snowflake_project
1. Title - SNOWFLAKE_PROJECT
   --> Includes all the 3 approaches of data loding such as using 1. Accesses_ID & Access_key
                                                                  2. Bulk loading using storage integration + staging +copy                                                                          into 
                                                                  3. Continuous loading using snowpipe
   --> Covered all types of Streams & Tasks in snowflake
   --> Covered Time travel, fail safe & Zero copy cloning topics in snowflake
   --> 'To see all the above mentioned topics visit Documentation'

2. Architecture diagram or flow
   AWS S3--> Access_ID&Access_key-->storage integration + staging + copy into-->snowpipe-->streams-->tasks-->time travel-->       fail safe-->Zero copy cloning

3. Tech stack
   AWS S3, Snowflake, SQL

4. What it dose?
   --> Tryed to load data using manual and automated and covered both ways of loading data from S3 to Snowflake
   --> Automates ingestion of order data from S3 to Snowflake using event-driven Snowpipe, eliminating manual loads
   --> And covered the most important topics like streams. tasks, time travel, fail safe & zero copy cloning in snowflake

5. Folder structure
   --> Documentation
   --> Datasets

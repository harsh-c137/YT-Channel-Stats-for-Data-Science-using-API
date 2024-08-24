# YT-Channel-Stats-for-Data-Science-using-API

This code uses YouTube's API to grab the latest 50 videos from any channel, to give you a Pandas DataFrame containing:
1. `video_id`
2. `video_title`
3. `upload_date`
4. `view_count`
5. `like_count`
6. `comment_count`
for the latest 50 videos.

Need to update the code so it fetches data for `max_results` number of videos.

Great project to understand how API's work and how API Quota works.

## How to use
### A] CHANNEL_ID
1. For any YouTube channel, go to their landing page (like https://www.youtube.com/@MrBeast)
2. Press CTRL + U for Windows which should take you to the page's source code
3. CTRL + F for "?channel" which will take you to the `channel_id`
4. Plug it into the code where `CHANNEL_ID` is mentioned

### B] API_KEY
1. Refer to this super concise blog https://www.slickremix.com/docs/get-api-key-for-youtube/
2. Get your `API_KEY` and plug it into the code where mentioned

### C] Helpful Links
1. [List of Methods](https://developers.google.com/youtube/v3/docs) - to read up on the various channel properties that you can request for
2. https://console.cloud.google.com/iam-admin/quotas - to check how much quota you have remaining
    - Also check out https://developers.google.com/youtube/v3/determine_quota_cost to know the cost of each method that you'll use

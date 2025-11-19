# Tiktok dataset

- **19,383 rows** (TikTok videos)
- **12 columns**

| column name | type | description |
| ------------------------ | ------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| # | int | TikTok assigned number for video with claim/opinion. |
| claim_status | obj | Whether the published video has been identified as an "opinion" or a "claim." In this dataset, an "opinion" refers to an individual's or group's personal belief or thought. A "claim" refers to information that is either unsourced or from an unverified source. |
| video_id | int | Random identifying number assigned to video upon publication on TikTok. |
| video_duration_sec | int | How long the published video is measured in seconds. |
| video_transcription_text | obj | Transcribed text of the words spoken in the published video. |
| verified_status | obj | Indicates the status of the TikTok user who published the video in terms of their verification, either "verified" or "not verified." |
| author_ban_status | obj | Indicates the status of the TikTok user who published the video in terms of their permissions: "active," "under scrutiny," or "banned." |
| video_view_count | float | The total number of times the published video has been viewed. |
| video_like_count | float | The total number of times the published video has been liked by other users. |
| video_share_count | float | The total number of times the published video has been shared by other users. |
| video_download_count | float | The total number of times the published video has been downloaded by other users. |
| video_comment_count | float | The total number of comments on the published video. |

Data made available by Coursera for the [Google Advanced Data Analytics Professional Certificate program](https://www.coursera.org/professional-certificates/google-advanced-data-analytics).

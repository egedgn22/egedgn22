# DevMap Pipeline - Privacy Policy

Last updated: October 24, 2026 (added comment, Drive backup and Telegram sections)

DevMap Pipeline is a personal tool operated by Ege Doğan. It is used only by its owner to upload videos to his own YouTube channel and to review how those videos perform. It is not offered to the public.

## What data is accessed

The tool requests five Google permissions, all for the owner's own YouTube channel and Google Drive:

youtube.upload (https://www.googleapis.com/auth/youtube.upload): to upload videos, with their titles, descriptions and tags.

youtube.readonly (https://www.googleapis.com/auth/youtube.readonly): to read the channel's video list and public statistics such as views, likes and comments. Read only.

yt-analytics.readonly (https://www.googleapis.com/auth/yt-analytics.readonly): to read the channel's YouTube Analytics reports such as watch time, average view percentage, audience retention and subscribers gained. Read only.

youtube.force-ssl (https://www.googleapis.com/auth/youtube.force-ssl): only to post one comment, written by the owner's channel, on each of the channel's own videos after it is published. The tool also reads the text of recent comments on the channel's own videos (this is possible with youtube.readonly as well).

drive.file (https://www.googleapis.com/auth/drive.file): to store weekly backup files of the tool's own data in a folder in the owner's Google Drive. With this permission the tool can only see and manage files it created itself; it cannot see any other Drive files.

The tool does not edit or delete any existing YouTube videos or comments, and does not access any other Google account data.

## How data is used and stored

Upload permission is used only to publish videos the owner has reviewed and approved. Statistics and analytics data are used only to produce private performance reports for the owner.

The access token and all statistics and analytics data are stored only on the owner's own computer, in local files that are never published. To generate a written summary for the owner, the channel's own video titles and per-video performance figures may be sent to the Anthropic API. These are channel-level numbers.

Once a week, the text of comments posted on the channel's videos in the last 14 days is sent to the Anthropic API to summarize which video topics viewers are asking for. Only the comment text, its like count and the video ID are sent; commenter names, channel IDs and profile data are not collected or sent. The resulting topic list is stored on the owner's computer; the comment texts themselves are not stored.

Weekly backups (video history, channel statistics and reports, without any access tokens or keys) are stored in the owner's own Google Drive. Status notifications (video titles, publish times, error messages) are sent to the owner's own private Telegram chat through a bot only he controls.

No data is sold, shared with other third parties, or used for advertising.

## YouTube API Services

This tool uses YouTube API Services. By using it you agree to the YouTube Terms of Service (https://www.youtube.com/t/terms). Google's handling of data is described in the Google Privacy Policy (https://policies.google.com/privacy).

The use of information received from Google APIs adheres to the Google API Services User Data Policy, including the Limited Use requirements.

## Revoking access

Access can be revoked at any time at https://myaccount.google.com/permissions. Deleting the local token file also removes the tool's access, and deleting the local data folder and the "devmapco-yedek" folder in Google Drive removes all stored statistics.

## Contact

egedogan22@gmail.com

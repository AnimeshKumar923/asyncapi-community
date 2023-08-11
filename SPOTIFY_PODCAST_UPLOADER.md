#### This document covers the steps to upload a YouTube video/livestream from AsyncAPI YouTube Channel.

# FAQ

## Why do we need this feature?

- There are some people who favor listening the video/livestream as an audio (podcast) instead of watching the video.

- The goal is to upload our AsyncAPI video/livestreams on `Spotify For Podcasters` platform which will ultimately allow the listener to play the episodes on Spotify. Almost every YouTube video can be converted into a podcast.

- This workflow provides the solution to the above problem.

## Who can upload the videos?

- The workflow can only be triggered by a person who has the write-access to the `master` branch of `asyncapi/community` repository.

## What is needed?

- The YouTube video ID is needed to trigger the workflow.

## What is YouTube video ID?

- A YouTube video ID is a unique combination of characters that identifies a specific video on the YouTube platform. It's used in the URL of the video to direct users to the exact video they want to watch. The video ID is typically a sequence of letters, numbers, and special characters that generally comes after the "v=" parameter in the URL.
- More examples of video ID are given below: ⬇️

### How to find YouTube ID?

Let's take this video link for example: https://www.youtube.com/watch?v=3rg_7hIb9PQ

Here the video ID is the word/entity after `https://www.youtube.com/watch?v=`, i.e., `3rg_7hIb9PQ`

***

### List of different types of YouTube links

- `https://www.youtube.com/watch?v=VIDEO_ID`
  - Here, it can be https://www.youtube.com/watch?v=3rg_7hIb9PQ
- `https://youtu.be/VIDEO_ID`
  - Here, it can be https://www.youtu.be/3rg_7hIb9PQ
- `https://www.youtube.com/embed/VIDEO_ID`
  - Here, it can be https://www.youtube.com/embed/3rg_7hIb9PQ
- `https://www.youtube.com/playlist?list=PLAYLIST_ID`
  - Here, it can be https://www.youtube.com/playlist?list=PLbi1gRlP7piiaD67o1F4EOPoZztg2r8l6
- `https://www.youtube.com/shorts/VIDEO_ID`
  - Here, it can be https://www.youtube.com/shorts/3rg_7hIb9PQ
- `https://www.youtube.com/watch?v=VIDEO_ID&list=PLAYLIST_ID`
  - Here, it can be https://www.youtube.com/watch?v=deLUAobdVpw&list=PLbi1gRlP7piiaD67o1F4EOPoZztg2r8l6
- `https://youtube.com/shorts/VIDEO_ID?feature=share`
  - Here, it can be https://youtube.com/shorts/U5jUr8XAF_M?feature=share

*If you find more formats, please add to this list by raising an issue and with a follow-up Pull Request (PR)*

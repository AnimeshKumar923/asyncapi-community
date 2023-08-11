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
- [More examples](#list-of-different-types-of-youtube-links) of video ID are given below: ⬇️

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

***

# Step-by-step Procedure (Example)

Here is an example with procedure on how to use this workflow:

1. Go to the `Actions` section on GitHub. ![Drawing sketchpad](https://github.com/AnimeshKumar923/asyncapi-community/assets/99868037/12be967e-75bf-40ad-acb6-13664b5aaffc)

2. Scroll down the menu on the left hand-side.

![Screenshot from 2023-08-11 23-08-22](https://github.com/AnimeshKumar923/asyncapi-community/assets/99868037/31bbe495-0329-459b-83f7-c51474fb82a0)

3. Click on the `Upload Episode from YouTube To Spotify for Podcasters` option.
   ![Drawing-2 sketchpad](https://github.com/AnimeshKumar923/asyncapi-community/assets/99868037/6176c2a9-ed2f-45a8-aa98-797da9d7de88)

4. Click on the `Run Workflow` button. ![Drawing-3 sketchpad](https://github.com/AnimeshKumar923/asyncapi-community/assets/99868037/81dc14ce-61bf-4b97-b1d8-6b29d24773fa)
5. Provide the YouTube ID in the box. ![Drawing-4 sketchpad](https://github.com/AnimeshKumar923/asyncapi-community/assets/99868037/e0b8f092-df13-44ab-9e4e-7cdfcf551975)
6. Click on `Run workflow` button. ![Drawing-4 sketchpad(1)](https://github.com/AnimeshKumar923/asyncapi-community/assets/99868037/628e4c20-c2d6-4b76-9894-16c97b4a8501)

 

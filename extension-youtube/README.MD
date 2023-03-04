# Youtube

Display a Youtube playlist or set of Youtube playlists on your Teletron display. Play videos directly
from your display and enjoy!

![youtube gif](docs/youtube.gif)

## Obtaining the playlist ID

You need the playlist ID for the configuration of the components. You can get the playlist ID for any
playlist by:

1. Navigating to the playlist on youtube.com
2. The URL in your browser should look something like this: `https://www.youtube.com/watch?v=kruqyd56oMU&list=PL-7t9DoIELCS7VIrtZoPUxDQZxEjvke7d`
3. The playlist ID is the part of the URL after `list=`, so in this case: `PL-7t9DoIELCS7VIrtZoPUxDQZxEjvke7d`
4. Use that value in the configuration when a playlist ID is required.

## Configuration

You need to obtain a youtube API key from Google to allow the extension to query Youtube data.

Follow these steps to obtain one:

1. Log in to Google Developers Console.
2. Create a new project.
3. On the new project dashboard, click Explore & Enable APIs.
4. In the library, navigate to YouTube Data API v3 under YouTube APIs.
5. Enable the API.
6. Create a credential.
7. A screen will appear with the API key.

View a follow along explanation in [this video](https://www.youtube.com/watch?v=yuM7KH-JLu8).

Once you have obtained the API key, you can configure the youtube extension by opening the _Extensions_ menu
in the CMS.

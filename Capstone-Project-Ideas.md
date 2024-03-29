# Hit Potential

For this project, I'll use the [Billboard 200 data](https://www.billboard.com/charts/billboard-200/) provided on the Billboard website over the past 50 year and pair with Spotify's API to analyze the metadata of the best performing songs over the past half century. The exploration of this [rich data](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-analysis/) will be used to uncover possible features to create a project that can be used to make predictions on the potential for a song to make it onto the Billboard 200 (today and in the past).

This is obviously a very limited model as it is not going to take into account, external factors such as promotional budget or larger music trends. However, it can take into account fanbase and some other factors that are not solely related to the song's make-up leading to a reasonable indicator of whether a song has hit potential.

# Concert Forecasting

A project, I've been thinking about for quite some time and one that I'm most excited about exploring. Evaluating the return of an event and audience size before the artist is booked. This is a major issue in the booking business.

Using tour history data (e.g. [Pollstar](https://www.pollstar.com/tourhistories)), box office returns and other factors such as venue size and comparing the make-up of the population could be used to create a model that attempts to solve this difficult feed.

One challenge I see is that a lot of times the best dat and richest data for this issue is proprietary and only licensed out for specific purposes. However, working with a local promoter in Buffalo, NY I would be able to test out the model by making predictions on existing bookings (buying only limited data sets).

# Playlist Builder

[Setlist.fm](https://www.setlist.fm/) offers data on setlists of millions of concerts that can be scraped. The goal is to merge these setlists with information from the [Spotify API](https://developer.spotify.com/documentation/web-api/reference/tracks/get-audio-analysis/) on the make-up of the individual songs to create a model for the flow of the ideal concert list as used by the most successful concert artists. Based on this model I'd like to create a simple interface for users to assess whether a song is a good fit for a specific spot in a playlist. This could be used by businesses to create better Playlists on spotify as this is often a long and tedious task for marketers. Making playlist sharing for customers an easy to accomplish task on a regular basis.

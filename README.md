# nico-tracer
Watching history analysis on nicovideo.jp

## Difference between the official watching history page
* [ ] Lifetime of the history
  * Watching histories on the official page expire in 90 days.
* [ ] The histories will be stored after you reach the end of the track.
  * On the official page, the history will be stored when you start the new track.
* [ ] Data visualization
  * We (will) analyze and visualize your watching history more luxuriously.


## TODO
* [ ] Ensure an online storage with Google Firebase.
* [ ] Make the browser extension to upload the watching information to the storage.
  * [ ] We should hook some function on the `ended` event of the html5 `<video>` tag.
* [ ] Make a web frontend to display the watching history.
* [ ] Do some data visualization, e.g., top hits for each user in the frontend.

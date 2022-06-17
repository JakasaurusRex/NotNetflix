# Project 1 - *Name of App Here*

NotNetflix is a movies app using the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

Time spent: **~20** hours spent in total

## User Stories

The following **required** functionality is complete:

- [ X ] User sees an app icon on the home screen and a styled launch screen.
- [ X ] User can view a list of movies currently playing in theaters from The Movie Database.
- [ X ] Poster images are loaded using the UIImageView category in the AFNetworking library.
- [ X ] User sees a loading state while waiting for the movies API.
- [ X ] User can pull to refresh the movie list.
- [ X ] User sees an error message when there's a networking error.
- [ X ] User can tap a tab bar button to view a grid layout of Movie Posters using a CollectionView.

The following **optional** features are implemented:

- [ X ] User can tap a poster in the collection view to see a detail screen of that movie
- [ X ] User can search for a movie.
- [ ] All images fade in as they are loading.
- [ X ] User can view the large movie poster by tapping on a cell.
- [ ] For the large poster, load the low resolution image first and then switch to the high resolution image when complete.
- [ X ] Customize the selection effect of the cell.
- [ X ] Customize the navigation bar.
- [ X ] Customize the UI.
- [ ] Run your app on a real device.

The following **additional** features are implemented:

- [ X ] User can get a random movie selected in a fun way and click on the poster to find out more information.
- [ X ] User can watch latest trailer or teaser in details page.
- [ X ] User can see ratings and movie release date.

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. I could have implemented the segues better and the text everywhere is appeneded strings.
2. I would like to discuss how we can make dynamically sized cells in the table view.

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='http://i.imgur.com/link/to/your/gif/file.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [Kap](https://getkap.co/).

## Notes

Describe any challenges encountered while building the app.

Creating the random page was really tricky and I also struggled with the network error and search bar features but I figured them out in the end. There are a lot of resources online to explain Objective C and xcode. 

## Credits

List an 3rd party libraries, icons, graphics, or other assets you used in your app.

- [AFNetworking](https://github.com/AFNetworking/AFNetworking) - networking task library
- [youtube-ios-player-helper](https://github.com/youtube/youtube-ios-player-helper) - youtuber playback library

## License

    Copyright 2022 Jake Torres

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

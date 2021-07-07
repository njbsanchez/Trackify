<p align="center">
  <img width="200" src="https://i.ibb.co/CV47pR3/logo-point.png" alt="Connectify Logo">

</p>

<h1 align="center">
    Connectify
</h1>
<h3 align="center">
    A Music-Based Social Media App
</h3>

# Connectify

Connectify is a music-based social media app that allows you to see how your music taste compares to other music fanatics in your area! 

Connectify does this in 3 steps: Connects, Compares, and Creates. By connecting Spotify and providing geolocation,  users can flip through other listener profiles within distance, see comparison statistics based on a listener's top tracks/artists , and bookmark listeners for later reference. Bookmarks are then aggregated based on similarity, giving the user the option to create playlists based off local top tracks.

## Features

A user can either create an account/log in using their Spotify premium account - which is authorized via Spotify's oAuth flow.
<p align="center">
![login](https://media.giphy.com/media/iVadCUYD5cgST9KqhA/giphy.gif)
<img height="250" src="https://i.ibb.co/zJp0NJH/Screen-Shot-2021-07-07-at-11-04-23-AM.png" alt="Connectify Logo">
</p>
Using Geolocation API and Google Maps Javascript API, the user is able to see users in their area, mapped and listed via Connect page.
<p align="center">
![connect map](https://media.giphy.com/media/paafF5u3T7EmW1spve/giphy.gif)
</p>
The user's listening data is pulled from Spotify's API, creating a snapshot of the user's top tracks, artists, and recently played playlists.
<p align="center">
![my profile](https://media.giphy.com/media/Ga8oMboFCL3SMAwcFD/giphy.gif)
</p>
The user can peruse through the profiles of local users and see comparison analysis of music taste similarities and differences. Profiles are bookmarkable, allowing the user to categorize bookmarks based on similarity analysis.
<p align="center">
![other profile](https://media.giphy.com/media/6AfJ7iM51loKymS8yW/giphy.gif)
![bookmark](https://media.giphy.com/media/lMAKBzXpR9dMK2hdyM/giphy.gif)
</p>
Users can create playists based on user's they have bookmarked, opening opportunity to discover new music they may be interested in.
<p align="center">
![create a playlist](https://media.giphy.com/media/J0YRRz5OglN1xT1aP5/giphy.gif)
![see playlist](https://media.giphy.com/media/yyUdjy0ElHVAuwszlE/giphy.gif)
</p>
## Demo

For a quick demonstration of Connectify, please click the image below - You should be sent to a youtube video that covers various features of the app.
<p align="center">
[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/s4K1UPxAdaM/0.jpg)](https://www.youtube.com/watch?v=s4K1UPxAdaM)
</p>

## Tech Stack

- Python backend
- PostgreSQL database
- SQLalchemy
- React
- Flask
- Jinja
- JQuery
- HTML
- CSS
- Bootstrap

## Installation

To get started, clone Connectify by pasting below into your terminal.

```bash
git clone https://github.com/njbsanchez/Connectify.git
```

Once you have Connectify opened in your preferred code editor, create and activate your virtual environment.

```bash
virtualenv env
source env/bin/activate
```

Separately, create

```bash
virtualenv env
source env/bin/activate
```

## Usage

```python
import foobar

# returns 'words'
foobar.pluralize('word')

# returns 'geese'
foobar.pluralize('goose')

# returns 'phenomenon'
foobar.singularize('phenomena')
```

## Contributing

Pull requests are welcome. 

## Lets Connect!

You can reach me here on [Github](https://github.com/njbsanchez/Connectify) or connect with me on [LinkedIn](https://www.linkedin.com/in/njbsanchez/) at njbsanchez.

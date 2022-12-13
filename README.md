# Spoty

Command line utility for managing Spotify from dmenu

## Dependencies

```
# pacman -S netcat jq curl xdg-utils dmenu
```

## How to use?

1. Create a new App on your [Dashbord](https://developer.spotify.com/dashboard/applications)
2. Create file `$HOME/.config/spotify_credentials.json` with you client id and secret:

```json
{
  "client_id": "YOUR_CLIENT_ID",
  "client_secret": "YOUR_CLIENT_SECRET"
}
```


Like current track

```
spoty like
```

Like current track and add to playlist

```
spoty add-to-playlist
```

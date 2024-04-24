
# Hi, I'm Akash ! 👋


## 🚀 About Me
I'm just building different projects to learn about different apis, tech stacks and more...


# Spootify

Just a Spotify clone for learning purpose (with more rounded corner).


## Tech Stack

**Client:** React

**API:** Spotify Web API


## API Reference
#### Get Your Playlist Contents

```http
  GET /playlists/{playlist_id}

```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `playlist_id` | `string` | **Required**. The Spotify ID of the playlist. |

#### Get Your Playlists

```http
  GET /me/playlists
```

#### Get Current User's Profile

```http
  GET /me
```

#### Get Playback State
```http
  GET /me/player
```

#### Get Currently Playing Track
```http
  GET /me/player/currently-playing
```

#### Start/Resume Playback
```http
  PUT /me/player/play  
```

#### Skip To Next
```http
  POST /me/player/next
```

#### Skip To Previous
```http
  POST /me/player/previous
```

#### Set Playback Volume
```http
  PUT /me/player/volume
```
| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `volume_percent` | `integer` | **Required**. The volume to set (0 - 100). |

## Lessons Learned

****Spotify Web Api****

****State Reducers****

****Styling Structures****

****OAuth 2.0****




## Environment Variables

To run this project, you will need to edit the following environment variables present in Login.jsx file

`clientId` 

`redirectUri` 


## Tips

***Set-Up your app on Spotify for Developers site and get your 'clientId' and add your 'redirectUri' there.***

***Use a Premium Account for most of the features.***

***Might add more features in the future***

# JioMusic-API

API HOST:https://beatsapi.media.jio.com

imageurl: https://jioimages.cdn.jio.com/hdindiamusic/images/

# Language list: 

GET: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/listlanguage/

# Song List :

GET: https://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/home/{language}

Example: https://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/home/english

## Single Song Details 

GET: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/songdetails/{song_id}

Example: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/songdetails/713_712784_1

## Listen Song

GET: http://jiobeats.cdn.jio.com/mod/_definst_/mp4:hdindiamusic/audiofiles/717/716180/{song_id}_{bitrate}.mp4/playlist.m3u8

Example: http://jiobeats.cdn.jio.com/mod/_definst_/mp4:hdindiamusic/audiofiles/717/716180/717_716180_1_320.mp4/playlist.m3u8

# Search 

## Autocomplete 

GET: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/autocomplete/{name}

Example: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/autocomplete/Linkin+park

## Search 

GET: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/search2/{name}/{language (optional)}

Example: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/search2/linkin+park/

Example: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/search2/linkin+park/english

# Album List :

GET: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/albumsongs/albumid/{album_id}

Example: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/albumsongs/albumid/1041579

# Playlist:

GET: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/listsongs/playlistsongs/{playlist_id}

Example: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/listsongs/playlistsongs/4308

# Radio List:

GET: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/radiohome/{language}

Example: http://beatsapi.media.jio.com/v2_1/beats-api/jio/src/response/radiohome/english

Note: Radio list is not complete. 

---

Require a proxy for CORS (for Web Only)

---

## Legal

This code is in no way affiliated with, authorized, maintained, sponsored or endorsed by Jio or any of its affiliates or subsidiaries. This is an independent and unofficial API. Use at your own risk.
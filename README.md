## Google Music in Home Assistant
Stream from your [Google Music library](https://play.google.com/music/listen#/home) with Home Assistant

#### Based on [the original gmusic in HA code](https://github.com/Danielhiversen/home-assistant_config/blob/master/custom_components/switch/gmusic.py) by @Danielhiversen

Robbed from (https://github.com/tprelog/GoogleMusic_HomeAssistant#google-music-in-ha----as-a-media-player)

just a incredible hack to use Artist / Album browsing on gmusic to avoid usage of playlists (and 1000 song limit...)

now i can loop thrue all songs in my library and not be limited with restrictions

seems to be somewhat working now:

1. set input_select.gmusic_player_source = Catalog
2. select play mode from input_select.gmusic_player_play_mode (normal,shuffle,random,shuffle random)  
2. select Artist from input_select.gmusic_player_artist
3. select Album from artist from input_select.gmusic_player_album
4. set media_player.gmusic_player = ON
5. set media_player.gmusic_player = Play

no support whatsoever, just made it public if someone find this interesting and want to push it further

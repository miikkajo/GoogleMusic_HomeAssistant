## Google Music in Home Assistant
Stream from your [Google Music library](https://play.google.com/music/listen#/home) with Home Assistant

#### Based on [the original gmusic in HA code](https://github.com/Danielhiversen/home-assistant_config/blob/master/custom_components/switch/gmusic.py) by @Danielhiversen

Robbed from (https://github.com/tprelog/GoogleMusic_HomeAssistant#google-music-in-ha----as-a-media-player)

just a incredible hack to use Artist / Album browsing on gmusic to avoid usage of playlists (and 1000 song limit...)

seems to be somewhat working now:

1. set input_select.gmusic_player_source = Catalog
2. select Artist from input_select.gmusic_player_artist
3. select Album from artist from input_select.gmusic_player_album
4. set media_player.gmusic_player = ON

no support whatsoever, just made it public if someone find this intresting and want to push it further

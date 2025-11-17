
### Server & Browser Sync
Browser sync command line manual
[https://www.browsersync.io/docs/command-line](https://www.browsersync.io/docs/command-line)



Vimeo api

https://developer.vimeo.com/api/playground/me/albums/2334700/videos

GET https://api.vimeo.com/me/albums/2334700/videos?sort=manual HTTP/2

sort=manual



http://tympanus.net/Development/IconHoverEffects/#set-3
http://tympanus.net/Development/CreativeLinkEffects/

Icon transitions
http://codepen.io/simonbuerger/pen/bVgzve
http://codepen.io/trilm/pen/LEejop
http://tympanus.net/Development/AnimatedSVGIcons/

Spinner
http://codepen.io/jnowland/pen/XJPEBO

Slideshow
http://codepen.io/patrickkunka/pen/qeFds

Video PLayer
http://codepen.io/souporserious/pen/gEvKG

Font size unit vw
http://codepen.io/abass/pen/myPjyY

Scroll load
http://codepen.io/jackrugile/pen/GpRYao


APIs
https://picasaweb.google.com/data/feed/base/user/tomas.jonsgarden?alt=json&kind=album
https://picasaweb.google.com/data/feed/base/user/tomas.jonsgarden?alt=json&kind=photo
https://picasaweb.google.com/data/feed/api/user/tomas.jonsgarden?alt=json&kind=photo
https://picasaweb.google.com/data/feed/base/user/tomas.jonsgarden?alt=json

https://vimeo.com/api/v2/4487625/videos.json
https://vimeo.com/api/v2/4487625/albums.json
https://vimeo.com/api/v2/user4487625/info.json
https://vimeo.com/api/v2/album/2334700/videos.json
https://vimeo.com/api/v2/album/2329080/videos.json
https://vimeo.com/api/v2/album/2329074/videos.json



# Vimeo use OAuth2 client side to get the list of external access to video files

- Playground: https://developer.vimeo.com/api/playground/videos/98161105
- Vimeo auth doc: https://developer.vimeo.com/api/authentication
- JavaScript lib: https://github.com/andreassolberg/jso

Sample external links:

- https://player.vimeo.com/external/85420971.hd.mp4?s=387eedcf13cb48bc8cb8ad01d2699c9f&profile_id=113
- https://player.vimeo.com/external/73254855.hd.mp4?s=937157657332438a8273f9e038fe8dd8&profile_id=119




<iron-ajax url="https://api.vimeo.com/me/videos/113585297?token=efc8e0f1d6018066b758519bcb307208338c47ca"
<iron-ajax url="{{src}}" last-response="{{data}}" auto></iron-ajax>
<iron-ajax url="https://player.vimeo.com/video/113585297/config?token=efc8e0f1d6018066b758519bcb307208338c47ca" last-response="{{data}}" auto></iron-ajax>

<template><div>{{data.request.files.progressive.url}}</div></template>


The ajax to videos config cdn progressive links https://player.vimeo.com/video/169325478/config?token=efc8e0f1d6018066b758519bcb307208338c47ca

Proper API call for public and private videos:
Films: https://api.vimeo.com/me/albums/2329080/videos?per_page=50&sort=date&direction=desc&access_token=84b9fbcdd4baa488372baa6f2a45f249

Commercials: https://api.vimeo.com/me/albums/2329074/videos?per_page=50&sort=date&direction=desc&access_token=84b9fbcdd4baa488372baa6f2a45f249





Animated SVG Icons with Snap.svg
=========

Using SVGs on websites is becoming more and more easy with great libraries like Snap.svg. Today we want to explore what we can do with it and animate some SVG icons as a practical example.

[Article on Codrops](http://tympanus.net/codrops/?p=16851)

[Demo](http://tympanus.net/Tutorials/AnimatedSVGIcons/)

Integrate or build upon it for free in your personal or commercial projects. Don't republish, redistribute or sell "as-is".

Read more here: [License](http://tympanus.net/codrops/licensing/)


[© Codrops 2013](http://www.codrops.com)

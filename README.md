## Youtube-Play-Pause-Python
A python library that uses browser automation to play & pause videos on youtube automatically
At present, it runs on Windows only.
It uses [datakund](https://pypi.org/project/datakund) internally

Complete Documentation available [here](https://youtube-api.datakund.com/en/latest/)


### Support
For any help / feedback you can message us here
* datakund@gmail.com
* https://t.me/datakund

### Installation

```sh
pip install youtube-video-play-pause
```

### Import

```javascript
from youtube-video-play-pause import *
```

### Open Video

To open video we use ``open`` function.
It requires **video url** as input parameter

```javascript
youtube.open("place_video_url_here")
```

### Play Pause Video
```javascript
youtube.play_pause_video()
```

### DataKund
It uses [datakund](https://pypi.org/project/datakund/) internally to do browser automation
DataKund is an automation library that uses selenium & supports automation of many sites including [Youtube](https://youtube-api.datakund.com/en/latest/), [Amazon](https://amazon-api.datakund.com/en/latest/), [Twitter](https://twitter-api.datakund.com/en/latest/), [LinkedIn](https://linkedin-api.datakund.com/en/latest/) , [Google](https://google-api.datakund.com/en/latest/) etc.

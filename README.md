flow
====

### GET

http://example.com/api/channels

http://example.com/api/channels?userid=1

http://example.com/api/videos

http://example.com/api/videos?chanid=1

http://example.com/api/activities

http://example.com/api/video?videoid=1

### POST

http://example.com/api/video

BODY: {"domain" : "youtube.com", "vid" : "xxxxxx",  "title" : "Achievement Hunter…", "url": "http://www.youtube.com/embed/xxxx", "length": 600}

### POST

http://example.com/api/activity

BODY:{"type”: 1, "user_id": 1, "video_id": 1,"channel_id": 1}

### POST

http://example.com/api/channel

BODY:{'name': channel.name, 'value': channel.value, 'owner_id': 1}

### Update videos from reddit and youtube feed

### GET

http://example.com/update/videos


Aac worked with me
---------------

    ffmpeg -re -i input.mp4 -c:a copy  -vn -f rtp rtp://127.0.0.1:5005
H264 not worked with me
---------------

    ffmpeg -re -i input.mp4 -c:v copy -an -f rtp rtp://127.0.0.1:5000

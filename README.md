
Aac worked with me
---------------

    ffmpeg -re -i input.mp4 -c:a aac  -vn -f rtp rtp://127.0.0.1:5005
H264 not worked with me
---------------

    ffmpeg -re -i input.mp4 -c:v h264 -an -f rtp rtp://127.0.0.1:5000

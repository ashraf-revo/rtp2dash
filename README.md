How to Stream and How to Emulate a live encoder
================================================

help


//ffmpeg -re -i input.mp4 -c:a aac  -vn -f rtp rtp://127.0.0.1:5005   aac      working with me
//ffmpeg -re -i input.mp4 -c:v h264 -an -f rtp rtp://127.0.0.1:5000   h264 not working with me

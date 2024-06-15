### Run by docker 
```bash
sudo docker run --rm -it \
  --name yt-dlp \
  developercyrus/yt-dlp \
  yt-dlp -F "https://www.youtube.com/watch?v=aaVnBxOAgfc"

sudo docker run --rm -it \
  --name yt-dlp \
  --volume /tmp:/folder1
  developercyrus/yt-dlp \
  yt-dlp -f 270 --output /folder1/aaVnBxOAgfc.mp4 "https://www.youtube.com/watch?v=aaVnBxOAgfc"
```

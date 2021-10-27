# Parties
Instructions:
-Download the Jupyter Notebook file and in the same location folder create three folders with names : figures,data and video.    
-Create videos with ffmpeg: ffmpeg -r 14 -i Figures/snapshot_t_%d.png -c:v libx264 -r 30 -pix_fmt yuv420p -vf scale=1600:800 videos/out.mp4  

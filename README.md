# HLS-Convert-
# 🎬 FFmpeg HLS Converter for Google Colab

Convert your videos into adaptive bitrate HLS streams (144p–1080p) **directly in Google Colab** — no setup needed!  
The output includes `.m3u8` playlists and segment files ready for web playback.

---

## 🚀 Features

✅ Google Drive integration (input/output folders auto-created)  
✅ GPU acceleration via **NVENC** (if available)  
✅ Multiple resolutions (144p → 1080p)  
✅ Master `.m3u8` playlist generation  
✅ Real-time FFmpeg logs + progress output  
✅ Saves output directly to your Drive  

---

## 🧠 How It Works

1. Mounts your Google Drive
2. Downloads your video (optional)
3. Converts it into 6 HLS renditions using FFmpeg
4. Saves everything to `/MyDrive/output_hls/<video_name>/`

---

## 🧩 Steps to Use

1. **Open the notebook in Google Colab:**

   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<yourusername>/ffmpeg-hls-colab/blob/main/colab_notebook.ipynb)

2. **Mount your Google Drive**  
   The notebook will create:

3. **Upload your `.mp4` file** to the `input_videos` folder.

4. **Run the conversion cell**  
Watch live FFmpeg progress logs.

5. **Done!**  
The HLS output (with master playlist) will appear in:

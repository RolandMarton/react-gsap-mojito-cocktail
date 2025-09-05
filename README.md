# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

## FFmpeg code to optimize the video
ffmpeg -i input.mp4 -vf scale=960:-1 -movflags faststart -vcodec libx264 -crf 20 -g 1 -pix_fmt yuv420p output.mp4
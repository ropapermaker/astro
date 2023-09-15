---
title: Star Trails 2023
description: Star Trails Near the North Star
date: 2023-08-21 00:00:00+0000
image: astro_trails_voskopoje.jpg
categories:
    - Star Trails
tags:
    - stars
    - sky
    - trails
    - google pixel
    - oneplus
weight: 2
---

## Polaris Star Trails in Voskopoje
![Star Trails](astro_trails_voskopoje.jpg)

> Photo taken in Voskopojë, Albania.
> 
> Taken on the Pixel 7
>
>   - 1 hour total of photos
>   - Google Camera camera app with the night mode setting
>   - 6s exposure, 8s between each picture using the Intervalometer app
>   - Stitched together using StarStaX
>
> Post-edited in Lightroom with different settings.

### Timelapse
{{< video src="astro_trails_voskopoje.mp4" >}}

## Polaris Star Trails in Munich
![Star Trails](astro_trails_munich.jpg)

> Photo taken in Munich.
> 
> Taken on the Pixel 7
>
>   - 1 hour total of photos
>   - Google Camera camera app with the night mode setting
>   - 6s exposure, 8s between each picture using the Intervalometer app
>   - Stitched together using StarStaX
>
> Post-edited in Lightroom with different settings.

### Timelapse
{{< video src="astro_trails_munich.mp4" >}}

## Stitching in ffmpeg
Photos from StarStaX combined together using ffmpeg
```bash
ffmpeg -framerate 29 -pattern_type glob -i 'Star*.jpg' -vf scale=iw/2:ih/2,format=yuv420p -crf 18 -c:v libx264 outx264.mp4
```

## Star Trails From Video
![(1)](astro_trails_voskopoje_try1.jpg) ![(2)](astro_trails_voskopoje_try2.jpg) ![(3)](astro_trails_voskopoje_try3.jpeg)

![Captured on the Oneplus 6](astro_trails_voskopoje_op6.jpeg) ![Captured on the Pixel 6](astro_trails_voskopoje_p6_from_video.jpg)

> These are some of my first tries using images extracted from the short videos that the Astrophotography feature produces.
>
> ... and other methods


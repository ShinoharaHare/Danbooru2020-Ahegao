# Danbooru2020-Ahegao

Ahegao datasets from **Danbooru2020**

:warning: Might Containing Some NSFW Contents!

## Proccess Pipeline

1. Download all images whose tag includes `ahegao` and excludes `greyscale,spot_color` from **Danbooru2020**.
2. Crop the faces using [anime-face-detector](https://github.com/qhgz2013/anime-face-detector) with `conf 0.95`
3. Scale cropped images to 512x512 with [waifu2x-caffe](https://github.com/lltcggie/waifu2x-caffe) but keep the ratio
4. Pad scaled images to 512x512

## Download

|         \          |                                                Description                                                |                                              Cropped                                               |                                              512x512                                               |
| :----------------: | :-------------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: | :------------------------------------------------------------------------------------------------: |
|    Full (11168)    | Since it's not filtered, might containing low quality, grayscale, duplicate, non-face, non-ahegao images. | [Google Drive](https://drive.google.com/file/d/1-fwgiRe9WmaqIIqPLe18wU5tslGxJt3G/view?usp=sharing) |                                                                                                    |
| Handpicked  (2651) |              Handpicked partial images by myself, but still not confirm every image is good.              | [Google Drive](https://drive.google.com/file/d/1jbJQEwLZcHTQzGikWXL0bj3gFq07Rmmz/view?usp=sharing) | [Google Drive](https://drive.google.com/file/d/1XYXquD_m8OdEa7hRMnfG4Ms-Wf6j-rCW/view?usp=sharing) |

## Credits

- Artists
- Danbooru2020
- anime-face-detector: https://github.com/qhgz2013/anime-face-detector
- waifu2x-caffe: https://github.com/lltcggie/waifu2x-caffe

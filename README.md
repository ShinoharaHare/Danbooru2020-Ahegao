# Danbooru2020-Ahegao

Ahegao datasets from **Danbooru2020**

:warning: Might Containing Some NSFW Contents!

![](https://github.com/ShinoharaHare/Danbooru2020-Ahegao/raw/main/handpicked.jpg)

## Process Pipeline

1. Download all images whose tag includes `ahegao` and excludes `greyscale,spot_color` from **Danbooru2020**.
2. Crop the faces using [anime-face-detector](https://github.com/qhgz2013/anime-face-detector) with `conf 0.95`
3. Scale cropped images to 512x512 with [waifu2x-caffe](https://github.com/lltcggie/waifu2x-caffe) but keep the ratio
4. Pad scaled images to 512x512

## Download

|      Version       |                                                Description                                                |                                               Cropped                                                |                                                Scaled                                                |                                                Padded                                                |
| :----------------: | :-------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------: |
|    Full (11168)    | Since it's not filtered, might containing low quality, grayscale, duplicate, non-face, non-ahegao images. | [Google Drive](https://drive.google.com/u/1/uc?id=1-fwgiRe9WmaqIIqPLe18wU5tslGxJt3G&export=download) | [Google Drive](https://drive.google.com/u/1/uc?id=1db3Xvv7riZ-z7U8gz2MgfB34fwP8EzbD&export=download) | [Google Drive](https://drive.google.com/u/1/uc?id=1IRzjUR5oF03O4yD56xMhI2CLJ5Qa1oIw&export=download) |
| Handpicked  (2651) |              Handpicked partial images by myself, but still not confirm every image is good.              | [Google Drive](https://drive.google.com/u/1/uc?id=1jbJQEwLZcHTQzGikWXL0bj3gFq07Rmmz&export=download) | [Google Drive](https://drive.google.com/u/1/uc?id=1QCzo0-WCY0TeqCTRO8RTdPcJXN-2KTxD&export=download) | [Google Drive](https://drive.google.com/u/1/uc?id=1XYXquD_m8OdEa7hRMnfG4Ms-Wf6j-rCW&export=download) |

## Credits

- Artists
- Danbooru2020
- anime-face-detector: https://github.com/qhgz2013/anime-face-detector
- waifu2x-caffe: https://github.com/lltcggie/waifu2x-caffe

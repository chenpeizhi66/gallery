# Gallery

Photographs for [chenpeizhi66.github.io/gallery](https://chenpeizhi66.github.io/gallery/).

## Add a picture

Put the file in `photos/`. The site reads that folder and shows it. No change to the website repository is required.

Pictures: `.jpg`, `.jpeg`, `.png`, `.gif`, `.webp`, `.avif`.
Video: `.mp4`, `.webm`, `.mov`. These play on the same page.
Any other file in `photos/` is listed under Other.

iPhone HEIC files need to be exported as JPEG first. Browsers do not show HEIC.

## Captions

`photos/captions.json` maps a file name to one line of text:

```json
{
  "harbor.jpg": "Xinghai Bay, Dalian"
}
```

A picture with no entry is shown without a title. Names sort in reverse, so a date at the start of the file name (`2026-10-coast.jpg`) puts newer pictures first.

## 添加照片

把照片放进 `photos/` 即可，个人页面会自己读到，不用改网站仓库。

想在照片下面加一句说明，写到 `photos/captions.json`，键用文件名。

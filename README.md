# Video Thumbnail Generate

Use MTN be easy with **Quick Action** on macOS

## Require

- [HomeBrew](https://brew.sh/)
- [MTN](https://gitlab.com/movie_thumbnailer/mtn/-/wikis/home#macos) `brew install vitkabele/tap/mtn`

## Automator

![How to use](https://raw.githubusercontent.com/9MZa/video-thumbnail-generate/main/screenshot/use.png)

![Automator](https://raw.githubusercontent.com/9MZa/video-thumbnail-generate/main/automator.png)

## Script

`/opt/homebrew/bin/mtn -c 4 -r 5 -w 1920 -g 3 -D 4 -f /Library/Fonts/SF-Mono-Bold.otf -F ffffff:12:SF-Mono-Bold.otf:ffffff:000000:14 -h 30 -k 000000 -g 5 -j 100 -L 4:2 -z $1`

If you need too more custom that result. Visit [MNT Wiki](https://gitlab.com/movie_thumbnailer/mtn/-/wikis/home#macos)

## Thumbnail Screenshot

### 3 Columns 4 Rows

![3 Columns 4 Rows](https://raw.githubusercontent.com/9MZa/video-thumbnail-generate/main/screenshot/3*4.jpg)

### 4 Columns 5 Rows

![4 Columns 5 Rows](https://raw.githubusercontent.com/9MZa/video-thumbnail-generate/main/screenshot/4*5.jpg)

### 6 Columns 12 Rows

![6 Columns 12 Rows](https://raw.githubusercontent.com/9MZa/video-thumbnail-generate/main/screenshot/6*12.jpg)

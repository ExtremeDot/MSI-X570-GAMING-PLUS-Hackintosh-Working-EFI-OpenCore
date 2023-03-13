my Custom Icons

![image](https://user-images.githubusercontent.com/120102306/224538456-758a1d00-04c2-4b29-93bf-31234d8f6cc8.png)


***



[EFI - OpenCore : How to change Icon and Names? See my Wiki ](https://github.com/ExtremeDot/MSI-X570-GAMING-PLUS-Hackintosh-Working-EFI-OpenCore/wiki/How-to-Edit-OpenCore-Boot-Menu-Entries%3F-%5B-Os-Name,-Icon-and-Visibility%5D)


***



### How to create icons?

Create an Icon on 1024 x 1024 png formatted.

create a folder , name it xxxxx.iconset , ex: linux.iconset

resize files with these filenames

@2x means resolution 2x bigger.

icon_128x128@2x.png = 256x256


```sh
icon_128x128.png
icon_128x128@2x.png
icon_16x16.png
icon_16x16@2x.png
icon_256x256.png
icon_256x256@2x.png
icon_32x32.png
icon_32x32@2x.png
icon_512x512.png
icon_512x512@2x.png
icon_64x64@2x.png
```


run command from mac-os termianl

```sh
iconutil --convert icns /Users/extreme/Desktop/linux.iconset
```

new icon file will be generated on Desktop


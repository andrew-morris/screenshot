# screenshot
Teeny CLI utility to take a quick screenshot of a webpage, powered by PhantomJS.

## Disclaimer
I uploaded this simply because it's useful to me. This is nothing more than several lines of barely functioning code. Please feel free to extend it. I don't actually know Javascript. I also didn't even know you could declare PhantomJS as an interpreter with a shebang until a few days ago. Life is full of twists and turns. 

## Prerequisites
* PhantomJS

## Usage

* Change the shebang to point to your PhantomJS binary
* Optionally add this script to a location in your PATH variable for ease-of-use

```
$ ./screenshot google.com
$ file google.com.png
google.com.png: PNG image data, 603 x 444, 8-bit/color RGBA, non-interlaced
```

## Known Bugs

* Will not work if you try to execute on a full URL. Only really accepts hostnames or IPs. I need an adult.
* Will not work with HTTPS pages unless you change the source code. Sorry.
* Will shit the bed if you do not pass an argument.
* Has literally no error handling of any sort. Is like 5 lines of code. 


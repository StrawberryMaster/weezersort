<p><img src="https://styles.redditmedia.com/t5_2s48r/styles/mobileBannerImage_drl6dtvgh1x71.png"><h1 style="text-align: center">Weezersort</h1></p>

![GitHub](https://img.shields.io/github/license/StrawberryMaster/weezersort)
![GitHub repo size](https://img.shields.io/github/repo-size/StrawberryMaster/weezersort)
![GitHub last commit](https://img.shields.io/github/last-commit/StrawberryMaster/weezersort)
![JavaScript](https://img.shields.io/badge/-JavaScript-black?style=flat-square&logo=javascript)
![Made with love](https://img.shields.io/badge/Made%20with%20%E2%9D%A4%EF%B8%8F%20by-many_people,_really-red)

A sorter for Weezer songs. This is a fork of an [updated Weezer sorter](https://github.com/weezersorter/weezersorter.github.io), which was an updated version of the original [Weezer sorter](https://weezersorter.tumblr.com/), which was based on this [character sorter](https://github.com/execfera/charasort). 

## Features
- Sorts all released Weezer songs (including SZNZ projects + B-sides)
- Lets you pick which albums to include or exclude
- Light/dark mode (courtesy of the fork)
- Mobile-friendly (cheers!)
- No ads, no tracking (not on our behalf), nada
- Open source (MIT license), just like previous versions
- Keeps it weezy

## Contributing
Open an issue or pull request if you have any suggestions or find any bugs. If you want to add a new song, you can do so by editing the `[DATE].js` file in the `src/js/data` folder. The format is as follows:
```js
  {
    name: "Song title",
    img: "Album png.png",
    opts: {
      album: ["Album nickname"],
    }
    bside: true // only if it's a B-side
  },
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- [execfera](https://github.com/execfera) for the original sorter
- [weezersorter](https://github.com/weezersorter) and [teunvgisteren](https://github.com/teunvgisteren) for the updated sorter
- [Weezer](https://weezer.com), you know why
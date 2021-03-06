Link to the original [repository](https://github.com/ooJerryLeeoo/hyper-material-box)

# Why this fork?
I've decided to fork this repository because it allowed me to add my custom color scheme, then upload it to [npm](https://www.npmjs.com/package/hyper-material-box-linking) to use the plugins functionality of Hyper. Thus, I can easily retrieve my theme and my configuration.

# Preview of my theme

![](http://i.imgur.com/8agdo5V.png)
![](http://i.imgur.com/4Ijurkd.png)
![](http://i.imgur.com/HJv4PLx.png)
(testing the multi panes functionality of Hyper. The left and bottom right panes have less opacity because they are not focused)
![](http://i.imgur.com/CAw7Rus.png)
(Example with Vim, using [spf13's Vim](https://github.com/spf13/spf13-vim) and syntax highlighting)
![](http://i.imgur.com/vGscIUX.png)

Yeah I went pretty crazy (gradients, text shadow), but I like it this way and I wanted to test the customization of Hyper. It's pretty good. 

I use [fish](https://github.com/fish-shell/fish-shell) and [Oh my fish](https://github.com/oh-my-fish/oh-my-fish) for my shell and for managing my fish packages and themes. The theme used in fish is [cmorrel](https://github.com/oh-my-fish/oh-my-fish/blob/master/docs/Themes.md#cmorrell). In Hyper, you can find my configuration for my .hyper.js file. And I use [Hyper Material Box](https://github.com/ooJerryLeeoo/hyper-material-box) (the original repository) for my theme in Hyper. But if you want to use the theme showed in the screen, use this repository, because I have included the [material-linking.js](https://github.com/Liinkiing/hyper-material-box/blob/master/scheme/linking-material.js) scheme.

### Installation


``` javascript
module.exports = {
  plugins: [ 'hyper-material-box-linking' ],
}
```

And then, if you want to use my custom theme, juste add in the config


```javascript
module.exports = {
  config: {
    materialBox: {
      scheme: 'linking-material',
    }
  }
}
```

The rest of the documentation of the theme is available at the [original repository](https://github.com/ooJerryLeeoo/hyper-material-box)
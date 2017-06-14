Link to the original [repository](https://github.com/ooJerryLeeoo/hyper-material-box)

# Why this fork?
I've decided to fork this repository because it allowed me to add my custom color scheme, then upload it to [npm](https://www.npmjs.com/package/hyper-material-box-linking) to use the plugins functionality of Hyperterm. Thus, I can easily retrieve my theme and my configuration.

# Preview of my theme

![](http://i.imgur.com/8agdo5V.png)
![](http://i.imgur.com/4Ijurkd.png)

Yeah I went pretty crazy (gradients, text shadow), but I like it this way and I wanted to test the customization of Hyperterm. It's pretty good. 

I use [fish](https://github.com/fish-shell/fish-shell) and [Oh my fish](https://github.com/oh-my-fish/oh-my-fish) for my shell and for managing my fish packages and themes. The theme used in fish is [cmorrel](https://github.com/oh-my-fish/oh-my-fish/blob/master/docs/Themes.md#cmorrell). In Hyperterm, you can find my configuration for my .hyper.js file. And I use [Hyper Material Box](https://github.com/ooJerryLeeoo/hyper-material-box) (the original repository) for my theme in Hyperterm. But if you want to use the theme showed in the screen, use this repository, because I have included the [material-linking.js](https://github.com/Liinkiing/hyper-material-box/blob/master/scheme/linking-material.js) scheme.

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
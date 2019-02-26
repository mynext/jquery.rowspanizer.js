# jquery.rowspanizer.js
Dynamic rowspan based on the content of the table

![Example](http://i.imgur.com/qLRHlzV.png)

### Demo

<http://codepen.io/marcosesperon/pen/MyWNGx>

### jQuery

Use the plugin as follows:

```js
$('table').rowspanizer();
```

By default, `vertical-align: top` css style will be added. You can override default by passing the `vertical_align` option:
```js
$('table').rowspanizer({vertical_align: 'middle'});
```

You can define columns to rowspanize:

```js
$('table').rowspanizer({columns: [0,1,2]});
```

You can even choose not to remove cells, but only hide them:

```js
$('table').rowspanizer({hide_cells: true});
```

## Notes

* Requires jQuery 1.7+.

## License

This plugin is available under [the MIT license](http://mths.be/mit).

# Scaffold
A light-weight, easy-to-edit CSS grid system.

![Scaffold Banner](Images/scaffold-banner.jpg?raw=true)

Scaffold is a no-frills CSS grid for rapid responsive website development and easy customization.

Nothing but grid!


## About

* [Intuitive](#intuitive)
* [Responsive](#responsive)
* [Mobile-First](#mobile-first)
* [Easy to Build With](#easy-to-build-with)

___

### Intuitive

Like many grid systems works with 12 columns, all the required code is sensible and familiar.

Example:
```html
        <div class="container">
            <div class="row">
                <div class="col-12 center">

                    <h1>Hello World</h1>
```

### Responsive

Control the display of elements with [size]-only classes.

Example: 
```html
	<div class="col-6 lg-only justify">
		Lorem ipsum dolor sit amet, incorrupte efficiantur id quo, putant erroribus cum te,
		ad quas solet sensibus vix. Copiosae invidunt ex mea. Mel verear dolorem prodesset ne, 
		et wisi facilis vim. Mei ut soluta commune elaboraret.
	</div>
	<div class="col-6 justify">
		Ei debet congue mandamus quo. Eum natum legimus expetenda ne. Dolore gloriatur cu usu, 
		eruditi sensibus inimicus et per. Ne vix incorrupte definitiones.
	</div>
```

Sizes notation is **sm md lg**.


### Mobile-First

sm-only is visible by default. Columns are only rendered for larger screens after breakpoints.


### Easy to build with

No surprise behaviours, or changes to defaults so you can quickly start your own styles without finicking. 

___

## License

MIT.

___

## Acknowledgements

Inspired by [Simple Grid](https://github.com/zachacole/Simple-Grid)

___

Feedback is welcome and appreciated! Please send me your comments as an [issue](https://github.com/ReginaExMachina/scaffold/issues).

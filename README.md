# Scaffold
A light-weight, easy-to-edit CSS grid system.

![Scaffold Icon](Images/scaffold-icon.jpg?raw=true)

Scaffold is a no-frills CSS grid system for rapid responsive website development.


## Easy &  Intuitive

Like many grid systems works with 12 columns, all the required code is sensible and familiar.

Example:
        <div class="container">
            <div class="row">
                <div class="col-12 center">

                    <h1>Hello World</h1>


## 

Control the display of elements with [size]-only classes.

Example: 			

		<div class="col-6 lg-only justify">
			Lorem ipsum dolor sit amet, incorrupte efficiantur id quo, putant erroribus cum te, ad quas solet sensibus vix. Copiosae invidunt ex mea. Mel verear dolorem prodesset ne, et wisi facilis vim. Mei ut soluta commune elaboraret.
		</div>
		<div class="col-6 justify">
			 Ei debet congue mandamus quo. Eum natum legimus expetenda ne. Dolore gloriatur cu usu, eruditi sensibus inimicus et per. Ne vix incorrupte definitiones.
		</div>

sm md lg


## Mobile-First


sm-only is visible by default. Columns are only rendered for larger screens after breakpoints.

Note: Add -sm to the end of class name for columns that don't expand on mobile and small screens.

Example:  

		<div class="col-sm-6">
			Cu qui officiis mediocrem forensibus, cum sint purto scriptorem ad, has velit mucius iuvaret ex. Ex utinam homero vituperatoribus sea.
		</div> 


## License

MIT
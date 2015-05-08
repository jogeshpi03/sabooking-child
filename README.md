# sbBooking Child

This plugin's functionality is depending on [saBooking plugin](http://codecanyon.net/item/sabooking-tours-events-booking-wp-plugin/8970021) 
which gives you some extra functionality in shortcodes.  

If you wish to modify the template of this plugin then create **omsabooking** directory in your theme and copy files from **sabooking_child/admin/templates** 
and paste it in **your_theme/omsabooking** directory.


## Usage for Tours

* For Tour list use ```[omsa_tour_list]``` will provides you all tours in 4(default) columns
* If you wish to set two columns then add ```item="2"``` attribute in shortcode like ```[omsa_tour_list item="2"]``` 
* Max columns you can set up to **6**
* For featured tours use ```featured="1"``` attribute that will display on featured tour ```[omsa_tour_list item="2" featured="1"]``` 


## Usage for Locations

* For Locations List use ```[omsa_location_list]``` will provides you all locations in 4(default) columns
* If you control the number of location then use ```posts="10"``` attribute that will provide you latest 10 results ```[omsa_location_list posts="10"]```
* For columns control you same attribute ```item="2"``` will work like ```[omsa_location_list posts="10" item="2"]```
* For only featured locations use ```featured="1"``` attribute ```[omsa_location_list posts="10" item="2" featured="1"]```

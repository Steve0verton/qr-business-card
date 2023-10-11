# TODO List

Running list of things to do.

* Improve form to input contact information, better visual layout
* Use a variable map or some mechanism to easily map to a predefined syntaxt for the VCF contact file versus the hard-coded method in Javascript
* Ability to select phone and email "type" in standardized drop down
* Ability to select address "type" in standardized drop down
* Country code selection from standardizrd drop down
* More field validation, especially on all of the address components
* Print and download buttons to make it easier to save QR code
* Dynamically build the form on the screen for fields with multiple entries (i.e. phone, email, address) - button to add more than 1 of something (instead of showing static fields for all)
* Add Notes field
* Add checkbox for "preferred" fields (i.e. phone, email, address)
* Add birthday
* Google Maps address lookup validation
* Favicon for index.html

## Other Ideas

* Contact photo support
  * Issues with URL request body too large
    * Problem: [https://developers.google.com/chart/image/faq?csw=1#url_length](https://developers.google.com/chart/image/faq?csw=1#url_length)
    * Possible solution (switch to POST request): [https://developers.google.com/chart/image/docs/post_requests](https://developers.google.com/chart/image/docs/post_requests)

# MKMapView+AttributionView

## A MKMapView category that adds a method to obtain the AttributionView.

Licensed under the MIT License.

On iOS < 6.0, this category will give you a reference to the Google
logo. Starting from iOS 6.0, it gives a reference to the "Legal
Information" link that's placed in the bottom left corner by default.

Apple probably won't like it if you remove or hide the AttributionView from
the MKMapView, but moving it to a different location should be fair game.

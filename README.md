# silly-creaturing
A webring for a group of silly creatures, using OnionRing.js

This webring is for any of the Wireless System's friends to join if they want to. Its relatively easy to join!

In order to join the ring, send a PR to this repo adding the url to `onionring-variables.js` under the var site following the format and including the https. Then, on your site, add this snippet to your html in order to add the widget:

```
<div id='silly-creaturing'>
    <script type="text/javascript" src="https://ring.wsys.pet/onionring-variables.js"></script>
    <script type="text/javascript" src="https://ring.wsys.pet/onionring-widget.js"></script>
</div>
```

it is also recommended to add this snippet to the head of your page if you'd like to have some unified style to the widget (this can also be managed by you with css!)

```
<link rel="stylesheet" href="https://ring.wsys.pet/onionring.css">
```

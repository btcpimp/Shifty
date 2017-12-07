# Shifty
The Shifty Button is for website owners that want to easily accept altcoins on their site.

![https://shapeshift.io/images/shifty/xs_light_ss.png](https://shapeshift.io/images/shifty/xs_light_ss.png)
___

### Choose Button type
Colors: Light / Dark 

### Choose Cryptocurrency type
Currently over 40 choices, including: Bitcoin, Dash, Ether, Monero...

### Choose Button copy
Copy 1: Pay with Altcoins <br />
Copy 2: Pay with ShapeShift

### Add public key
(only for affiliates - [sign up here](https://shapeshift.io/affiliate.html))

### Add Cryptocurrency public (share) address
(Tip: use your own addresses, but if you want to use mine, here you go) <br />
<br />
Monero address: 44EfHnnajJmab6xvUmkWRda26rgfwvQHeHFmWDi48gzV6Zztn7iPkdDMn6FjSLZN12XrRd5PtWb2UeykmbWLWBnRLR6t2sv <br />
<br />
Bitcoin / Bitcoin Cash address: 13mpxrvYfrVwPFkpMvUZfRCrViYFj7yXRj <br />

### Optional
Add the amount you want to receive
___

## ShapeShift button Monero code ex1
[Click here](https://github.com/btcpimp/Shifty/blob/master/js/ex1.js)
<br /><br />
<a onclick="shapeshift_click(this, event);" href="https://shapeshift.io/shifty.html?destination=44EfHnnajJmab6xvUmkWRda26rgfwvQHeHFmWDi48gzV6Zztn7iPkdDMn6FjSLZN12XrRd5PtWb2UeykmbWLWBnRLR6t2sv&amp;output=XMR"><img src="https://shapeshift.io/images/shifty/xs_dark_ss.png" class="ss-button"></a>

```
<script>function shapeshift_click(a,e){e.preventDefault();var link=a.href;window.open(link,'1418115287605','width=700,height=500,toolbar=0,menubar=0,location=0,status=1,scrollbars=1,resizable=0,left=0,top=0');return false;}</script> <a onclick="shapeshift_click(this, event);" href="https://shapeshift.io/shifty.html?destination=44EfHnnajJmab6xvUmkWRda26rgfwvQHeHFmWDi48gzV6Zztn7iPkdDMn6FjSLZN12XrRd5PtWb2UeykmbWLWBnRLR6t2sv&amp;output=XMR"><img src="https://shapeshift.io/images/shifty/xs_dark_ss.png" class="ss-button"></a>
```

## ShapeShift button Bitcoin code ex2
[Click here](https://github.com/btcpimp/Shifty/blob/master/js/ex2.js)
<br /><br />
<a onclick="shapeshift_click(this, event);" href="https://shapeshift.io/shifty.html?destination=13mpxrvYfrVwPFkpMvUZfRCrViYFj7yXRj&amp;output=BTC"><img src="https://shapeshift.io/images/shifty/xs_light_ss.png" class="ss-button"></a>

```
<script>function shapeshift_click(a,e){e.preventDefault();var link=a.href;window.open(link,'1418115287605','width=700,height=500,toolbar=0,menubar=0,location=0,status=1,scrollbars=1,resizable=0,left=0,top=0');return false;}</script> <br />
<a onclick="shapeshift_click(this, event);" href="https://shapeshift.io/shifty.html?destination=13mpxrvYfrVwPFkpMvUZfRCrViYFj7yXRj&amp;output=BTC"><img src="https://shapeshift.io/images/shifty/xs_light_ss.png" class="ss-button"></a>
```

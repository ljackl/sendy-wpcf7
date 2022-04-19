Sendy-WPCF
==========

Sendy integration for WP Contact Form 7 (https://wordpress.org/plugins/contact-form-7/)

change the line to your Sendy location:

``$sendyUrl = "http://www.yoursendy.com/subscribe";``

Then use the Contact Form 7 to build you form like so:

```
<p>Name *<br />
    [text* your-name] </p>

<p>Your Email *<br />
    [email* your-email] </p>

<p>[acceptance acceptance-175 default:on] Yes! Sign me up for the BETA list!</p>

[sendywpcf id=""]

[quiz quiz-44 "4+2=?|6" "2+10=?|12" "X+Y=?|Z" "33+33=?|66" "A+B=?|C"]

<p>[submit "Sign ME Up!"]</p>
```

In the shortcode [sendywpcd id=""] add in your list id from Sendy.

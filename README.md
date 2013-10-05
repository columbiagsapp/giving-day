# Giving Day 2013

GSAPP website alterations for Columbia University Giving Day 2013

## Script

We will trigger a script one week before Giving Day (October 23) that will slowly mutate the background colors of the GSAPP website from white and grey to light versions of Columbia blue, and mutate the text from black to dark blue.

The site will look something like what happens when you type this in the console:

    $('li.menu-item a').css('color', '#072761');
    $('body').css('backgroundColor', '#dbecff').css('color', '#072761');
    $('#header, #navigation, #columbialogo').css('backgroundColor', '#b7d8fc');
    
![Example colors](https://raw.github.com/columbiagsapp/giving-day/master/example.png)

## Widget

We will make a Giving Day widget at 500px wide to put at the top of the site for the week prior to giving day with a countdown ticker in it.

On Giving Day, it will allow people to click through to give, and show the amount of money raised.

## Alumni Page

We will also put a similar widget on the Alumni page.

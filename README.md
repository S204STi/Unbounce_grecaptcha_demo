# Unbounce_grecaptcha_demo
Quick and dirty demonstration of how to implement the Google Recaptcha on a wysiwyg builder that does not support it natively.

As you can see, this code would ideally be either an include at the bottom of the body tag, or inline as you see it. The main components for this to work are the div with the id or 'recaptcha' and the onload script with a validate function. I have some checks in that validate function to make sure the user made at least minimal effort to fill out the form, but in this context we had other validation going on already.

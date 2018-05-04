# Postman Collection to Marvel API
Postman Collection to Test few Marvel API end points.

![Marvel for Developers](http://i.annihil.us/u/prod/marvel/i/mg/8/e0/52bdf830aa094.jpg "Marvel")

* Go to [Marvel Developer Page](https://developer.marvel.com/) to Sign in and get
   * Public Key
   * Private Key
* Import the *Testing Marvel API.postman_collection.json* to your Postman Environment
* When Editing your Collection, go to the *Pre-request* Tab
* Edit *pubkey* and *pvtkey* variables values to the one you've just get at **Marvel Developer Page**
* Other **Enviromnent Variables** will be automatically created, they are:
    * **ts**: Time stamp required
    * **apikey**: The same *pubkey* value
    * **hash**: Hash in MD5 created from *ts*, *pubkey* and *pvtkey*
> Time to Run! Good Luck!

This file was written with [Dillinger.io](https://dillinger.io/) Online Editor and [:octocat:](https://www.webpagefx.com/tools/emoji-cheat-sheet/)

 



Okay, now we know what reverse image searching program to use. Let's try to actually look at the picture now to figure out where it is!

Let's say we have a webcam we found on <a href="http://shodan.io/">Shodan.io</a>:

https://padcam.liverpool.ac.uk/cgi-bin/guestimage.html

<img width="3175" height="1797" alt="image" src="https://github.com/user-attachments/assets/a507e3ee-27b5-4cc3-b421-a356f9399b4a" />

Where is this camera?

The first thing we notice is the weird crest & title with a black bar (and possibly text) underneath it.

Second thing is the logo, "Kaplan".

The third thing is that there is a glass building next to a concrete building.

And finally, we have what appears to be a highway next to the glass building. Because it's a webcam, we can see cars moving quickly!

Putting this into a reverse image search program shows nothing.

Now, something important to note is the name of the webcam. The URL points to <a href="http://liverpool.ac.uk/">Liverpool.ac.uk</a>, which is a university in Liverpool.

If we just had an IP address, we could try to geolocate it using an online tool, checking the ASN number or finding it on Shodan.


Googling "Kaplan University of Liverpool" leads us to a news article about a new building. If we take a look at the image, it looks approximately similar to the one we saw.

<img width="585" height="394" alt="image" src="https://github.com/user-attachments/assets/7e7f1c30-5cb1-45fa-8238-f5da58fb9156" />

Rows of long glasses with a little bit of overhang.

Luckily for us, Liverpool have captioned the image.

"The proposed new Liverpool International College facility"

If we google Liverpool International College we get:


https://www.google.com/maps/place/University+of+Liverpool+International+College/@53.4062447,-2.9625347,17z/data=!4m5!3m4!1s0x487b211eda1b2f5f:0xc226c2ccfb209504!8m2!3d53.4060784!4d-2.9605928

<img width="923" height="512" alt="image" src="https://github.com/user-attachments/assets/0ef38009-2526-415d-85e3-1bfb451ce0f0" />

Which is our building! But it's not built yet... What gives?

In the bottom right hand corner, Google tells us the image was captured in June 2019.

<img width="2140" height="1908" alt="image" src="https://github.com/user-attachments/assets/1d80d16b-b21c-4b84-838b-3c72445b6ca4" />

So Google maps hasn't updated yet.

If we turn the camera around on Google maps, we can see where the live webcam should be.

<img width="2691" height="1624" alt="image" src="https://github.com/user-attachments/assets/ccc46eca-c4d5-4e8c-88ab-0b2b1338fe13" />

Somewhere on this building!


When geolocating an image, we want to point out big landmarks we can easily find on a map. Road layouts, business names, The Empire States Building.

Answer the questions below

_No Answer Needed_

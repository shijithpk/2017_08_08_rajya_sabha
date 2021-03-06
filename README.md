This is the code and data for a [slideshow on the Rajya Sabha elections](http://projects.wionews.com/how-will-rajya-sabha-elections-affect-nda-and-upa-numbers/) published on [wionews.com](http://www.wionews.com).

All the data on party numbers and alliances comes from the [Election commission](https://eci.nic.in), news reports and the occasional wikipedia entry. :)

First came up with the idea for this at a Huffington Post hackathon after the elections in March 2017. [Guneet Narula](https://twitter.com/guneetnarula) of Datameet and I even worked on a calculator to predict Rajya Sabha seats, we put out an [alpha version](https://sputznik.io/rajyasabhacal/), might come back to it soon. 

Used a modified version of the [reveal.js](http://lab.hakim.se/reveal-js/) library and D3.js to make this slideshow. [This slideshow](http://explunit.github.io/d3_cposc_2014.html#/) helped me figure out how to make D3 work with reveal.js .

The slideshow is kind of designed with mobiles in mind, but should look fine on desktops too.

A detailed illustration of how the Rajya Sabha elections are done and how counting takes place is available in this [Election Commission handbook](http://eci.nic.in/eci_main/ElectoralLaws/HandBooks/Handbook_For_Returning_Officers(Council_Elections).pdf#page=407). Other official explanations of the elections are available [here](http://bit.ly/2hDJubc) and [here](http://rajyasabha.nic.in/rsnew/rsat_work/CHAPTER—3.pdf#page=19), but the handbook has the most exhaustive explanation.

If you want to know how I analysed the data, the [ipython/jupyter notebook](https://nbviewer.jupyter.org/github/shijithpk/2017_08_08_rajya_sabha/blob/master/data/alliance_strength_over_time.ipynb) I used is available in the repository. It's commented, don't know how readable the code will be to someone else, but you're welcome to have a look.

The image for the Rajya Sabha chamber used in the first slide was taken from a photo gallery on the Rajya Sabha [website](http://rajyasabha.nic.in/rsnew/picture_gallery/162.asp).

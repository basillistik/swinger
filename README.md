# Swinger

Swinger is a couchapp for creating and showing Presentations. Think Keynote, stored in CouchDB, run via Javascript and Sammy.js.

A free hosted version of the application lives at [http://swinger.quirkey.com](http://swinger.quirkey.com)

# !NOTE!

The codebase is currently in flux while I'm working out authentication stuff. Unfortunately, the CouchDB's new authentication features are slated for version 0.11 but only available in CouchDB trunk. Therefore, the current state of swinger only works on CouchDB trunk. If you're on OSX you can easily [grab the latest CouchDBX nightly](http://couch.lstoll.net/nightly/).

## About

This was created as a Demo for my talk at jQuery Conf 2009 about Sammy.js, however, its usefulness might outlast my talk. We'll see.

## Requirements

* A running CouchDB server (>= 0.11)
* [CouchApp](http://github.com/couchapp/couchapp) - You need the latest and greatest couchapp for the push to work without errors. Follow [these instructions](http://wiki.github.com/couchapp/couchapp/manual-2) to install from source

## Usage

All you need to do to get up and running after the requirements are installed is:

    $ couchapp push . http://localhost:5984/swinger
    
It should print out instructions of where you can view it.

You can also set up a .couchapprc file that looks something like this:

    {
      "env": { 
        "default": {
          "db": "http://admin:password@localhost:5984/swinger"
        }
      }
    }

Once that is set up you can just do:

    $ couchapp push


## Acknowledgments

Swinger was greatly inspired by Pat Nakajima's [Slidedown](http://github.com/nakajima/slidedown). 

### Technologies/Projects used

* [Sammy.js](http://code.quirkey.com/sammy) for frontend controller/routing
* [CouchApp](http://github.com/couchapp/couchapp) for hosting the app in CouchDB
* [Aristo CSS](http://github.com/maccman/aristo/tree/master) for base buttons/styles
* [Showdown](http://attacklab.net/showdown/) for Markdown
* [Prettify](http://code.google.com/p/google-code-prettify/) for Code higlighting




























* [All Swingers Clubs & Sex Clubs](http://allswingersclubs.org/)
* [Swingers clubs & Sex clubs in Argentina](http://allswingersclubs.org/country/argentina/)
* [Swingers clubs & Sex clubs in Australia](http://allswingersclubs.org/country/australia/)
* [Swingers clubs & Sex clubs in Austria](http://allswingersclubs.org/country/austria/)
* [Swingers clubs & Sex clubs in Bahamas](http://allswingersclubs.org/country/bahamas/)
* [Swingers clubs & Sex clubs in Belgium](http://allswingersclubs.org/country/belgium/)
* [Swingers clubs & Sex clubs in Bolivia](http://allswingersclubs.org/country/bolivia/)
* [Swingers clubs & Sex clubs in Brazil](http://allswingersclubs.org/country/brazil/)
* [Swingers clubs & Sex clubs in Bulgaria](http://allswingersclubs.org/country/bulgaria/)
* [Swingers clubs & Sex clubs in Canada](http://allswingersclubs.org/country/canada/)
* [Swingers clubs & Sex clubs in Chile](http://allswingersclubs.org/country/chile/)
* [Swingers clubs & Sex clubs in China](http://allswingersclubs.org/country/china/)
* [Swingers clubs & Sex clubs in Colombia](http://allswingersclubs.org/country/colombia/)
* [Swingers clubs & Sex clubs in Costa Rica](http://allswingersclubs.org/country/costa-rica/)
* [Swingers clubs & Sex clubs in Croatia](http://allswingersclubs.org/country/croatia/)
* [Swingers clubs & Sex clubs in Czech Republic](http://allswingersclubs.org/country/czech-republic/)
* [Swingers clubs & Sex clubs in Denmark](http://allswingersclubs.org/country/denmark/)
* [Swingers clubs & Sex clubs in Dominican Republic](http://allswingersclubs.org/country/dominican-republic/)
* [Swingers clubs & Sex clubs in Estonia](http://allswingersclubs.org/country/estonia/)
* [Swingers clubs & Sex clubs in Finland](http://allswingersclubs.org/country/finland/)
* [Swingers clubs & Sex clubs in France](http://allswingersclubs.org/country/france/)
* [Swingers clubs & Sex clubs in Germany](http://allswingersclubs.org/country/germany/)
* [Swingers clubs & Sex clubs in Greece](http://allswingersclubs.org/country/greece/)
* [Swingers clubs & Sex clubs in Guatemala](http://allswingersclubs.org/country/guatemala/)
* [Swingers clubs & Sex clubs in Hungary](http://allswingersclubs.org/country/hungary/)
* [Swingers clubs & Sex clubs in Indonesia](http://allswingersclubs.org/country/indonesia/)
* [Swingers clubs & Sex clubs in Ireland](http://allswingersclubs.org/country/ireland/)
* [Swingers clubs & Sex clubs in Italy](http://allswingersclubs.org/country/italy/)
* [Swingers clubs & Sex clubs in Jamaica](http://allswingersclubs.org/country/jamaica/)
* [Swingers clubs & Sex clubs in Latvia](http://allswingersclubs.org/country/latvia/)
* [Swingers clubs & Sex clubs in Lithuania](http://allswingersclubs.org/country/lithuania/)
* [Swingers clubs & Sex clubs in Luxembourg](http://allswingersclubs.org/country/luxembourg/)
* [Swingers clubs & Sex clubs in Malaysia](http://allswingersclubs.org/country/malaysia/)
* [Swingers clubs & Sex clubs in Mexico](http://allswingersclubs.org/country/mexico/)
* [Swingers clubs & Sex clubs in Netherlands](http://allswingersclubs.org/country/netherlands/)
* [Swingers clubs & Sex clubs in New Zealand](http://allswingersclubs.org/country/new-zealand/)
* [Swingers clubs & Sex clubs in Norway](http://allswingersclubs.org/country/norway/)
* [Swingers clubs & Sex clubs in Peru](http://allswingersclubs.org/country/peru/)
* [Swingers clubs & Sex clubs in Philippines](http://allswingersclubs.org/country/philippines/)
* [Swingers clubs & Sex clubs in Poland](http://allswingersclubs.org/country/poland/)
* [Swingers clubs & Sex clubs in Portugal](http://allswingersclubs.org/country/portugal/)
* [Swingers clubs & Sex clubs in Puerto Rico](http://allswingersclubs.org/country/puerto-rico/)
* [Swingers clubs & Sex clubs in Romania](http://allswingersclubs.org/country/romania/)
* [Swingers clubs & Sex clubs in Saint-Martin](http://allswingersclubs.org/country/saint-martin/)
* [Swingers clubs & Sex clubs in Singapore](http://allswingersclubs.org/country/singapore/)
* [Swingers clubs & Sex clubs in South Africa](http://allswingersclubs.org/country/south-africa/)
* [Swingers clubs & Sex clubs in Spain](http://allswingersclubs.org/country/spain/)
* [Swingers clubs & Sex clubs in Suriname](http://allswingersclubs.org/country/suriname/)
* [Swingers clubs & Sex clubs in Sweden](http://allswingersclubs.org/country/sweden/)
* [Swingers clubs & Sex clubs in Switzerland](http://allswingersclubs.org/country/switzerland/)
* [Swingers clubs & Sex clubs in Thailand](http://allswingersclubs.org/country/thailand/)
* [Swingers clubs & Sex clubs in Trinidad And Tobago](http://allswingersclubs.org/country/trinidad-and-tobago/)
* [Swingers clubs & Sex clubs in Turkey](http://allswingersclubs.org/country/turkey/)
* [Swingers clubs & Sex clubs in UK](http://allswingersclubs.org/country/uk/)
* [Swingers clubs & Sex clubs in Ukraine](http://allswingersclubs.org/country/ukraine/)
* [Swingers clubs & Sex clubs in Uruguay](http://allswingersclubs.org/country/uruguay/)
* [Swingers clubs & Sex clubs in Venezuela](http://allswingersclubs.org/country/venezuela/)<!-- states -->
* [Swingers clubs & Sex clubs in Alabama (AL)](http://allswingersclubs.org/al-clubs.html)
* [Swingers clubs & Sex clubs in Alaska (AK)](http://allswingersclubs.org/ak-clubs.html)
* [Swingers clubs & Sex clubs in Arizona (AZ)](http://allswingersclubs.org/az-clubs.html)
* [Swingers clubs & Sex clubs in Arkansas (AR)](http://allswingersclubs.org/ar-clubs.html)
* [Swingers clubs & Sex clubs in California (CA)](http://allswingersclubs.org/ca-clubs.html)
* [Swingers clubs & Sex clubs in Colorado (CO)](http://allswingersclubs.org/co-clubs.html)
* [Swingers clubs & Sex clubs in Connecticut (CT)](http://allswingersclubs.org/ct-clubs.html)
* [Swingers clubs & Sex clubs in Delaware (DE)](http://allswingersclubs.org/de-clubs.html)
* [Swingers clubs & Sex clubs in Florida (FL)](http://allswingersclubs.org/fl-clubs.html)
* [Swingers clubs & Sex clubs in Georgia (GA)](http://allswingersclubs.org/ga-clubs.html)
* [Swingers clubs & Sex clubs in Hawaii (HI)](http://allswingersclubs.org/hi-clubs.html)
* [Swingers clubs & Sex clubs in Idaho (ID)](http://allswingersclubs.org/id-clubs.html)
* [Swingers clubs & Sex clubs in Illinois (IL)](http://allswingersclubs.org/il-clubs.html)
* [Swingers clubs & Sex clubs in Indiana (IN)](http://allswingersclubs.org/in-clubs.html)
* [Swingers clubs & Sex clubs in Iowa (IA)](http://allswingersclubs.org/ia-clubs.html)
* [Swingers clubs & Sex clubs in Kansas (KS)](http://allswingersclubs.org/ks-clubs.html)
* [Swingers clubs & Sex clubs in Kentucky (KY)](http://allswingersclubs.org/ky-clubs.html)
* [Swingers clubs & Sex clubs in Louisiana (LA)](http://allswingersclubs.org/la-clubs.html)
* [Swingers clubs & Sex clubs in Maine (ME)](http://allswingersclubs.org/me-clubs.html)
* [Swingers clubs & Sex clubs in Maryland (MD)](http://allswingersclubs.org/md-clubs.html)
* [Swingers clubs & Sex clubs in Massachusetts (MA)](http://allswingersclubs.org/ma-clubs.html)
* [Swingers clubs & Sex clubs in Michigan (MI)](http://allswingersclubs.org/mi-clubs.html)
* [Swingers clubs & Sex clubs in Minnesota (MN)](http://allswingersclubs.org/mn-clubs.html)
* [Swingers clubs & Sex clubs in Mississippi (MS)](http://allswingersclubs.org/ms-clubs.html)
* [Swingers clubs & Sex clubs in Missouri (MO)](http://allswingersclubs.org/mo-clubs.html)
* [Swingers clubs & Sex clubs in Montana (MT)](http://allswingersclubs.org/mt-clubs.html)
* [Swingers clubs & Sex clubs in Nebraska (NE)](http://allswingersclubs.org/ne-clubs.html)
* [Swingers clubs & Sex clubs in Nevada (NV)](http://allswingersclubs.org/nv-clubs.html)
* [Swingers clubs & Sex clubs in New Hampshire (NH)](http://allswingersclubs.org/nh-clubs.html)
* [Swingers clubs & Sex clubs in New Jersey (NJ)](http://allswingersclubs.org/nj-clubs.html)
* [Swingers clubs & Sex clubs in New Mexico (NM)](http://allswingersclubs.org/nm-clubs.html)
* [Swingers clubs & Sex clubs in New York (NY)](http://allswingersclubs.org/ny-clubs.html)
* [Swingers clubs & Sex clubs in North Carolina (NC)](http://allswingersclubs.org/nc-clubs.html)
* [Swingers clubs & Sex clubs in North Dakota (ND)](http://allswingersclubs.org/nd-clubs.html)
* [Swingers clubs & Sex clubs in Ohio (OH)](http://allswingersclubs.org/oh-clubs.html)
* [Swingers clubs & Sex clubs in Oklahoma (OK)](http://allswingersclubs.org/ok-clubs.html)
* [Swingers clubs & Sex clubs in Oregon (OR)](http://allswingersclubs.org/or-clubs.html)
* [Swingers clubs & Sex clubs in Pennsylvania (PA)](http://allswingersclubs.org/pa-clubs.html)
* [Swingers clubs & Sex clubs in Rhode Island (RI)](http://allswingersclubs.org/ri-clubs.html)
* [Swingers clubs & Sex clubs in South Carolina (SC)](http://allswingersclubs.org/sc-clubs.html)
* [Swingers clubs & Sex clubs in South Dakota (SD)](http://allswingersclubs.org/sd-clubs.html)
* [Swingers clubs & Sex clubs in Tennessee (TN)](http://allswingersclubs.org/tn-clubs.html)
* [Swingers clubs & Sex clubs in Texas (TX)](http://allswingersclubs.org/tx-clubs.html)
* [Swingers clubs & Sex clubs in Utah (UT)](http://allswingersclubs.org/ut-clubs.html)
* [Swingers clubs & Sex clubs in Vermont (VT)](http://allswingersclubs.org/vt-clubs.html)
* [Swingers clubs & Sex clubs in Virginia (VA)](http://allswingersclubs.org/va-clubs.html)
* [Swingers clubs & Sex clubs in Washington (WA)](http://allswingersclubs.org/wa-clubs.html)
* [Swingers clubs & Sex clubs in Washington, DC (DC)](http://allswingersclubs.org/dc-clubs.html)
* [Swingers clubs & Sex clubs in West Virginia (WV)](http://allswingersclubs.org/wv-clubs.html)
* [Swingers clubs & Sex clubs in Wisconsin (WI)](http://allswingersclubs.org/wi-clubs.html)
* [Swingers clubs & Sex clubs in Wyoming (WY)](http://allswingersclubs.org/wy-clubs.html)
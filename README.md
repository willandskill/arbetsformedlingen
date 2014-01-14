arbetsformedlingen
==================

A Python wrapper for [Arbetsförmedlingens API](http://api.arbetsformedlingen.se/)

##Usage

* ```pip install``` the package

```
import arbetsformedlingen

#First page of listings (20 at a time)
page = 1

#The 'län' of the listings (1 is Stockholm) 
lanid = 1

listings = arbetsformedlingen.get_listings()
first_listing = listings[0]
print first_listing['title']
```

[Complete list of läns offered by Arbetsförmedlingen](http://api.arbetsformedlingen.se/platsannons/soklista/lan)

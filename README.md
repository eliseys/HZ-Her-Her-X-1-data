# HZ Her/Her X-1 data
Optical data of X-ray binary system HZ Her/Her X-1

The JSON file has the following structure:
```
{
  "0.0":
    {
	  "B":
	    {
	      "JD":[...],
	      "flux":[...],
	      "orbit":[...],
	      "prec":[...]
	    }
	  "V":
	    {
	      "JD":[...],
	      "flux":[...],
	      "orbit":[...],
	      "prec":[...]
	    }
    }
  "1.0":
    {
	    "B":
	      {
	        "JD":[...],
	        "flux":[...],
	        "orbit":[...],
	        "prec":[...]
	      }
	    "V":
	      {
	        "JD":[...],
	        "flux":[...],
	        "orbit":[...],
	        "prec":[...]
	       }
    }
    
    ...	
	
}
```

where `"0.0", "1.0", ..., "19.0"` is the number of bin of precession phase (*n* in the article).

`"B"` and `"V"` is the name of the Johnson-Cousins filter.

All the observations in each bin *n* combined in the following lists: 

`"JD":[...]` is the Modified Julian Date of the observations.

`"flux":[...]` is the relative flux in the corresponding filter (flux in the main minimum equals 1).

`"orbit":[...]` is the orbital phase of the observation (0 corresponds to main minima).

"prec":[...] is the superorbital 35-day phase of the observation.


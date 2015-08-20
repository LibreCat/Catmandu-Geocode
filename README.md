# NAME

Catmandu::Geocode - Catmandu modules for the Google Maps geocoding api

# SYNOPSIS

    geocode(address)         # address: 'Hollywood and Highland, Los Angeles, CA' 
    reverse_gecode(latlng)   # latlng:  '34.1015473,-118.3387288'

# DESCRIPTION

This code requires you to create a Google MAP API key:

    https://console.developers.google.com//flows/enableapi?apiid=geocoding_backend&keyType=SERVER_SIDE

Your UNIX environment should contain two variabels:

    export GMAP_CLIENT=<your_google_address>
    export GMAP_KEY=<your_api_key>

As a free service a maximum of 5 requests per second are permitted, 2500 requests per day.

# MODULES

- [Catmandu::Fix::geocode](https://metacpan.org/pod/Catmandu::Fix::geocode)
- [Catmandu::Fix::reverse\_geocode](https://metacpan.org/pod/Catmandu::Fix::reverse_geocode)

# SEE ALSO

[Catmandu::Fix](https://metacpan.org/pod/Catmandu::Fix) , [Geo::Coder::Google](https://metacpan.org/pod/Geo::Coder::Google)

# AUTHOR

Patrick Hochstenbach, `<patrick.hochstenbach at ugent.be>`

# LICENSE AND COPYRIGHT

Copyright 2012 Ghent University Library

This program is free software; you can redistribute it and/or modify it
under the terms of either: the GNU General Public License as published
by the Free Software Foundation; or the Artistic License.

See http://dev.perl.org/licenses/ for more information.

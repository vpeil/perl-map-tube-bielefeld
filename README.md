# NAME

Map::Tube::Bielefeld - interface to the Bielefeld Stadtbahn

# DESCRIPTION

It currently provides functionality to find the shortest route between
the two given stations.

# CONSTRUCTOR

    use Map::Tube::Bielefeld;
    my $tube = Map::Tube::Bielefeld->new;

# METHODS

## get\_shortest\_route(_START_, _END_)

This method expects two parameters _START_ and _END_ station name.
Station names are case insensitive. The station sequence from _START_
to _END_ is returned.

    use Map::Tube::Bielefeld;
    my $tube = Map::Tube::Bielefeld->new;
    my $route = $tube->get_shortest_route('', '');
    print "Route: $route\n";

# AUTHOR

Vitali Peil <vitali.peil@uni-bielefeld.de>

# COPYRIGHT

Copyright 2019- Vitali Peil

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

[Map::Tube](https://metacpan.org/pod/Map::Tube).

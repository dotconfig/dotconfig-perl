# NAME

dotconfig - deserializing dotconfig formatted file

# SYNOPSIS

    use dotconfig;
    my $config = load_config("path/to/app.config");

    # or
    
    my $config = decode_config(q| { foo: "bar" } |);

# DESCRIPTION

dotconfig is a deserialization library for dotconfig formatted files.

dotconfig specification is a text format for the serialization of hand-written application configurations. See also [https://github.com/dotconfig/spec](https://github.com/dotconfig/spec)

Serializing methods are not supported currently.

# AUTHOR

punytan <punytan@gmail.com>

# COPYRIGHT

Copyright 2015- punytan

# LICENSE

This library is free software; you can redistribute it and/or modify
it under the same terms as Perl itself.

# SEE ALSO

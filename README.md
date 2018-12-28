[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=65SFZJ25PSKG8&currency_code=SEK&source=url) - Every tiny cent helps a lot!


accesstail - like tail -f, but prettier, for your access.log
------------------------------------------------------------

![accesstail](/extra/accesstail.png)


# USAGE

accesstail \[OPTION\]... \[FILE\]...

Provide an accesslog or export the env var ACCESS_LOG in your shellrc.


# INSTALLATION

    cpan Term::ExtendedColor File::LsColor File::Tail
    git clone git://github.com/trapd00r/accesstail.git
    cd accesstail
    perl Makefile.PL
    make && su -c 'make install'


# AUTHOR

    \ \ | / /
     \ \ - /
      \ | /
      (O O)
      ( < )
      (-=-)

    Magnus Woldrich
    CPAN ID: WOLDRICH
    m@japh.se
    http://japh.se


# COPYRIGHT

Copyright 2018 AUTHOR and CONTRIBUTORS as listed above.

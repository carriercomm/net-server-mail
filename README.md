Net::Server::Mail
=================

This module is a versatile and extensible implementation of the SMTP
protocol and its different evolutions like ESMTP and LMTP. The event
driven object-oriented API makes easy to incorporate the SMTP protocol
to your programs.

Other SMTPd implementations don't support useful ESMTP extensions and
the LMTP protocol. Their interface design precludes adding them
later. So I've decided to rewrite a complete implementation with
extensibility in mind.

It provides mechanism to easy addition future or not yet implemented
ESMTP extensions. Developers can hook code at each SMTP session state
and change the module's behaviors by registering event call-backs. The
class is designed to be easily inherited from.

Installation
------------

To install this module type the following:

    perl Makefile.PL
    make
    make test
    make install

Dependencies
------------

This module requires these other modules and libraries:

Sys::Hostname IO::Select and Carp all available on CPAN.

Licence
-------

This library is  free software; you can redistribute  it and/or modify
it  under  the terms  of  the GNU  Lesser  General  Public License  as
published by the  Free Software Foundation; either version  2.1 of the
License, or (at your option) any later version.

This library  is distributed in the  hope that it will  be useful, but
WITHOUT   ANY  WARRANTY;   without  even   the  implied   warranty  of
MERCHANTABILITY  or FITNESS  FOR A  PARTICULAR PURPOSE.   See  the GNU
Lesser General Public License for more details.

You  should have  received a  copy of  the GNU  Lesser  General Public
License along  with this library; if  not, write to  the Free Software
Foundation, Inc.,  59 Temple Place,  Suite 330, Boston,  MA 02111-1307
USA

Copyright
---------

* Copyright (C) 2002 - Olivier Poitrey
* Copyright (C) 2007-2015 - Xavier Guimard <x.guimard@free.fr>

STARTTLS

* Copyright (C) 2009 - Dan Moore
* Copyright (C) 2013 - Mytram <rmytram@gmail.com>
* Copyright (C) 2013 - Xavier Guimard <x.guimard@free.fr>

Contributors

 * Georg Hoesch (patch to reduce memory consumption)


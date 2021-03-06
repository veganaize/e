e
=

the minimalistest text editor


Description
=

Weighing in at about half the memory footprint of ed, e is the most minimalist text editor I am aware of. This is achieved through its ridiculously minimalist feature set. e has no output, and only takes four commands: save (ctrl+d), close (ctrl+f), seek left (ctrl+j), and seek right (ctrl+k). Rather than taking a file name as an argument (e has no arguments) e writes to stdout, so to edit a file you must direct e to it using the shell > operator. Part of my goal in writing e was to distil the concept of a text editor down to its bare minimum, where removing any functionality would change the fundamental nature of the software. Because of the heavy reliance on UNIX system APIs, e will only compile and run on UNIX and UNIX-like systems.


Installation Instructions
=

    make


Usage Instructions
=

    e > filename.ext


License
=

Copyright (C) 2012-2013  Peter Sussman

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as
published by the Free Software Foundation, either version 3 of the
License, or (at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

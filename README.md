DCSDCHK
-------

Dreamcast disc image utility that checks, converts and renames DCSDRIP dumps.

 - Identifies TOSEC and Redump databases matching entries
 - Compares hashes then validates dumps integrity
 - Restores pregaps with offset correction
 - Archives converted tracks and generated cue to zip

Works on any GNU/Linux x86-64 with Bash and on Windows WSL.

Setup
-----

Execute 'build'.

Download and rename the Dreamcast .dat files to 'redump.dat' 'tosec-j.dat' 'tosec-u.dat' 'tosec-e.dat'
then put them into the 'db' directory.

 * Redump : http://redump.org/downloads
 * TOSEC : https://www.tosecdev.org/downloads

Download and put 'edcre' into the 'sp' directory.

 * EDCRE : https://github.com/alex-free/edcre

Usage
-----

 1. Copy every dump file to the 'gd' directory
 2. Open a terminal and execute 'check'

Option : --zip

Note : the provided DCSDRIP dump should be complete and remain untouched.

Source
------

https://github.com/jonblau/dcsdchk

License
-------

 SPDX-License-Identifier: GPL-3.0-or-later

 DCSDCHK

 Copyright (C) 2024 Jon Blau

 This program is free software: you can redistribute it and/or modify
  it under the terms of the GNU General Public License as published by
  the Free Software Foundation, either version 3 of the License, or
  (at your option) any later version.

 This program is distributed in the hope that it will be useful,
  but WITHOUT ANY WARRANTY; without even the implied warranty of
  MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
  GNU General Public License for more details.

 You should have received a copy of the GNU General Public License
  along with this program.  If not, see <https://www.gnu.org/licenses/>.

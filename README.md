cbundle is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

cbundle is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with cbundle. If not, see <http://www.gnu.org/licenses/>.


cbundle
============================
cbundle is a simple tool to generate Mercurial bundles easily.

Author
----------------------------
Alejandro El Informático

Requirements
----------------------------
UNIX system

Configuration
----------------------------
There is no pre-determined configuration.

Installation
----------------------------
There is no installation option but if you want to use cbundle "anywhere" copy it to your binaries path.

Usage
----------------------------
`cbundle [project_name] [branch 1] ... [branch N] [revision] [all-your-comments-separated-with-dashes]`

_tip:_ revision may be `null`

Output
----------------------------
_example:_

    $cbundle extractor trunk 2 fix-all-bugs
    extractor.trunk.2.abcd12345678.fix-all-bugs

    $cbundle extractor js demo trunk null full
    extractor.js.demo.trunk.full

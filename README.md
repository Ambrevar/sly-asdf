 [![License: GPL v3](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0)     [![MELPA](http://melpa.org/packages/sly-asdf-badge.svg)](http://melpa.org/#/sly-asdf)
 
 ## Sly-asdf

SLY contrib that adds support for editing ASDF systems. 

Ported from [slime](https://github.com/slime/slime/blob/master/contrib/slime-asdf.el) with changes to support [`package-inferred-system`](https://common-lisp.net/project/asdf/asdf/The-package_002dinferred_002dsystem-extension.html). Potentially I'd like to make some future changes to improve debugging ASDF systems (e.g., cut off stack trace at system boundaries, etc.)

## Installation 
Now available from MELPA

Installing manually will require the contrib be registered in SLY's `sly-contrib` variable. 
```
(add-to-list 'sly-contribs 'sly-asdf 'append)
```

..
   SPDX-License-Identifier: AGPL-3.0-or-later

   ----------------------------------------------------------------------
   Copyright © 2024, 2025  Pellegrino Prevete

   All rights reserved
   ----------------------------------------------------------------------

   This program is free software: you can redistribute it and/or modify
   it under the terms of the GNU Affero General Public License as published by
   the Free Software Foundation, either version 3 of the License, or
   (at your option) any later version.

   This program is distributed in the hope that it will be useful,
   but WITHOUT ANY WARRANTY; without even the implied warranty of
   MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
   GNU Affero General Public License for more details.

   You should have received a copy of the GNU Affero General Public License
   along with this program.  If not, see <https://www.gnu.org/licenses/>.


=========================
ucantellme
=========================

-----------------------------------------------------------------------------
Passphrase insertion tool
-----------------------------------------------------------------------------
:Version: ucantellme |version|
:Manual section: 1

Synopsis
========

ucantellme *[options]* *out-name* (*key*)


Description
===========

Retrieves the OpenPGP keys uniquely
associated to an external owner account (EOA)
published on the Ethereum Virtual Machine (EVM)
networks OpenPGP Key Server.


Networks
=========
All those supported by
'evm-chains-info' as
well as direct RPC addresses.


Options
========

-m out_type             Output type (file, variable)
-x prompt_command       Passphrase prompt command (zenity, systemd, simple)
-d display_message      Message to display
-t input_timeout        Input timeout.

-h                      Displays help.
-v                      Enable verbose output


Bugs
====

https://github.com/themartiancompany/ucantellme/-/issues

Copyright
=========

Copyright Pellegrino Prevete. AGPL-3.0.

See also
========

* key-gen
* mkimg

.. include:: variables.rst

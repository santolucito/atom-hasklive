# Hasklive for Atom

This will be an way to do live coding in haskell. The editor should look like this. See bret viktor's demos in  'inventing on principle' for examples of this.


=======================
|          |          | 
|   INPUT  |  OUPUT   |
|          |          |
-----------------------
|                     |
|                     |
|        CODE         | 
|                     |
|                     |
=======================

## Setup

We are using [atom-tidal](https://github.com/seansay/atom-tidal), an existing atom extension, as a starting point.
We want to get rid of all tidal and dirt dependencies. The code of key interest to us is in the 'lib' directory. To test the current version you need the following instructions.

1. [Install Tidal](https://github.com/tidalcycles/Tidal/blob/master/doc/tidal.md#installation)

2. Install `tidal` package in `atom` editor

3. The default `ghci` path is in `/usr/local/bin/ghci`, you can change this in the package setting view.

4. running `dirt`

5. Open a `.tidal` file, and select `Boot` in the submenu `Tidal`

6. Then, you can:

  * `shift+enter` to evaluate current line or selection

  * `cmd+enter` to evaluate multi-lines or selection

  You can customize if you want, see [atom's doc](https://atom.io/docs/latest/customizing-atom#)

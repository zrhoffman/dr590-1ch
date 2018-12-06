BlackVue DR590-1CH Configuration
================================

Setup
-----

The microSDHC card should be formatted FAT32 (even if its capacity is larger
than 32GB). Capacities up to 128GB have been tested.

Clone the repo as a directory named BlackVue at the root directory of the card.
If you have an existing BlackVue directory, you can place the `.git` directory
inside that directory. Recordings, version info (/Config/version.bin), and
firmware upgrade files (in /System) are ignored.

Changing the configuration
--------------------------

The options in `config.ini` lack proper documentation. If unsure of what to
change, BlackVue's SD Card Viewer software can manipulate the config and you can
simply track the changes to the file.

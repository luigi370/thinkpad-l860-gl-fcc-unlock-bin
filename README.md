# thinkpad-l860-gl-fcc-unlock-bin

After trying to install the AUR package and getting the error:

`==> Starting prepare()...
tar: lenovo-wwan-unlock_ver2.1.tar.gz: Cannot open: No such file or directory
tar: Error is not recoverable: exiting now
==> ERROR: A failure occurred in prepare().
    Aborting...`

I added a missing line in the PKGBUILD:

`bsdtar -xvf n3xwp04w.zip`

So to use this version:

`git clone git@github.com:luigi370/thinkpad-l860-gl-fcc-unlock-bin.git`

`cd thinkpad-l860-gl-fcc-unlock-bin`

`makepkg -si`
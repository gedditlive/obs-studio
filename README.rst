Geddit Studio
===================================

Forked from OBS Studio <https://obsproject.com>

Origin: https://github.com/obsproject/obs-studio

Installing
-------------------

  Clone this git repository.
  ```git clone https://github.com/gedditlive/geddit-studio.git```

  Update the submodules.
  ```git submodule update --init --recursive```

  Use homebrew to install FFmpeg, x264, Qt5, cmake, mbedtls and swig.

Building
-------------------

  On Mac OS, remember to set this environment variable before building.
  ```export QTDIR=/usr/local/opt/qt```

  Create a 'build' directory, then change directory into the 'build' dir.

  Run the command ```cmake .. && make```

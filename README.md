heroku-buildpack-cmake
======================

A Heroku buildpack that simply installs the CMake tools without detecting nor reading `CMakeLists.txt`.

Usage
-----

Simply add this Git repo to your `.buildpacks` file and set your Heroku config var `BUILDPACK_URL` to `https://github.com/mojodna/heroku-buildpack-multi.git#build-env`.

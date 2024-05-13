# mod_vad

a voice activity detection module for freeswitch.

just put the module directory under the folder freeswitch-xx.xx.xx/src/mod/application/ and make!

```sh
# using freeswitch packages
apt update ; apt install libfreeswitch-dev libfreeswitch1 libfreeswitch1-dbg
cd mod_vad
mkdir build
cd build
cmake -DCMAKE_BUILD_TYPE=Release ..
make -j
make install
```

# crystal-multi-tool.coot

This role is in development.

A [Crystal-Multi-Tool](#) Ansible role to install the [Coot](https://www2.mrc-lmb.cam.ac.uk/personal/pemsley/coot/) (**C**rystallographic **O**bject-**O**riented **T**oolkit) suite.

This role installs the Enterprise Linux (rhel) [Coot Binaries](https://www2.mrc-lmb.cam.ac.uk/Personal/pemsley/coot/devel/build-info.html)

## NOTE

This role does not install drivers for graphical hardware acceleration. Coot's graphics will run slowly because of this. Install drivers specific to your hardware when using this role. The future crystal-multi-tool.os role will address this issue.

## TODO

Create alternative to install Coot from source.
  - [github](https://github.com/pemsley/coot)

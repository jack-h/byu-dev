Template resource estimation models for an 8-input, 32k channel PFB design.

To open/modify/compile:

1. Clone this repository
2. Clone submodules:
```
git submodule init
git submodule update
```
3. Create a local environment specification file `startsg.local`. See `startsg.local.2018` for a template.
4. From the top level of this repository, run `startsg` (if your environment file is called `startsg.local`) or `startsg <my_local_environment_paths>.local`.

5. After opening `byu.slx` you can compile the design by running `jasper` from the MATLAB prompt.

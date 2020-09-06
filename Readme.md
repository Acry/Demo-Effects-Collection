# Demo Effect Collection

Fork from <http://demo-effects.sourceforge.net/>

**Do not have spaces in directory names!**

## Currently working

Fixed building for SDL 1 based demos.

## Building
`./configure` - to build without the equalizer demo  
`./configure --enable-mikmod`  

`make -j$(nproc) CXXFLAGS="-fpermissive"` - builds all,  
but OpenGL demos are currently not working.

## not building

xhacks: eruption and metaballs

## Crashing

- demon
- demons
- raytracer
- terrain
- ufos

## Bugged

- plasmacube

## unkown state

- tunnel (do not know if it renders correctly)

## Deps

- Using SDL 1, SDL_image (1)
- Mikmod (optional)

- OPENGL
- OPCODE was used for 3D frustum culling and 3D collision detection.

The Demo Effects Collection is licensed under the GPL.

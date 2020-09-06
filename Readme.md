# Demo Effect Collection

Fork from <http://demo-effects.sourceforge.net/>

**Do not have spaces in directory names!**

## Building
`./configure` - to build without the equalizer demo  
`./configure --enable-mikmod`  

`make -j$(nproc) - builds all,  

## not building

xhacks: eruption and metaballs

## Crashing

- raytracer on raytrace

## Bugged

- demon
- demons
- plasmacube
- terrain
- ufos

I had to disable collision checking in `WPCG/WP_ObjectManager.C` I doubt that `libopcode` works at all;

## unkown state

- tunnel (do not know if it renders correctly)  
but lightning looks strange in all OpenGL demos.

## Deps

- Using SDL 1, SDL_image (1)
- Mikmod (optional)

- OPENGL
- OPCODE was used for 3D frustum culling and 3D collision detection.

## License

The Demo Effects Collection is licensed under the GPL.

## Issues

**fixed:**  
warning: extra qualification
https://www.eso.org/sdd/bin/view/SDDPublic/Gcc4Warnings#warning_extra_qualification_XXX

**fixed:**
ARFLAGS = crUu
https://bugzilla.redhat.com/show_bug.cgi?id=1155273#c1


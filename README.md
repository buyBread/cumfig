### cumfig
a team fortress 2 config   
   
### sources:
* [mastercoms' mastercomfig](https://github.com/mastercoms/mastercomfig)   
* [valve developer community](https://developer.valvesoftware.com/wiki/Main_Page)   
   
### benchmarks
**hardware**: ubuntu 18.04, gtx 1050 ti (430.50), 16gb of ram, i7-8750h  
**note**: these aren't exact averages, just numbers that i saw the framerate be around at in normal gameplay sessions, also since opengl performs better than directx expect to see slightly lower framerates on windows   
- **performance** preset: `~300` fps   
- **default** config preset: `~240` fps   
- **quality** preset: `~150` fps   
   
you can find presets in the `main.cfg` file located in `cfg/cumfig/`   
   
### launch options
`-novid -reuse -softparticlesdefaultoff -gl_enablesamplerobjects`   
   
`-novid` - doesn't play the valve intro   
`-reuse` - reuse network sockets   
`-softparticlesdefaultoff` - sets particles to be rendered without feathering (scene depth blending) by default   
`-gl_enablesamplerobjects` - (linux) use opengl sampler objects for better texture preloading   
   
##### -dxlevel
`81` - for weak hardware (might crash sometimes)    
`90` - shader model 2   
`92` - (opengl) partial shader model 3   
`95` - most stable option   
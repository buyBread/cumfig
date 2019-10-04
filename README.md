### cumfig
a team fortress 2 config  

### sources:
* [mastercoms' mastercomfig](https://github.com/mastercoms/mastercomfig)  
* [valve developer community](https://developer.valvesoftware.com/wiki/Main_Page)  
  
### features
* there aren't really any unique features that stand out here..
* i guess it's a bit more approachable than mastercomfig?

### benchmarks
hardware: ubuntu 18.04, gtx 1050 ti (430.50), 16gb of ram, i7-8750h  
note: these aren't exact averages, just numbers that i saw the framerate be around at in normal gameplay sessions, also since opengl performs better than directx expect to see slightly lower framerates on windows    
- **performance** preset: `~300` fps  
- **default** config preset: `~240` fps  
- **quality** preset: `~160` fps  
  
[more on presets here](https://github.com/buyBread/cumfig/wiki/presets)  
  
### launch options
`-novid -high -reuse -softparticlesdefaultoff -gl_enablesamplerobjects`  
  
`-high` - sets the game's priority to high  
`-reuse` - reuse network sockets  
`-softparticlesdefaultoff` - sets particles to be rendered without feathering (scene depth blending) by default   
`-gl_enablesamplerobjects` - (linux) use opengl sampler objects for better texture preloading   
  
##### -dxlevel
`81` - for weak hardware (might crash sometimes)    
`95` - most stable option  
other versions might cause graphical issues or, in some cases, even crash the game.
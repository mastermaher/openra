openra
======

openRA - Installation failed - SDL.dll missing

Hi

Massive RA fan, only just found out about open RA!!

tried all morning to install, cannot get past installer, tried many times with different versions from the website.

it gets to about 75% then stops installing and says
installation aborted

exception log below:
Exception of type `System.DllNotFoundException`: Unable to load DLL 'SDL.dll': The specified module could not be found. (Exception from HRESULT: 0x8007007E)
TypeName=``
at Tao.Sdl.Sdl.__SDL_Init(Int32 flags)
at Tao.Sdl.Sdl.SDL_Init(Int32 flags)
at OpenRA.Renderer.SdlCommon.SdlGraphics.InitializeSdlGl(Size& size, WindowMode window, String[] requiredExtensions)
at OpenRA.Renderer.Glsl.GraphicsDevice..ctor(Size size, WindowMode window)
at OpenRA.Renderer.Glsl.DeviceFactory.Create(Size size, WindowMode windowMode)
at OpenRA.Graphics.Renderer.CreateDevice(Assembly rendererDll, Int32 width, Int32 height, WindowMode window)
at OpenRA.Graphics.Renderer.Initialize(WindowMode windowMode)
at OpenRA.Game.Initialize(Arguments args)
at OpenRA.Program.Run(String[] args)
at OpenRA.Program.Main(String[] args)



I am running running win 7 64 bit.
i have deactivated anti virus and also if i search my computer i can also find the DLL it mentions so really stuck now...

please help

Mike
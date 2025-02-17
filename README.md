# IF-Animation-Workflows
This are a series of ComfyUI workflows that work together to create and repurpose animation
                                   
--------------------------------------------------------

to watch tutorials
https://www.youtube.com/@impactframes

Blogs/support
https://ko-fi.com/impactframes

github 
https://github.com/if-ai/IF-Animation-Workflows

--------------------------------------------------------
This are a series of workflows that work together to create and repurpose animation 

|[CD_FLUX_LORA](workflows/Flux_LoRA.json.json)|[![Try CD_FLUX_LORA](https://beta.app.comfydeploy.com/button)](https://beta.app.comfydeploy.com/home?nodes=cubiq%2FComfyUI_essentials%4033ff89f&workflowLink=https%3A%2F%2Fgithub.com%2Fif-ai%2FIF-Animation-Workflows%2Fblob%2Fmain%2FFlux_LoRA.json&comfyui_version=a7fe0a94dee08754f97b0171e15c1f2271aa37be)|

IF_Animator (Main workflow )
IF_KeyAnimation_Helper (has a lite and SMPL version is workflow to extract keys redraw them on a external app)
IF_Inbetweeners (You can select a few frames create the inbetween)

Bring your animation you want to use as base on the source Load video 

I like to prep my image to a square format and set the FPS beforehand in Premiere pro or Blender. 

Anime and animation in general works at 12FPS but even 8 is enough the VFI nodes can interpolate or you can use a program called flowframes.

Animated diff works on chunks of 8Frames 2Second length Animation we don't need to be limited by that but is a good consideration, the best scenario is to work at 8FPS for a length of 2 seconds 16frames or the second best are multiples of 8, 16,24,32,48

The target is the character we want to transfer the animation to.

We could use the key animation helper to extract the keyframes round trip processed frames on an external app like TV paint, Krita etc then use this workflow to get better consistency draw frames.

You could even create your own 3 keyframes from scratch and use the IF_Inbetweeners WF to get some original animation with in-betweens you could also extract some keyframes from an animation with the IF_Animation_Helper 

Anyone is welcome to contribute to this workflow for the enjoyment of the animation and ai enthusiast community, Also if I make any mistake on my explanations please correct me I am learning too.

Thanks.
ImpactFrames
If I miss a repo please let me know an I will add it here

https://github.com/jojkaart/ComfyUI-sampler-lcm-alternative/tree/main

https://github.com/comfyanonymous/ComfyUI_experiments

https://github.com/Fannovel16/ComfyUI-MotionDiff

https://github.com/Fannovel16/ComfyUI-Frame-Interpolation

https://github.com/cubiq/ComfyUI_IPAdapter_plus

https://github.com/Kosinkadink/ComfyUI-Advanced-ControlNet

https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved

https://github.com/if-ai/ComfyUI-Iterative-Mixer

https://github.com/Kosinkadink/ComfyUI-VideoHelperSuite

https://github.com/peteromallet/Steerable-Motion

https://github.com/FizzleDorf/ComfyUI_FizzNodes

https://github.com/shadowcz007/comfyui-mixlab-nodes/tree/main

Special AD motion controlnet Model
https://huggingface.co/crishhh/animatediff_controlnet/tree/main

Special thanks to thanks to Kijai, banodoco discord, Elriel, LCM discord.

    


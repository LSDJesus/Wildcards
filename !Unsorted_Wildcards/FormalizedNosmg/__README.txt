These wildcards were made to be used with autismmixSDXL_autismmixDPO.safetensors, the vast majority of the prompts will not work in other models.

It is also meant to be used with Hako's NegPiP for setting negative weights. Again, many of the prompts will not work otherwise.

You can get it from https://github.com/hako-mikan/sd-webui-negpip, and I believe it also shows up on the default extension list for Automatic1111 and Forge


FAQ


* What do these prompts contain?


A lot, and despite my best efforts it is kind of disorganized. These are a random assortment of accumulated prompts of various themes. I separated them into folders, but here is the rundown;


The THREE MAIN FILES on this pack are TR_AllCharacters, TR_NSFWPrompts, TR_BadEnds and TR_SFWPrompts, located at the root folder. AllCharacters gives you characters, the other two puts those characters into situations. You may of course describe your own characters if you want, or write your own situation for the characters.

TR_BadEnds is basically NSFW but for heavier stuff, not full on guro but clearly the characters involved are not having fun.


If in doubt, just write what character you want to see, and call either the SFW or NSFW files, like "Ruby Rose __TR_NSFW_Prompts__"


As for the folders, they also countain prompts you can call, but aren't the main focus; here's a rundown:

NSFW -> Countains Prompts that are NSFW. Sex and sex adjacent stuff. The prompts inside these aren't actually meant to be called directly, they are just there to be called from inside the 'TR_NSFWPrompts' file, but you're free to use them as well.

SFW -> Same as NSFW, but without the sex

Backgrounds -> Self explanatory, some backgrounds. It's honestly lacking compared to everything else. Inside you'll find "Indoors" and "Outdoor" locations, also TR_LocDetails. Ignore that last one

Characters -> A list of over 850 female characters from popular media that are baked into Autismmix (meaning, they require no lora). They are separated by company and series name, but if you want to just spin the wheel then call __TR_AllCharacters__ which countains all of them.

Characters\MALES -> A list of male characters baked into Autismmix. Very lacking compared to the feminine list.

Other -> Do not bother with this folder, it's just snippets of prompt I used in wildcards to be called from others prompts.

Outfits -> Various outfits of various themes, separated into SFW and NSFW versions. I tried to make variations within each of them (sometimes armor has shoulderpads, sometimes not, sometimes shirts have cleavage, sometimes not, that kind of stuff)

Styles -> Various styles, divided in general (art nouveau, etc), 3D (pixar, blender, etc), Artists (popular rule 34 artists baked in) and Media (Akira Toriyama style, etc)

Transformations -> Call these to transform your character into something. The prompt "Yang Xiao Long __TR_Tra_CatGirl__" for example makes Yang into a catgirl



* All my images are ugly!

Have you added "score_9, score_8, score_7_up, score_6_up, score_5_up" to the prompt? The way Autismmix and other Pony based modes are trained, those words are required to make the images look good. Think of them as the model's version of writing 'beautiful, 4k, amazing artwork, detailed'



* Some of my images are burned

Try changing the Emphasis Mode setting to 'No Norm'. It is located into Settings -> Stable Diffusion -> Emphasis Mode



* I notice there aren't loli characters in AllCharacters

Yeah it's not really my thing. Honestly some of the characters on the list are already too young looking for me to be fully confortable and I added them just for the sake of completionism



* The images sometimes look weird if I call transformations and clothes at the same time

It's unfortunately a limitation of image generation software; if you add too many prompts they start fighting each other for attention. So if you call a clothe prompt that inclused 'headphones' and a transformation that includes 'pointy ears', it'll try to make the headphones pointy, or make the ears appear over the headphones.
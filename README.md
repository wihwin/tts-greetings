# tts-greetings
Various Text-To-Speech (TTS) compilation/recipies for using with Apple OSX voices and speech synthesis engine.

Apple OSX comes with a bunch of premium voices and the voice generation engine that allows to generate high quality wav files suitable for Interactive Voice Response (IVR) application, for example FreeSwitch IVR.

The simpliest way to convert text to speech that can be used in IVR applications is by utilising Apple native utility - say. The utility comes with few special switches that allow fine tune the voice output. For example \[\[slnc 50\]\] will pause the speech for 50ms, \[\[emph +\]\] will add the emphasis to the next word, and so on.

say -v Lee --quality=127 --bit-rate=8000 --rate=40 "Welcome to \[\[emph +; pbas -1;pmod -1\]\] Company \[\[emph -\]\] Name, \[\[emph +\]\] Your \[\[emph -\]\] Local Agency."

This repository is set of compilations for various phrases that can be utilised in building custom IRV menus.

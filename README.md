# Allegro-txt2vid-pinokio
A Pinokio Install Script for the [Rhymes Allegro](https://github.com/rhymes-ai/Allegro) text-to-video model.

## Sources
* Installs a Pinokio fork: https://github.com/ai-anchorite/Allegro-txt2vid
* Gradio UI and associated code borrowed from: https://huggingface.co/spaces/fffiloni/allegro-text2video

## Important Notes
* Takes an hour to generate a result. 1 hour. hopefully will be optimized, but yeah. 1 hour (on a 3090). 
* My GPU warms me at night. 
* 12GB VRAM should be sufficient though. (1 hour. txt2video so mostly luck as to what you get at the end).
* After the inference Steps have completed, there's a vae decode phase that can take quite a while. So don't panic and stop it prematurely!
* I can't stop clicking the go button..

* Img2vid is in the works apparently: https://github.com/rhymes-ai/Allegro/issues/8
* Yes, it's not (yet) optimized for consumer GPUs: https://github.com/rhymes-ai/Allegro/issues/20
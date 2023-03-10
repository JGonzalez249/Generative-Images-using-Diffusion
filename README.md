# Generative-Images-using-Diffusion
3 sets of 3 images using generative AI with different styles of art

Used this notebook: https://colab.research.google.com/github/sagiodev/stablediffusion_webui/blob/master/StableDiffusionUI_ngrok_sagiodev.ipynb?authuser=1#scrollTo=gJBtadxGOK7b

Using this notebook, I used the v1.5 inpainting model to generate images via promtps, then using those generated images, I just added the styles I wanted (including Artist), changed various settings and used different sampling models to generate a certain style for the same image. You can see the original image that was generated and the results of using different styles below. 

# First Batch

    Original Image

        Used Standard Settings

        Positive Prompt: A woman in futuristic armor,a crowd in the foreground,walking in a cyberpunk city,at night,in the rain

        Negative Prompt: low quality,blurry, duplicate people,helmet

![Original](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/00000-613250346-A%20woman%20in%20fut.png)

    Anime/Realistic

        Settings: Steps: 40, Sampler: DPM++ 2S a Karras, CFG scale: 7, Seed: 326607768, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.75, Conditional mask weight: 1.0, Mask blur: 4

![Anime/Realistc](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/futureWomanAnime.png)

    Picasso

        Settings: Steps: 25, Sampler: Euler a, CFG scale: 15, Seed: 3961209117, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.75, Conditional mask weight: 1.0, Mask blur: 4

![Picasso](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/futureWomanPicasso.png)

    Pollock

        Settings: Steps: 35, Sampler: Euler a, CFG scale: 10, Seed: 2245521335, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.8, Conditional mask weight: 1.0, Mask blur: 4

![Pollock](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/futureWomanPollock.png)

# Second Batch

    Original Image

        Used Standard Settings

        Positive Prompt: Space, planets in the background, shooting stars, space ships around planet, dark

        Negative Prompt: blurry, low quality, bright

![Original](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/spaceOriginal.png)

    90's Anime

        Settings: Steps: 25, Sampler: Euler a, CFG scale: 1.5, Seed: 2846331361, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.75, Conditional mask weight: 1.0, Mask blur: 4


![90's Anime](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/spaceAnime.png)

    Post-Impressionism/Vincent von Gogh

        Settings: Steps: 25, Sampler: Euler a, CFG scale: 15, Seed: 4238743229, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.75, Conditional mask weight: 1.0, Mask blur: 4

![Post-Impressionism](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/spacePostImpress.png)

    Pop Art/Andy Warhol

        Settings: Steps: 40, Sampler: Euler a, CFG scale: 25, Seed: 8622219, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.5, Conditional mask weight: 1.0, Mask blur: 4

![Pop Art](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/spacePop.png)

# Third Batch

    Original

        Settings: Steps: 40, Sampler: Euler a, CFG scale: 3, Seed: 2364453493, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Conditional mask weight: 1.0

        Positive Prompt: race cars, in the street, in the city, people on the sidelines, at night, zoomed out, speed lines, smoke, realistic

        Negative Prompt: blurry, low quality, duplicate cars, people on the street, flags, barriers, black and white, illustrated

![Original](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/raceCarOriginal.png)


    Street Art

        Settings: Steps: 50, Sampler: DPM++ SDE, CFG scale: 10.5, Seed: 1399911285, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.65, Conditional mask weight: 1.0, Mask blur: 4

![Street Art](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/raceCarStreet.png)


    Neo-Expressionsim/Jean-Michel Basquiat

        Settings: Steps: 30, Sampler: Euler a, CFG scale: 14, Seed: 1399911285, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.6, Conditional mask weight: 1.0, Mask blur: 4

![Neo-Expressionsim](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/raceCarNeoEx.png)

    Art Nouveau

        Settings: Steps: 25, Sampler: Euler a, CFG scale: 19, Seed: 1399911285, Size: 512x512, Model hash: c6bbc15e32, Model: sd-v1-5-inpainting, Denoising strength: 0.5, Conditional mask weight: 1.0, Mask blur: 4

![Art Nouveau](https://github.com/JGonzalez249/Generative-Images-using-Diffusion/blob/master/img/raceCarNou.png)







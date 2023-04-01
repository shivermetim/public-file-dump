# Contents
- [Perameters](#perameters)
  * [Basic Parameters](#basic-parameters)
  * [Model Version Parameters](#model-version-parameters)
  * [Upscaler Parameters](#upscaler-parameters)
  * [Other Parameters](#other-parameters)
- [Control Phrases](#control-phrases)
- [Commands](#commands)
- [Settings](#settings)
  * [Versions](#versions)
  * [Quality](#quality)
  * [Style](#style)
  * [Other](#other)
- [Useful Websites for Prompt Building](#useful-websites-for-prompt-building)

---

## Perameters
### Basic Parameters
* `--aspect` or `--ar:` Change the aspect ratio of a generation. Eg: `--ar 2:3`
  * `--ar 1:1` Default aspect ratio.
  * `--ar 5:4` Common frame and print ratio.
  * `--ar 3:2` Common in print photography.
  * `--ar 7:4` Close to HD TV screens and smartphone screens.
* `--chaos <number 0–100>`: Change how varied the results will be. Higher values produce more unusual and unexpected generations.
* `--no:` Negative prompting, remove plants from the image.
* `--quality <.25, .5, 1, or 2>` or `--q <.25, .5, 1, or 2>`: How much rendering quality time you want to spend. The default value is 1. Higher values cost more and lower values cost less.
* `--seed <integer between 0–4294967295>`: The Midjourney bot uses a seed number to create a field of visual noise, like television static, as a starting point to generate the initial image grids. Seed numbers are generated randomly for each image but can be specified with the `--seed` or `--sameseed` parameter. Using the same seed number and prompt will produce similar ending images.
* `--stop <integer between 10–100>`: Use the `--stop` parameter to finish a Job partway through the process. Stopping a Job at an earlier percentage can create blurrier, less detailed results.
* `--style <4a, 4b or 4c>`: Switch between versions of the Midjourney Model Version 4
* `--stylize <number>` or `--s <number>`: Parameter influences how strongly Midjourney’s default aesthetic style is applied to Jobs.
* `--uplight`: Use an alternative “light” upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image is less detailed and smoother.
* `--upbeta`: Use an alternative beta upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image has significantly fewer added details.
### Model Version Parameters
* `--niji`: An alternative model focused on anime style images.
* `--hd`: Use an early alternative Model that produces larger, less consistent images. This algorithm may be suitable for abstract and landscape images.
* `--test`: Use the Midjourney special test model.
* `--testp`: Use the Midjourney special photography-focused test model.
* `--version <1, 2, or 3>` or `--v <1 2, or 3>`: Use an earlier version of the Midjourney algorithm. The current algorithm (V4) is the default setting.
### Upscaler Parameters
* `--uplight`: Use an alternative “light” upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image is less detailed and smoother.
* `--upbeta`: Use an alternative beta upscaler when selecting the U buttons. The results are closer to the original grid image. The upscaled image has significantly fewer added details.
* `--upanime`: Use an alternative upscaler trained to work with the `--niji` Midjourney Model.
### Other Parameters
* `--creative`: Modify the test and testp models to be more varied and creative.
* `--iw`: Sets image prompt weight relative to text weight. The default value is `--iw 0.25`.
* `--sameseed`: Seed values create a single large random noise field applied across all images in the initial grid. When `--sameseed` is specified, all images

## Control Phrases
* `fine ultra-detailed realistic` - Can be a bit grainy and "ropey" but increases detail generation
* `ultra photorealistic` - Simiar to `fine ultra-detailed realistic`
* `Hasselblad H6D` - Sharper focus on subect; shadows are deepened
* `high definition` - Shadows are lightened; more fanciful and saturated colors
* `8k` - Lighting tends to be more extreme; colors even more saturated and computer-generated looking than "high definition"
* `cinematic` - Shadows tend to be more extreme (though not darker); objects a bit thicker; more poster-like
* `color grading` - Extreme variations in hue; vibrant but not over-saturated colors
* `depth of field` - sharp focus on subject, background and foreground blurred
* `film lighting` - Limited lighting sources; backlighting common; deep shadows cast by light sources
* `rim lighting` - Slighting stronger lighting effect than "film lighting," but very similar results
* `intricate` - Tends toward non-realistic "crafts" and "pattern" type designs.
* `realism` - Aristic realism. Backgrounds tend to be more uniform; subject looks more like a painting; more objects with subject
* `photography` - Subject tends to have a little area of objects around it with little else in the background
* `rendered for IMAX` - More complex subject with very directional lighting and subdued saturation
* `tilt-shift` - Like `depth of field,` but from above or with high angle
* `motion-blur` - Speed lines. May render as if wind is blowing
* `35mm film` - More vibrant colors, but muted saturation, detailed with additional foreground and/or background elements
* `soft focus` - Slight blurry focus and thiner subject with lots of potentially grainy detail; colors tend toward pastels
* `harsh lighting` - Extreme contrast with dark shadows
* `minimalist line art` - Very simplified pen-on-paper type line sketch of the subject with few or no additional elements†
* `Hasselblad full frame` - Similar to "35mm film" with more emphasis on strong contrast.

## Commands
* `/ask` - Get an answer to a question.
* `/blend` - Easily blend two images together.
* `/daily_theme` - Toggle notification pings for the #daily-theme channel update
* `/docs` - Use in the official Midjourney Discord server to quickly generate a link to topics covered in this user guide!
* `/faq` - Use in the official Midjourney Discord server to quickly generate a link to popual prompt craft channel FAQs.
* `/fast` - Switch to Fast mode.
* `/help` - Shows helpful basic information and tips about the Midjourney Bot.
* `/imagine` - Generate an image using a prompt
* `/info` - View information about your account and any queued or running jobs.
* `/stealth` - For Pro Plan Subscribers: switch to Stealth Mode
* `/public` - For Pro Plan Subscribers: switch to Public Mode
* `/subscribe` - Generate a personal link for a user's account page.
* `/settings` - View and adjust the Midjourney Bot's settings
* `/prefer option` - Create or manage a custom option.
* `/prefer option list` - View your current custom options.
* `/prefer suffix` - Specify a suffix to add to the end of every prompt.
* `/show` - Use an images Job ID to regenerate the Job within Discord.
* `/relax` - Switch to Relax mode.
* `/remix` - Toggle Remix mode.

## Settings
### Versions
Sets the Model Versions used for jobs.
* 1️⃣ MJ Version 1 
* 2️⃣ MJ Version 2 
* 3️⃣ MJ Version 3 
* 4️⃣ MJ Version 4 [default]
* 5️⃣ MJ Version 5
* 🌈 Niji Mode [for weebs]
* 🤖 MJ Test [--test]
* 📷 MJ Test Photo [--testp]
### Quality
Sets the Quality Parameter used for jobs.
* 🔥 Half Quality 
* 🔥 Base Quality 
* 🔥 High Quality (2x cost)
### Style
Sets the Stylize Parameter used for jobs.
* 🖌️ Style Low 
* 🖌️ Style Med 
* 🖌️ Style High 
* 🖌️ Style Very High
### Other
* 🧍‍♂️ Public 
* 🕵️ Stealth
* 🎛️ Remix
* 🐇 Fast 
* 🐢 Relax

## Useful Websites for Prompt Building
* [IMI Prompt](https://www.imiprompt.com/)
* [DSNR](discord.gg/SkXXZABWfe) A discord bot that walks through the process of creating an elaborate prompt
* [MidJourney Prompt Tool](https://prompt.noonshot.com/)

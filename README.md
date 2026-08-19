[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://github.com/chris1111/Icon-Studio/blob/main/LICENSE) [![pages-build-deployment](https://github.com/chris1111/Icon-Studio/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/chris1111/Icon-Studio/actions/workflows/pages/pages-build-deployment)
# Icon-Studio 
### Create your unique icon or avatar with custom shapes, rings, and effects.

## Start using Icon-Studio ➢ [Icon-Studio](https://chris1111.github.io/Icon-Studio/)

## List Update: ⬇︎
<details> 
  <summary>View Update</summary>

### Update 19 Aug 2026 Add Export Padding, Inner Glow & Vignette, UI Optimization

	1	Export Padding: We added a slider in the center column that allows you to shrink the icon and add transparent space around it. We initially tried adding Aspect Ratios (Banners, GitHub, HD) but you decided you only wanted the 1:1 square padding, so we stripped out the rest to keep it clean!
	2	Inner Glow & Vignette: We filled the remaining space in the center column by adding 6 new glow options (White Glow, Dark Vignette, Cyan, Gold, Purple) that radiate beautifully from the center outward.
	3	"UI Optimization" We tightened all the gaps, margins, and padding in the CSS so the entire app fits perfectly onto a 1080p screen without needing to scroll!.
        4	Fixed a bug when using Scale and (Inner Glow & Vignette) together.
-----------------------------------------

### Update 16 Aug 2026 Add Film Grain Effect, Frosted Glass Effect, Low Frosty" Tweak

	1	Film Grain Effect: We added a textured, vintage noise overlay to the "Image Effects" list. It gives the icons a really premium, gritty camera texture.
	2	Frosted Glass Effect: We added a glassmorphism effect (blurs the image slightly and adds a frosty tint) to the "Image Effects" list.
	3	"Low Frosty" Tweak: I just adjusted the Frosted Glass to be much subtler (less blur, lower opacity) so the image is still clearly visible underneath the frost.
-----------------------------------------

### Update 17 Aug 2026 Add Template images.
------------------------------------------
### Update 18 Aug 2026 Fix bug.

	1	100% WYSIWYG (What You See Is What You Get): We completely rebuilt the preview system. The live preview now uses the exact same Canvas API math as the download engine. The border thickness (Thin/Medium/Thick) you see on screen is exactly what you get in the downloaded PNG.
	2	Flawless, Notch-Free Borders: We fixed the ugly jagged corners on the Square, iOS, and Rounded shapes. By using the arcTo method and the evenodd ring-punching logic, the borders are now perfectly clean and smooth.
	3	HiDPI Crispness: We implemented High-Definition rendering so the canvas looks sharp on Retina screens.

</details>

### Here is an example of the choices I made for the image created below.

    1       Loading 1-Puppy from Template
    2       Image Effect = Film Grain
    3       Background = Transparent
    4       Border Shaper = IOS
    5       Icon Color = Metal
    6       Icon Width = Thick
	7       Download = 256px
    ⚙️      Al the others settings default
	
<img src="https://github.com/user-attachments/assets/1693b1cf-bb89-4061-8e40-d17849d4461f" />


-------------------------------------------



### Description of the Icon Studio project

1. Image Upload and Preview
Users can upload their own image via drag-and-drop or file browsing (supports PNG, JPG, ICO, SVG, WebP).
The page provides a large, live preview of the image alongside smaller previews showing how the icon will look at standard smaller sizes (128px, 64px, 40px, 28px).
2. Extensive Customization Options
The page acts as a mini image editing tool, offering various ways to style the icon:

3. Border Shapes: 
Users can change the shape of the icon (Circle, Rounded, Square, iOS style, Hexagon, Diamond, Octagon).
Icon Rings: Users can add a glowing, colored border around the icon. There are 14 color gradients to choose from (Ice, Frost, Aurora, Gold, Crystal, Nebula, Rose, etc.) and 3 width options (Thin, Medium, Thick).
Backgrounds: Users can choose different background colors or gradients to sit behind their image (e.g., Deep Ocean, Void, Indigo Night, or Transparent).
Image Effects & Filters: Users can apply visual overlays (Dark Gradient, Vignette, Inner Shadow) and color filters (Frost, Vintage, Cyberpunk, Magma, Mono, etc.) to give the image a specific aesthetic.
Adjustments: Sliders allow users to fine-tune the image by rotating, scaling, and shifting its position (X/Y axis and Up/Down) to ensure it sits perfectly inside the chosen shape.

4. Preset Management
Save/Load: Users can save their exact combination of customizations as a .json preset file to their computer. They can later load this file back into the tool to instantly apply the same settings to a new image.
5. High-Resolution Exporting
Once the user is happy with their design, they can click download buttons to export the final image as a PNG image.
The tool uses an off-screen HTML5 Canvas to render the final high-quality image, offering exports in 4 specific resolutions: 128x128, 256x256, 512x512, and 1024x1024 pixels.
Summary
In short, Icon-Studio is a client-side design tool meant for creating aesthetically pleasing, perfectly cropped, and stylized profile pictures or app icons without the need for complex software like Photoshop. All processing is done directly in the user's browser using HTML, CSS, and JavaScript.

#### A free easy way for those who have virtually no knowledge of graphic design. they are the perfect tools for creating themes icons sets for OpenCore or Clover ➦ Combined with this tools ➥ [Image Resizer](https://chris1111.github.io/Image-Resizer/) ➥ [Workshop Layered Image-Studio](https://github.com/chris1111/Workshop-Layered-Image-Studio) 


- HTML Page Create with help of [Z-AI](https://z.ai)


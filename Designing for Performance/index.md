#Designing for Performance - Lara Callender Hogan

- Performance is user experience - 2 sec or less loading time expects users
- After 3 seconds 40% will abandon your site
- When we eliminated jank (scroll lag) - better user experience
- "Our industry has not *designed* for performance"
- "Fast page load time build trust in your website"

> Performance + Aesthetics =  User Experience

- Mobile Network 300ms loading average, Desktop Wifi 50ms
- webpagetest.com must have for testing with lower speeds and insights in how your pages load
- Order of loading assets will affect the feel of the site while loading
- The size of requests is important, it should be as small as possible

##Images (the nerdy parts)

- http://httparchive.org/interesting.php

###JPEG
- JPEG's are lossy, bad at high contrast areas
- Lower quality is not bad, but good for image size
- Blurring image can reduce image size
- Cropping image can also reduce image size

###GIF
- Best for animations that can't be replaced with CSS
- Do not use GIF nowadays
- If you want to use them, use dithering for GIF
- Replace not animated GIFs with PNG-8

###PNG
- Best for images with fewer colors
- Recognize horizontal and vertical patterns

###WebP
- Introduced in 2010, both lossless and lossy
- Predicts a value then encodes the difference between the predication and actual value

> Replace simple images with SVG

###SVG
- XML based vector image format
- Inline eliminates a HTTP request
- Removes cache-ability when used inline

###Responsive images
- Use image optimization
- Use Responsive web format

##Fonts
- Only import the font weight you absolutely need
- Only load fonts on larger screens
- Use unneeded characters
- Document subsetting so others can know and, if needed, edit it

##Semantics and repurposability
- Save development time and page load time
- Create repurposable code
- Rename non-semantic elements
- Remove inefficient selectors
- Remove unnecessary elements
- Firefox 3D viewer for insights about 'nested debt'
- Create patterns
- Reduce color usages, font-weights and create consistency in your code

##Tips and Tricks
- Use a mobile-first workflow
- Create a performance budget and goal
- Be deliberate about loading assets like images and fonts
- A/B testing
- Make it easy for non-developers to do performance
- Changing culture is *hard*
- Help people *feel* your sites's performance
- We need to have empathy

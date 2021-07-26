# DefaultWebTheme

## The project
This project was made to provide a simple, nice looking theme for people who are not that experienced with html/css and want a website to create content on.
Check out the [demo](https://default-web-theme.vercel.app/). (I'm too lazy to add images).

## Features
* Mobile Responsive
Enjoy an kind of good looking experience on mobile!
* Dark mode
If your device is in darkmode the site will automatically apply a dark color theme.
* Containers
I originally wanted to have a system were you can easily place text, images etc. where you want, but that turned out to be a little more complex than I thought so I made a container system where you can place 2 items left and right. I will try to make a better system in the future. If you want to know how it works, you can read the documentation (Coming soon).
* Synced navbar and footer
Pure convenience!

## What you need to know
The lines I wrote / the solutions I found aren't the best, but they work for me. Feel free to contribute!

If you open the file locally it may glitch out because of the IFrames. You should use the VS Code extension [LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer).

Also i suggest you use [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/) to deploy it :) 

## Documentation
The docs **will** avaible under [here](docs.dwt.tech-cat.de).

## Lighthouse score on local machine
![Lighthouse Score (95, 70, 100, 100)](https://i.imgur.com/gX0qCHp.png)
Accessiblity is only 70 because:
* The Navbarbar button on mobile is only a FontAwesome icon (not a "discernible" name)
* I have disabled zoom on mobile, feel free to enable that again (simply replace this part ```<meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=0">``` in the head tag with ```<meta name="viewport" content="width=device-width, initial-scale=1.0">```)
* Not a high enough background-foreground contrast, not sure why tho.

## Credits
[css-tricks](https://css-tricks.com/) for fixing the iframe flickering issue
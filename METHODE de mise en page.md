#methode
DONNÉES POUR MISE EN PAGE

/1.4

# Un habitat groupé, locatif, intergénérationnel, solidaire et écologique

*en gras* et **en italique**

## sous titre
### soussous titre

voyez ici [un lien](http://monlien.fr)

aussi ![une image](http://mhotte.github.io/images/uneimage.jpg)

![]({{site.baseurl}}//testimageencore.jpg)


CHANGEMENT DE PAGE
donner dans la rubrique “metadata“ le nom du fichier
par exemple metadata >>> permalink: /ferme/
---

MODIFIER LE SITE À PARTIR DE L'INTERFACE
Cliquer sur l'élément à modifier et faire clic droit : « inspecter »

ces modifications permettent de voir directement l'effet sur la mise en page de site mais elles doivent être inscrites “en dure » dans la feuille de style de prose.io

'''


FORMAT DES IMAGES
72 DPI
800 PX DE LARGE
eviter png

RAJOUTER IMAGES/ avant le nom du fichier image

images/cubeROUGE.jpg

'''

FONTS
GOOGLE FONTS
https://www.google.com/fonts

choisir une font 

cliquer sur “Quick Use“

prendre le lien proposé dans  Add this code to your website:
<link href='https://fonts.googleapis.com/css?family=Nunito' rel='stylesheet' 

rajouter dans le “style“
DANS LAYOUT + DEFAULT : copy the code as the first element in the <head> of your HTML document.

PUIS INTÉGRER DANS LA FEUILLE DE STYLE

 All you need to do is add the font name to your CSS styles. For example:
font-family: 'Nunito', sans-serif;

/**************/
/* BASE RULES */
/**************/

IMPORTANT !! NE PAS CHANGER DANS STYLE : DONNÉES GÉNÉRALES DU SITE
html {
  font-size: 100%;
}

body {
	background: $white;
  font: 14px $helvetica;
  color: $darkGray;
  
}

HIÉRARCHIE
h1 = #
h2 = ##

h3, h4, h5, h6

PARAGRAPHES
p {
  margin: 15px 0;
}

LIENS
a {
  color: $blue;
  text-decoration: none;
	cursor: pointer;
  &:hover, &:active {
    color: $blue;
  }
}

…………………………………………………………………………………………………………
/*********************/
/* LAYOUT / SECTIONS */
/*********************/

IMAGE EN HAUT DE SITE
.site-avatar {
  float: left;
  width: 70px;
  height: 70px;
  margin-right: 15px;

…………………………………………………………………………………………………………
…………………………………………………………………………………………………………
…………………………………………………………………………………………………………

# Jekyll Now

**Jekyll** is a static site generator that's perfect for GitHub hosted blogs ([Jekyll Repository](https://github.com/jekyll/jekyll))

✘ No installing dependancies  
✘ No need to set up local development  
✘ No configuring plugins  
✘ No need to spend time on theming  
✘ More time to code other things ... wait ✓!  

## Questions?

[Open an Issue](https://github.com/barryclark/jekyll-now/issues/new) and let's chat!

## Other forkable themes

You can use the [Quick Start](https://github.com/barryclark/jekyll-now#quick-start) workflow with other themes that are set up to be forked too! Here are some of my favorites:

- [Hyde](https://github.com/poole/hyde) by MDO
- [Lanyon](https://github.com/poole/lanyon) by MDO
- [mojombo.github.io](https://github.com/mojombo/mojombo.github.io) by Tom Preston-Werner
- [Left](https://github.com/holman/left) by Zach Holman
- [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes) by Michael Rose
- [Skinny Bones](https://github.com/mmistakes/skinny-bones-jekyll) by Michael Rose

## Credits

- [Jekyll](https://github.com/jekyll/jekyll) - Thanks to its creators, contributors and maintainers.
- [SVG icons](https://github.com/neilorangepeel/Free-Social-Icons) - Thanks, Neil Orange Peel. They're beautiful.
- [Solarized Light Pygments](https://gist.github.com/edwardhotchkiss/2005058) - Thanks, Edward.
- [Joel Glovier](http://joelglovier.com/writing/) - Great Jekyll articles. I used Joel's feed.xml in this repository.
- [David Furnes](https://github.com/dfurnes), [Jon Uy](https://github.com/jonuy), [Luke Patton](https://github.com/lkpttn) - Thanks for the design/code reviews.
- [Bart Kiers](https://github.com/bkiers), [Florian Simon](https://github.com/vermluh), [Henry Stanley](https://github.com/henryaj), [Hun Jae Lee](https://github.com/hunjaelee), [Javier Cejudo](https://github.com/javiercejudo), [Peter Etelej](https://github.com/etelej), [Ben Abbott](https://github.com/jaminscript), [Ray Nicholus](https://github.com/rnicholus), [Erin Grand](https://github.com/eringrand), [Léo Colombaro](https://github.com/LeoColomb), [Dean Attali](https://github.com/daattali), [Clayton Errington](https://github.com/cjerrington), [Colton Fitzgerald](https://github.com/coltonfitzgerald), [Trace Mayer](https://github.com/sunnankar) - Thanks for your [fantastic contributions](https://github.com/barryclark/jekyll-now/commits/master) to the project!

## Contributing

Issues and Pull Requests are greatly appreciated. If you've never contributed to an open source project before I'm more than happy to walk you through how to create a pull request.

You can start by [opening an issue](https://github.com/barryclark/jekyll-now/issues/new) describing the problem that you're looking to resolve and we'll go from there.

I want to keep Jekyll Now as minimal as possible. Every line of code should be one that's useful to 90% of the people using it. Please bear that in mind when submitting feature requests. If it's not something that most people will use, it probably won't get merged. :guardsman:

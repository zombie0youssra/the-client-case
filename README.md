> _Fork_ deze leertaak en ga aan de slag. Onderstaande outline ga je gedurende deze taak in jouw eigen GitHub omgeving uitwerken. De instructie vind je, zoals altijd, in: [docs/INSTRUCTIONS.md](docs/INSTRUCTIONS.md)


# Contactpagina FDND 

Voor (nieuwe) studenten, colllega's en opdrachtgevers heeft FDND een contactpagina met de contactgegevens zoals een email-adres en telefoonnummer, en een routebeschrijving naar het leslokaal. 

## Beschrijving

<img width="887" alt="FDND contactpagina" src="https://user-images.githubusercontent.com/1391509/137478299-c46c4903-7db8-4305-a072-8ba4c92e31fd.png">

Op de pagina staat een duidelijk header met een titel en beschrijving: "Hier staan de contactgegevens en routebeschrijving van de opleiding Frontend Design & Development (FDND). FDND is een HBO Ad opleiding aan de Hogeschool van Amsterdam."

In de beschrijving staan links naar de twee onderdelen van de pagina: _contactgegevens_ en _routebeschrijving_. Als je op de link klikt ga je met een animatie naar dat onderdeel van de pagina. Of je kan scrollen. 

Hier staat de website: https://contact.fdnd.nl

### contactgegevens

In het onderdeel _contactgegevens_ staat het telefoonnummer en email-adres van het onderwijsbureau, en de adresgegevens van de opleiding. 

### routebeschrijving

In het onderdeel _routebeschrijving_ wordt met behulp van foto's getoond hoe een bezoeker vanaf station Amstel bij het lokaal kan komen. Als iemand voor het eerst in het gebouw de Leeuwenburg komt is dat nogal een doolhof. Hierom is de routebeschrijving met behulp van foto's stap-voor-stap uitgelegd. Een bezoeker kan met een mobiel in de hand in 9 stappen bij het lokaal komen. Als een soort game. Bij elke foto staat een duidelijke beschrijving en is te zien welke stap van de 9 het is. 

![shotsnapp-1634298030 685](https://user-images.githubusercontent.com/1391509/137481669-51c22e21-7b42-404f-b5ba-8d4f43b52d3f.png)

## Kenmerken

De website is gebouwd met HTML en CSS.

### HTMLL
De basis structuur is

#### <head>
  IN de head straan de meta settings zoals 
  `<meta name="viewport" content="width=device-width,initial-scale=1">`
  
  In de `<head>` worden twee CSS file geladen. De algemene styleguide met basis settings en kleuren. 
  En een local CSS file met specifieke styling voor deze pagina. 
  
`<link rel="stylesheet" href="https://styleguide.fdnd.nl/fdnd.css">`
`<link rel="stylesheet" href="local.css">`
  
  In de `<head>` wordt een exter font geladen: De Open Sans 

### <body>

  De structuur van de body is `<header>` met de titel en eerste paragraaf.
  
  De `<main>` met daarin de section contactgegevens en een id setting voor de anchor. 
` <section id="contactgegevens">`
  En een section voor de routebeschrijving en een id setting voor de anchor. 
  `<section id="routebeschrijving">`
  
## Licentie

![GNU GPL V3](https://www.gnu.org/graphics/gplv3-127x51.png)

This work is licensed under [GNU GPLv3](./LICENSE).

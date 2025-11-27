# ConstructionPRO.fr

A simple, multilingual website for a construction company featuring services, galleries, and a contact form.

## Features
- **3 languages:** FR / EN / RU  
- **Gallery with carousel:** supports images + mp4 videos, swipe, keyboard arrows  
- **Services overview:** interior, insulation, exterior  
- **Contact form:** powered by Formspree  
- **Google Maps** embed  
- **TailwindCSS** for UI and responsive design

## Structure
index.html # Main page
gallery.html # Carousel gallery (set=1,2,3)
gallery/ # Media folders
    common/
    exterieur/
    interieur/
    isolation/

## Add Gallery Items
Place files inside `gallery/<category>/`  
Update the corresponding array inside `gallery.html`.

## Deployment
Fully static — works on GitHub Pages, Netlify, Vercel, or any shared hosting.

## License
MIT (optional).
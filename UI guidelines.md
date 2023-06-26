# Guidelines for the weather app

## Body background

### CSS gradient

`` background: linear-gradient(169.16deg, #97FFFF -13.21%, #C260FF 117.7%); ``

### Images
All background images are in /images/backgrounds

Use 0.66 opacity

## Loader animation
Ready-to-paste code in available here : https://codepen.io/jackrugile/pen/JddmaX

Use 0.75 opacity

## Blocks

### Main blocks :
```
background: rgba(255, 255, 255, 0.18);

/* BG Blur */
backdrop-filter: blur(20px);

/* Note: backdrop-filter has minimal browser support */
border-radius: 25px;
```

### Secondary blocks :
```
background: rgba(255, 255, 255, 0.05);
border-radius: 20px;
```

### Shadows

#### Outer
```
/* Neo shadow */
box-shadow: -2px -2px 4px rgba(255, 255, 255, 0.25), 2px 2px 4px rgba(0, 0, 0, 0.12);
```

#### Inner (active)
```
/* Neo shadow active */
box-shadow: inset -2px -2px 4px rgba(255, 255, 255, 0.25), inset 2px 2px 4px rgba(0, 0, 0, 0.12);
```
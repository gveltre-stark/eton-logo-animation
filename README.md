# eton-logo-animation

web prototype for Eton animated navigation logo

## Live Prototype

[View the live prototype](https://gveltre-stark.github.io/eton-logo-animation/)

## Animation Behavior

- **Page load:** Flower → Circle
- **Mouse enter:** Circle → Flower
- **Mouse leave:** Flower → Circle

The animated logo is intended to function as the website's navigation/home link.

## Files

- `index.html` — Interactive web prototype demonstrating the intended logo behavior.
- `assets/ETON-logo-animation.json` — Lottie animation asset for implementation.
- `assets/ETON - horizontal - for web_1.mp4` - Video reference of the complete logo animation.

## Technical Notes

The animation was created in Adobe After Effects and exported for Lottie.

The prototype uses the Lottie/Bodymovin JavaScript player, currently loaded via CDN.

For the prototype, the Lottie animation data is embedded directly in `index.html`. The separate JSON file is included as the animation asset for development and implementation.

The Lottie player/CDN setup is for the prototype; the final implementation can use the appropriate Lottie/web animation approach for the site.

## Source

Master animation created in Adobe After Effects.

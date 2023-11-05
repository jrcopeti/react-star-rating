# StarRating React Component

StarRating is a dynamic, reusable and customizable React component for star-based ratings.

![Screenshot](public/screenshot1.png)

## Usage

Fork and import into your project.

```javascript
import StarRating from './StarRating';
``````

## Props and customization


- maxRating (Number, required): Maximum number of stars.
- defaultRating (Number): Initial rating, default is 0.
- color (String): Star color, default is #fcc419.
- size (Number): Star size, default is 48 pixels.
- className (String): Additional CSS class.
- messages (Array of Strings): Messages corresponding to each rating value.
- onSetRating (Function): Callback when a rating is set.

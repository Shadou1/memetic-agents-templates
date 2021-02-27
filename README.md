# memetic-agents-templates
### Templates for creating the most abominable and hilarious of images

## Structure
### How this project should be structured:

Each image should be placed into a folder describing its most distinct category.
For example, if and image is from a movie or series of movies, it should be placed into a folder named after that movie.

Images themselves should be prefixed with either the name of the category or with something else relating to that category.

### Example

![Image of Spongebob and Patrick laughing](https://data.whicdn.com/images/208194316/original.jpg)

Take a look at this potentially rib-tickling picture. It's from an animated comedy television series [SpongeBob SquarePants](https://en.wikipedia.org/wiki/SpongeBob_SquarePants).
Its category, therefore, is *SpongeBob SquarePants* or just *SpongeBob* for short. **For folder names use all lowercase words separated with dashes**.

Its name should describe what's happening in the image. It could be named `spongebob-and-patrick-laughing`. But you can also use names that describe the picture in not so forward way. `spongebob-25` will also be a valid name. Take note on how in both variants the names are prefixed with `spongebob-`. **For file names also use only lowercase letters and dashes**

They could also be prefixed with other words if it is more appropriate. If another character is the main focus of the picture, it could be prefixed with `krabs-` or `plankton-`. All these prefixes still relate to the category of this picture.

## Custom images

Some images will carry with them extra information besides the image itself, contained in a `.json` file.
**It should be placed in the same folder as the image and should have the same name as the image**.
These custom images should be placed in a separate folder named `custom` witin the category folder.

### Custom .json files structure
```json
{
  // Textboxes that could be filled with text
  "textboxes": [
    // x, y is top left corner of the textbox
    // w, h is the width and height of the textbox
    { "x": 262, "y": 27, "w": 225, "h": 154 },
    // r is rotation of the textbox around the middle of it
    { "x": 270, "y": 290, "w": 225, "h": 154, "r": 12 }
  ]
}
```
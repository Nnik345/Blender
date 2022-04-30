## Bowling

Inside this project is a 3-D model of a Bowling Ball, Bowling Pins and an animation all made in Blender.
![image](https://user-images.githubusercontent.com/37971128/166103960-7a6e1cbd-8cc0-4e9d-a209-12c8ae969de2.png)

### Bowling Pin
Starting with the Bowling Pin, it was designed using a reference image. An outline was drawn around the Image and using Blender's auto generate tool, a frame was generated and rotated 360° to make a Bowling Pin. This was then edited by combining and removing faces to make it look more natural and the bottom made flat, since it had a curved shape. Once this was done the number of faces was reduced to a minimum to make it easier to render. 

Once the shape of the Bowling Pin was decided, I began to add colour to it. Making the stripes red and the rest of the pin white, I made it a little reflective. With this, the Bowling Pin was done.

Here is an image of the completed Bowling Pin
![image](https://user-images.githubusercontent.com/37971128/166104497-16990ffc-2222-45a0-9748-21d0f452ce0b.png)

### Bowling Ball
Next up, the bowling ball was made using a UV Sphere. Some faces were combined to make it possible to create a proper finder hold. Once done, I decided to make it red and very reflective.

An image of the Bowling Ball:
![image](https://user-images.githubusercontent.com/37971128/166104434-a83b0d3d-374e-4485-80af-40685618a4d7.png)

### Animation
After creating the two objects, I combined them together in one scene. Using Blender's physics system, I gave both objects the required mass and animated the Ball to roll to the Pins and hit them. I then saw the Pins bobble instead of falling down, which is when I realised I forgot to set the center of mass of the Bowling Pins properly. After changing it to the proper location, it worked!

https://github.com/Nnik345/Blender/tree/main/Bowling

## Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [Basic writing and formatting syntax](https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Nnik345/Blender/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.

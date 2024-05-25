## Background Gradients Using CSS
A CSS gradient displays a smooth transition using two or more specified colors. 
CSS gradients provide better control and performance over using an actual image 
file of a gradient that you can create using tools like Adobe Illustrator. Use 
the background-image CSS property to declare gradients as a background.

There are three types of gradients: linear (created with the linear-gradient() 
function), radial (created with the radial-gradient() function), and conic 
(created with the conic-gradient() function). You can also create repeating 
gradients with the repeating-linear-gradient(), repeating-radial-gradient(), 
and repeating-conic-gradient() functions.

## MDN Docs define these functions as:

<b>linear-gradient():</b> The linear-gradient() CSS function creates an image consisting 
of a progressive transition between two or more colors along a straight line. Its 
result is an object of the <gradient> data type, which is a special kind of <image>.

<b>radial-gradient():</b> The radial-gradient() CSS function creates an image consisting 
of a progressive transition between two or more colors that radiate from an origin. 
Its shape may be a circle or an ellipse. The function's result is an object of the 
<gradient> data type, which is a special kind of <image>.

<b>conic-gradient():</b> The conic-gradient() CSS function creates an image consisting of 
a gradient with color transitions rotated around a center point (rather than 
radiating from the center). Examples of conic gradients include pie charts and 
color wheels. The result of the conic-gradient() function is an object of the 
<gradient> data type, which is a special kind of <image>.

<b>radial-gradient():</b> The radial-gradient() CSS function creates an image consisting 
of a progressive transition between two or more colors that radiate from an origin. 
Its shape may be a circle or an ellipse. The function's result is an object of the 
<gradient> data type, which is a special kind of <image>.

<b>conic-gradient():</b> The conic-gradient() CSS function creates an image consisting of 
a gradient with color transitions rotated around a center point (rather than radiating 
from the center). Examples of conic gradients include pie charts and color wheels. 
The result of the conic-gradient() function is an object of the <gradient> data type, 
which is a special kind of <image>.

## Here's the official syntax of each type of gradient.

### Syntax of Linear Gradients

```
linear-gradient(
 [ <angle> | to <side-or-corner> ]? ,
 <color-stop-list>
)
<side-or-corner> = [to left | to right] || [to top | to bottom]
```

### Syntax of Radial Gradients

```
radial-gradient(
 [ <ending-shape> || <size> ]? [ at <position> ]? ,
 <color-stop-list>
);
```

### Syntax of Conic Gradients

```
conic-gradient(
 [ from <angle> ]? [ at <position> ]?,
 <angular-color-stop-list>
)
```

Here are some awesome background gradient examples created using the background-image 
CSS property that can enhance the UI of your website to the next level.

## 35 Stylish CSS Background Gradient Examples;

1. Dusty Grass
 
Use the following CSS to create the above gradient:
```
background-image: linear-gradient(120deg, #d4fc79 0%, #96e6a1 100%);
```

2. Sand to Blue
 
To create the gradient shown above, use the following CSS code:
```
background-image: linear-gradient(to right, #DECBA4, #3E5151);
```

3. Kye Meh
 
Use the following CSS code to create the above linear gradient background:
```
background-image: linear-gradient(to right, #8360c3, #2ebf91);
```

4. Amin
 
Use the following CSS to create the above gradient:
```
background-image: linear-gradient(to right, #8e2de2, #4a00e0);
```

5. Relaxing Red
 
With just a single line of CSS code, you can add a beautiful, eye-catching background 
gradient to your website:
```
background-image: linear-gradient(to right, #fffbd5, #b20a2c);
```

6. Sublime Light
 
Try using this CSS to create a gradient background. It's easy to use and will add a touch 
of style to your site:
```
background-image: linear-gradient(to right, #fc5c7d, #6a82fb);
```

7. Megatron
 
Use the following CSS to create a 3-colored gradient:
```
background-image: linear-gradient(to right, #c6ffdd, #fbd786, #f7797d);
```

8. Blue Raspberry
 
Use the following CSS to create a simple bluish linear gradient background:
```
background-image: linear-gradient(to right, #00b4db, #0083b0);
```

9. Premium Dark
 
Get the gradient look shown above with this linear gradient CSS code:
```
background-image: linear-gradient(to right, #434343 0%, black 100%);
```

10. Crystalline
 
Use the following CSS to create the above gradient:
```
background-image: linear-gradient(-20deg, #00cdac 0%, #8ddad5 100%);
```

11. Lawrencium
 
Use the following CSS to create the above gradient. You can also use this code to create 
other gradients with different colors.
```
background-image: linear-gradient(to right, #0f0c29, #302b63, #24243e);
```

12. Ohhappiness
 
Add a touch of style to your site with this easy-to-use CSS gradient background:
```
background-image: linear-gradient(to right, #00b09b, #96c93d);
```

13. The Strain
 
Looking to add some pizzazz to your website? Try using this CSS to create a gradient background:
```
background-image: linear-gradient(to right, #870000, #190a05);
```

14. Yellow Mango
 
Use the following CSS to create the above radial gradient background:
```
background-image: radial-gradient(circle farthest-side, #fceabb, #f8b500);
```

15. Juicy Grass
 
Transform your HTML elements in a snap with this CSS code:
```
background-image: radial-gradient( circle 759px at -6.7% 50%, rgba(80,131,73,1) 0%, 
  rgba(140,209,131,1) 26.2%, rgba(178,231,170,1) 50.6%, rgba(144,213,135,1) 74.1%, 
  rgba(75,118,69,1) 100.3% );
```

16. Pink Fish
 
Use the following CSS to create the above linear gradient background:
```
background-image: linear-gradient(to right, rgb(242, 112, 156), rgb(255, 148, 114));
```

17. Sea Lord
 
Use the following CSS to create the above gradient:
```
background-image: linear-gradient( 109.6deg, rgba(156,252,248,1) 11.2%, rgba(110,123,251,1) 91.1% );
```

18. Cherry Blossom
 
This CSS code will create a cherry-colored gradient. You can also use it to create 
other gradients with different colors:
```
background-image: linear-gradient(25deg,#d64c7f,#ee4758 50%);
```

19. Fresh Air
 
To create the gradient shown above, use the following CSS code:
```
background-image: linear-gradient( 95.2deg, rgba(173,252,234,1) 26.8%, rgba(192,229,246,1) 64% );
```

20. Stellar
 
Use the following CSS to create a blue gradient that is sure to capture attention:
```
background-image: radial-gradient( circle farthest-corner at 22.4% 21.7%, rgba(4,189,228,1) 0%, rgba(2,83,185,1) 100.2% );
```

21. Noon to Dusk
 
Transform your HTML elements with a single line of CSS code, and add a beautiful background gradient with ease:
```
background-image: linear-gradient(to right, #ff6e7f, #bfe9ff);
```

22. Sunrise
 
Your website can have a sunrise gradient by just adding one line of CSS code:
```
background-image: linear-gradient(to right, #ff512f, #f09819);
```

23. Forest
 
Use the following CSS to create the above gradient. You can also use it to create 
other gradients with different colors, giving you endless possibilities for 
customizing your site.
```
background-image: linear-gradient(to right, #5a3f37, #2c7744);
```

24. Superman
 
Get the gradient look shown above with this linear gradient CSS code:
```
background-image: linear-gradient(to right, #0099f7, #f11712);
```

25. Deep-Sea Space
 
Use the following CSS to make the background look professional and polished:
```
background-image: linear-gradient(to right, #2c3e50, #4ca1af);
```

26. Royal
 
Use the following CSS to create the above linear gradient background:
```
background-image: linear-gradient(to right, #141e30, #243b55);
```

27. Orange Coral
 
Use the following CSS to create the above gradient:
```
background-image: linear-gradient(to right, #ff9966, #ff5e62);
```

28. Old Wine
 
You can create a dark pink gradient style using the following CSS code:
```
background-image: linear-gradient(to right, #33001b, #ff0084); 
```

29. Morning Sky
 
Use the following CSS to create a clear morning sky gradient:
```
background-image: linear-gradient(to right, #b6fbff, #83a4d4);
```

30. Caramel
 
Make your background stand out with this CSS linear gradient background:
```
background-image: linear-gradient(to right, #FFD194, #D1913C);
```

31. Dusk
 
Looking to captivate your audience? Incorporate this CSS code snippet to create a 
dusk-themed gradient background that will elevate your website's appeal.
```
background-image: linear-gradient(to right, #9796f0, #fbc7d4);
```

32. Margo White
 
Generate an eye-catching and simplistic gradient background by implementing this CSS code:
```
background-image: linear-gradient(to right, #ffefba, #ffffff);
```

33. Evening to Night
 
Achieve the same alluring gradient effect showcased above by utilizing this linear gradient CSS code:
```
background-image: linear-gradient(to right, #005aa7, #fffde4);
```

34. Ocean View
 
Enhance your website's aesthetics with this simple CSS code for creating a captivating linear gradient background:

```
background-image: linear-gradient(to right, #a8c0ff, #3f2b96);
```

35. Feather
 
Utilize this CSS code snippet to create a gradient background similar to the one displayed above:

```
background-image: linear-gradient(to right, #d3cce3, #e9e4f0); 
```

### Make Your Webpage Elegant With Gradients

You can use gradients with several elements of your webpage like background, borders, icons, 
buttons, text, underlining, list bullets, etc. Take your site's design to new heights.


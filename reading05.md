# css & html

In this blog we will summrize **chapter 10** wich is **introducing css**

# Chapter 10

we will dicuss:

* What CSS does
* How CSS works
* Rules, properties and values

### Understanding CSS

#### What CSS does

CSS allows you to create rules that control the way that each individual element in html (and the contents of that element) is presented.

#### BLOCK & INLINE ELEMENTS

* **Block level** elements look like they start on a new line.

* **Inline elements** flow within the text and do not start on a new
line. 

### Example Styles : 

#### BOXES
1. Width and height
1. Borders (color, width, and style)
1. Background color and images
1. Position in the browser window.

#### TEXT 

1. Typeface
1. Size
1. Color
1. Italics, bold, uppercase,
1. lowercase, small-caps

#### SPECIFIC
There are also specific ways in which you can style certain elements such as lists, tables and forms.

## CSS Associates Style rules with HTML elements

A CSS rule contains two parts: a *selector* and a *declaration*.

## CSS Properties Affect How Elements Are Displayed

CSS declarations sit inside curly brackets and each is made up of two parts: a *property* and a *value*, separated by a colon. 

### There are three ways to apply CSS to HTML:
1. **Inline** : plonked straight into the HTML tags using the style attribute.
2. **Internal** : styles are used for the whole page. Inside the head element, the *style* tags surround all of the styles for the page. 
3. **External** : External styles are used for the whole, multiple-page website. There is a *separate CSS file*.

### Declarations are made up of two parts: 
* the properties : of the element that you want to change
*  the values of those properties.
 **For example** the font-family property sets the choice of font, and the value arial specifies Arial as the preferred typeface.


# chapter 11 

## Color

we will dicuss : 
* How to specify colors
* Color terminology and contrast
* Background color

The color property allows you to specify the color of text inside an element.  in one of three ways:

* rgb values
* hex codes
* color names

#### Every color on a computer screen is created by mixing amounts of red,green, and blue. 


### Colors properties : 
* Hue 
* Saturation
* Brightness
* Contrast
* Opacity


### Css3: hsl, hsla
It is an alternative way to specify colors.
The value of the property starts
with the letters hsl, followed
by individual values inside
parentheses for:
* **hue**
 an angle(between 0 and 360 degrees).
* **saturation**
a percentage.
* **lightness**
 a percentage with 0% being white,50% being normal, and 100% being black.
* **alpha**
This is expressed as a number between 0 and .0.
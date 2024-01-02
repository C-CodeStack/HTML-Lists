# HTML Lists 

We can use Nested Tags to create lists.

The list below:

**Teams with the Most Super Bowl Wins**

- Steelers
- Patriots
- Cowboys
<br>
<br>

## Task 1

**Copy the code above onto your HTML file**

```
<h1> Teams with Most Super Bowl Wins</h1>
<ul>
  <li>Patriots</li>
  <li>Steelers</li>
  <li>Cowboys</li>
</ul>

```


This is an **Unordered List**. It uses BULLET POINTS for each list item. Notice that the title for the list **is not** a part of the list itself, it is in ```<h1>``` tags.

- Nested inside of the ```<ul>``` tags will be the list items.  Each list item will be inside ```<li>``` tags.  Each list item should be closed. ```<li>list item</li>```

```
<h1>Teams with Most Super Bowl Wins</h1>

<ul><---Opening Tag for the entire list
  <li>Patriots</li><---list item
  <li>Steelers</li><---list item
  <li>Cowboys</li><----list item
</ul><---closing Tag for the entire list

```

## Task 2

**Recreate the list below inside the body tags of the HTML document**

- John
- Paul
- George
- Ringo

# Ordered Lists

An Ordered List uses NUMBERS or LETTERS that display each list item in alphabetical or numerical order. The list must begin with ```<ol>``` and end with ```</ol>```.  Nested inside of the <ol> tags will be the list items.  Each list item will be inside ```<li>``` tags. 

**Copy the sample code below onto your webpage:**

```
<h1> Teams with Most Super Bowl Wins</h1>
<ol>
  <li>Patriots</li>
  <li>Steelers</li>
  <li>Cowboys</li>
</ol>

```
When you run the code you will notice numbers instead of letters.



## CSS List Properties

You can use CSS to style your lists.  You can change the ```font-family```, ```color```, ```font-size```, or any other text property just as you do with any text element.

```
ul {
  font-family: Arial;
  color: darkblue;
}
```
You can also change the list item markers (bullet points or numbers) using CSS.

**For Example:**

```
ul {
  list-style-type: circle;
}
```

**Changes bullet points on a unordered list to square**



```
ol {
  list-style-type: upper-roman;
}
```
**Changes numbers on a ordered list to roman numerals**

```
ol {
  list-style-type: lower-alpha;
}
```
**Changes numbers on a ordered list to lowercase letters**

Click the link below to explore common **list properties.**

[CSS List Properties](https://www.w3schools.com/css/css_list.asp)

## CSS classes

You can use **CSS classes** to change a single type of element in multiple ways by adding a **class attribute** in the opening tag like this:

```
<ol class="cities">
```

## Task 4

***Use HTML and CSS to recreate the list below. Like this:***

```
<h1>World’s Largest Cities</h1>

<ol class="cities">
  <li>Tokyo</li>
  <li>Jakarta</li>
  <li>Chongqing</li>
  <li>Delhi</li>
  <li>Chongqing</li>
</ol>

```
Now in CSS, you use the class selector, which looks like this ```.cities```. () A period, followed by the class name).  In CSS the ruleset would look like this:

```
.cities {
  list-style-type: decimal;
}
```

## Task 5

**Use HTML and CSS to recreate each type of list on the below. Remember to use a different class for each list**


A. Alpha

B. Beta

C. Gamma

D. Delta

--

I. Uno

II. Dos

III. Tres

IV. Cuatro

--

a. Ishi

b. Ni 

C. Son

d. Shii


## Task 6

Change the ```font-family``` of the ordered lists to ```Helvetica``` and the ```font-family``` of the unordered lists to ```san-serif```.
  
## Task 7

Click the link below to explore common **list properties.**  Scroll down to see how you can change List Items ```<li>``` independently of the entire list, ```<ol>``` or ```<ul>```

[CSS List Properties](https://www.w3schools.com/css/css_list.asp)

Create an **ordered list** of 5 of your favorite foods. Add a background color to the list and a **different** background color to the **list items**.  Change the font and color of the text (doesn't matter what color or font).


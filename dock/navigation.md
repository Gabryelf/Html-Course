# Html-Course

```html
<nav id="menu1">
    <ul>
 		<li><a href="#m1">MENU</a></li>
        <li><a href="#m2">MENU</a></li>
 		<li><a href="#m3">MENU</a>
 			<ul>
                <li><a href="#m3_1">Menu</a></li>
                <li><a href="#m3_2">Menu</a></li>
                <li><a href="#m3_3">Menu</a></li>
                <li><a href="#m3_4">Menu</a></li>
                <li><a href="#m3_5">Menu</a></li>
 			</ul>
 		</li>
 		<li><a href="#m4">MENU</a></li>
 		<li><a href="#m5">MENU</a></li>
    </ul>
</nav>
```

# Styles NAV

## 1

```css
#menu1{
position: relative;
display: block;
width: 100%;
height: auto;
z-index: 10;
}
```

## 2

```css
#menu1 ul{
position: relative;
display: block;
margin: 0px;
padding: 0px;
width: 100%;
height: auto;
list-style: none;
}
```

## 3

```css
#menu1 > ul::after{
display: block;
width: 100%;
height: 0px;
clear: both;
content: " ";
}
```

## 4

```css
#menu1 ul li{
position: relative;
display: block;
 float: left;
width: auto;
height: auto;
}
```

## 5

```css
#menu1 ul li a{
display: block;
padding: 9px 25px 0px 25px;
font-size: 14px;
line-height: 1.3em;
text-decoration: none;
font-weight: bold;
text-transform: uppercase;
height: 36px;
box-sizing: border-box;
color: white;
}
```

## 6

```css
#menu1 ul li ul{
position: absolute;
top: 36px;
left: 0px;
display: none;
width: 200px;
background: #38b6ff;
}
```

## 7

```css
#menu1 ul li:hover ul{
display: block;
}
```

## 8

```css
#menu1 ul li ul li{
float: none;
width: 100%;
}

#menu1 ul li ul li a{
display: block;
text-transform: none;
height: auto;
padding: 7px 25px;
width: 100%;
box-sizing: border-box;
border-top: 1px solid #ffffff;
color: white;
}

#menu1 ul li ul li:first-child a{
border-top: 0px;
}
```

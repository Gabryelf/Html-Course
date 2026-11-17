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

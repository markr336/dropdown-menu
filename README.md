# dropdown-menu

Simple dropdown menu that appears when hovering over the text.

DOM Tree:

<div class="dropdown">
<p class="dropdown-menu">Dropdown 1</p>
<div class="dropdown-content">
<a href="#">Link 1</a>
<a href="#">Link 2</a>
<a href="#">Link 3</a>
</div>
</div>
<div class="dropdown">
<p class="dropdown-menu">Dropdown 2</p>
<div class="dropdown-content">
<a href="#">Link 4</a>
<a href="#">Link 5</a>
<a href="#">Link 6</a>
</div>
</div>
.
.
.
<div class="dropdown">
<p class="dropdown-menu">Dropdown 2</p>
<div class="dropdown-content">
<a href="#">Link 7</a>
<a href="#">Link 8</a>
<a href="#">Link 9</a>
</div>
</div>

Stylesheet
/_ dropdown stylesheet _/
/_ The container <div> - needed to position the dropdown content _/
.dropdown {
position: relative;
display: inline-block;
}

/_ Dropdown Content (Hidden by Default) _/
.dropdown-content {
display: none;
position: absolute;
background-color: #f1f1f1;
min-width: 160px;
box-shadow: 0px 8px 16px 0px rgba(0, 0, 0, 0.2);
z-index: 1;
}

/_ Links inside the dropdown _/
.dropdown-content a {
color: black;
padding: 12px 16px;
text-decoration: none;
display: block;
}

/_ Change color of dropdown links on hover _/
.dropdown-content a:hover {
background-color: #ddd;
}

/_ Change the background color of the dropdown button when the dropdown content is shown _/
.dropdown:hover .dropdown-menu {
background-color: #3e8e41;
}
# dropdown-menu

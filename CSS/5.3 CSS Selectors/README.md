### CSS Selector

Link refer https://developer.mozilla.org/en-US/docs/Web/HTML/Element/li

#### CSS selector & where apply CSS Selector

example:
    color: blue
        -> properly: value


Example:

***h1*** {                 => CSS selector
    color: blue
}

.red_heading {
    color: green 
}

=> <h2 class=".red_heading"> Heading 2 </h2>
------------------------------------------------------------------------------
set para => paragraph
p {
    color: red
}
------------------------------------------------------------------------------

set class => <li class="note" id="id-selector-demo" value="3">
.note {
    color: yellow
}
------------------------------------------------------------------------------

id selector => <li class="note" id="id-selector-demo" value="3">
#id_selector {
    color: green
}
------------------------------------------------------------------------------

element value selector => <li class="note" id="id-selector-demo" value="3">
li[value="4"] {
  color: blue;
}
------------------------------------------------------------------------------

all selector => *
* {
  text-align: center;
}
<h6><b>Adilakshmi Meesala</b></h6>
<p>I'am AdiLakshmi Meesala from Hyderabad.Currently I'm pursuing Masters in Northwest Missouri State unversity Maryville</p>
<a href="http://www.google.com">AboutMe.md</a>
<img src="lakshmi.png" width=450" height="450">
<hr>
<h4> Famous cities to visit</h4>
<p>Best Places to Visit in Missouri state in USA</p>
<table border="1">
<tr>
<th>City Name</th>
<th>Location Name</th>
<th>amount of time to spend visiting</th>
</tr>
<tr>
<td>Kansas City</td>
<td>mozingo lake</td>
<td>1 to 3hrs we can spend time to visit</td>
</tr>
<tr>
<td>Dallas</td>
<td>The Dallas Zoo </td>
<td>1 to 2hrs we can spend time to visit</td>
</tr>
<tr>
<td>Chicago</td>
<td>Millennium Park</td>
<td>1 to 2hrs we can spend time to visit</td>
</tr>
<tr>
<td>Florida</td>
<td>Universal Orlando Resort</td>
<td>1 to 2hrs we can spend time to visit</td>
</tr>
</table>
<hr>
<h2>Quote Section</h2>
<blockquote>Never look back unless you are planning to go that way---<i>​Henry David Thoreau</i></blockquote>
<blockquote>“The most common way people give up their power is by thinking they don’t have any---<i>Alice Walker</i></blockquote>

<hr>
Stephen King
# Code Fencing
_ _ _
> What does that mixin mean.
[stackoverflow](https://stackoverflow.com/questions/54974250/what-does-this-mixin-mean)

/// Gives a card depth effect.
/// @param {Number} $depth - depth level (between 1 and 5)
/// @link http://www.google.com/design/spec/layout/layout-principles.html#layout-principles-dimensionality Google Design
/// @requires {function} top-shadow
/// @requires {function} bottom-shadow
@mixin card($depth) {
  @if $depth < 1 {
    box-shadow: none;
  } @else if $depth > 5 {
    @warn "Invalid $depth `#{$depth}` for mixin `card`.";
  } @else {
    box-shadow: bottom-shadow($depth), top-shadow($depth);  
  }
}

[Snippet Source](https://css-tricks.com/snippets/sass/material-shadows-mixin/)



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
<q> The most common way people give up their power is by thinking they don’t have any---<i>Alice Walker</i></q>

<hr>
<h6>Code Fencing</h6>

<blockquote>sort properties in .sass files automaticaly</blockquote>

<a href="https://stackoverflow.com/questions/57286768/how-to-sort-sass-properties-for-example-in-alphabetical-order"> How to sort Sass properties</a>

<code> 
@function quick-sort($list) {
  $less:  ();
  $equal: ();
  $large: ();

  @if length($list) > 1 {
    $seed: nth($list, ceil(length($list) / 2));

    @each $item in $list {
      @if ($item == $seed) {
        $equal: append($equal, $item);
      } @else if ($item < $seed) {
        $less: append($less, $item);
      } @else if ($item > $SEED) {
        $large: append($large, $item);
      }
    }

    @return join(join(quick-sort($less, $order), $equal), quick-sort($large, $order));
  }

  @return $list;
}
</code>

<a href="https://css-tricks.com/snippets/sass/sorting-function/"> Sorting Function</a>


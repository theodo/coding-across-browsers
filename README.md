IE bugs
========

This repository is a community-curated list of differences between browsers when dealing with CSS.
It is inspired by the famous [flexbugs](https://github.com/philipwalton/flexbugs) repository.

## The bugs and their workarounds

1. [Minimum content sizing of flex items not honored](#flexbug-1)

### Issue #1

_Minimum content sizing of flex items not honored_

<table>
  <tr>
    <th align="left">Demos</th>
    <th align="left">Browsers concerned</th>
  </tr>
  <tr valign="top">
    <td>
      <a href="https://codepen.io/philipwalton/pen/MYbrrr">1.1.a</a> &ndash; <em>bug</em><br>
      <a href="https://codepen.io/philipwalton/pen/ByQJOQ">1.1.b</a> &ndash; <em>workaround</em><br>
      <a href="https://codepen.io/philipwalton/pen/ByQJqQ">1.2.a</a> &ndash; <em>bug</em><br>
      <a href="https://codepen.io/philipwalton/pen/wBopYg">1.2.b</a> &ndash; <em>workaround</em>
    </td>
    <td>
      Chrome (partially fixed in 44)<br>
      Opera (partially fixed in 31)<br>
      Safari (fixed in 10)
    </td>
  </tr>
</table>

When ...

> By default, ...

#### Workaround

You can ...

---
title: "Schedule"
permalink: /schedule.html
layout: single
classes: wide  
toc: false
sidebar:
    - nav: sitemap
    - nav: contact
---

{% comment %}
    In an element with a 2in font, 1em thus means 2in.
    Declarations such as text-indent: 1.5em and margin: 1em are extremely common in CSS.
{% endcomment %}

{% raw %}
<style>
table.schedule{
  margin-bottom: 0;
  margin-top: 0;
  overflow-x: auto;
  border-bottom-width:0;
}

tr.min15{
  height: 1.5em;
}
tr.min30{
  height: 3em;
}
tr.min60{
  height: 6em;
}
tr.lunch{
  height: 3em;
}

td{
  padding: 0 0.5em;
  text-align: center;
}

th{
  padding: 1em 0.5em;
  font-weight: bold;
  text-align: center;
}
</style>

<style type="text/css" media="print">
  a:link:after, a:visited:after {
    display: none;
    content: "";
  }
  td{
  padding: 0 0.5em;
  text-align: center;
  }
</style>

<table class="schedule">
<tbody>
    <tr class="min15">
      <th>Time</th>
      <th>Day 1 (Mon)</th>
      <th>Day 2 (Tue)</th>
      <th>Day 3 (Wed)</th>
      <th>Day 4 (Thu)</th>
      <th>Day 5 (Fri)</th>
    </tr>
    
    <tr class="min60">
      <td>9:30&#8209;10:30</td>
      <td>Talk 1<br>(Speaker TBD)</td>
      <td>Talk 1<br>(Speaker TBD)</td>
      <td>Talk 1<br>(Speaker TBD)</td>
      <td>Talk 1<br>(Speaker TBD)</td>
      <td>Talk 1<br>(Speaker TBD)</td>
    </tr>
    
    <tr class="min30">
      <td>10:30&#8209;11:00</td>
      <td colspan="5">Coffee Break</td>
    </tr>
    
    <tr class="min60">
      <td>11:00&#8209;12:00</td>
      <td>Talk 2<br>(Speaker TBD)</td>
      <td>Talk 2<br>(Speaker TBD)</td>
      <td>Talk 2<br>(Speaker TBD)</td>
      <td>Talk 2<br>(Speaker TBD)</td>
      <td>Talk 2<br>(Speaker TBD)</td>
    </tr>
    
    <tr class="lunch">
      <td>12:00&#8209;15:00</td>
      <td colspan="5">Lunch Break</td>
    </tr>
    
    <tr class="min60">
      <td>15:00&#8209;16:00</td>
      <td>Talk 3<br>(Speaker TBD)</td>
      <td>Talk 3<br>(Speaker TBD)</td>
      <td>Talk 3<br>(Speaker TBD)</td>
      <td>Talk 3<br>(Speaker TBD)</td>
      <td>Talk 3<br>(Speaker TBD)</td>
    </tr>

    <tr class="min30">
      <td>16:00 onwards</td>
      <td colspan="5">Free Discussion</td>
    </tr>
</tbody>
</table>
{% endraw %}

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
  width: 100%;
}

tr.min10{
  height: 1.5em; /* For Opening Remarks */
}
tr.min15{
  height: 1.5em;
}
tr.min30{
  height: 3em;
}
tr.min60{
  height: 4em;
}
tr.lunch{
  height: 3em;
}

td{
  padding: 0.5em;
  text-align: center;
  vertical-align: middle;
  border: 1px solid #eee;
}

th{
  padding: 1em 0.5em;
  font-weight: bold;
  text-align: center;
  background-color: transparent;
  border: 1px solid #eee;
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
      <th style="width: 10%;">Time</th>
      <th style="width: 18%;">1.19 (Mon)</th>
      <th style="width: 18%;">1.20 (Tue)</th>
      <th style="width: 18%;">1.21 (Wed)</th>
      <th style="width: 18%;">1.22 (Thu)</th>
      <th style="width: 18%;">1.23 (Fri)</th>
    </tr>

    <tr class="min10">
      <td>9:20&#8209;9:30</td>
      <td><strong>Opening Remarks</strong></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    
    <tr class="min60">
      <td>9:30&#8209;10:30</td>
      <td>Robert de Mello Koch</td>
      <td>Cynthia Yan</td>
      <td>Frank Ferrari</td>
      <td>Elisa Tabor</td>
      <td>Mathew Heydeman</td>
    </tr>
    
    <tr class="min30">
      <td>10:30&#8209;11:00</td>
      <td colspan="5" style="background-color:transparent; font-style:italic;">Coffee Break</td>
    </tr>
    
    <tr class="min60">
      <td>11:00&#8209;12:00</td>
      <td>Zechuan Zheng</td>
      <td>Masamichi Miyaji</td>
      <td>Sean Colin-Ellerin</td>
      <td>Jan Boruch</td>
      <td>Philipp A. Hoehn</td>
    </tr>
    
    <tr class="lunch">
      <td>12:00&#8209;14:00</td>
      <td colspan="5" style="background-color:transparent; font-style:italic;">Lunch Buffet</td>
    </tr>
    
    <tr class="min60">
      <td>14:00&#8209;15:00</td>
      <td>Sam van Leuven</td>
      <td>Diandian Wang</td>
      <td>Ji-Hoon Lee</td>
      <td style="font-style:italic;">Free Discussion</td>
      <td style="font-style:italic;">Free Discussion</td>
    </tr>

    <tr class="min30">
      <td>15:00&#8209;15:30</td>
      <td colspan="5" style="background-color:transparent; font-style:italic;">Coffee Break</td>
    </tr>

    <tr class="min60">
      <td>15:30&#8209;16:30</td>
      <td>Eunwoo Lee</td>
      <td>Mengyang Zhang</td>
      <td></td>
      <td></td>
      <td></td>
    </tr>

</tbody>
</table>
{% endraw %}

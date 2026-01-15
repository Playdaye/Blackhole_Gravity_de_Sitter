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
      <th style="width: 18%;">1.19 (Monday)</th>
      <th style="width: 18%;">1.20 (Tuesday)</th>
      <th style="width: 18%;">1.21 (Wednesday)</th>
      <th style="width: 18%;">1.22 (Thursday)</th>
      <th style="width: 18%;">1.23 (Friday)</th>
    </tr>


    <tr class="min10">
      <td>9:00&#8209;9:25</td>
      <td><strong>Registration</strong></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    
    
    <tr class="min10">
      <td>9:25&#8209;9:30</td>
      <td><strong>Opening Remarks</strong></td>
      <td></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>
    
    <tr class="min60">
      <td>9:30&#8209;10:30</td>
      <td><strong>Robert de Mello Koch</strong></td>
      <td><strong>Cynthia Yan</strong></td>
      <td><strong>Frank Ferrari</strong></td>
      <td><strong>Elisa Tabor</strong></td>
      <td><strong>Mathew Heydeman</strong></td>
    </tr>
    
    <tr class="min30">
      <td>10:30&#8209;11:00</td>
      <td colspan="5" style="background-color:transparent; font-style:italic;">Coffee Break</td>
    </tr>
    
    <tr class="min60">
      <td>11:00&#8209;12:00</td>
      <td><strong>Zechuan Zheng</strong></td>
      <td><strong>Masamichi Miyaji</strong></td>
      <td><strong>Sean Colin-Ellerin</strong></td>
      <td><strong>Jan Boruch</strong></td>
      <td><strong>Philipp A. Hoehn</strong></td>
    </tr>
    
    <tr class="lunch">
      <td>12:00&#8209;14:00</td>
      <td colspan="5" style="background-color:transparent; font-style:italic;">Lunch Buffet</td>
    </tr>
    
    <tr class="min60">
      <td>14:00&#8209;15:00</td>
      <td><strong>Sam Van Leuven</strong></td>
      <td><strong>Diandian Wang</strong></td>
      <td><strong>Ji-Hoon Lee</strong></td>
      <td style="font-style:italic;">Free Discussion</td>
      <td style="font-style:italic;">Free Discussion</td>
    </tr>

    <tr class="min30">
      <td>15:00&#8209;15:30</td>
      <td colspan="5" style="background-color:transparent; font-style:italic;">Coffee Break</td>
    </tr>

    <tr class="min60">
      <td>15:30&#8209;16:30</td>
      <td><strong>Eunwoo Lee</strong></td>
      <td><strong>Mengyang Zhang</strong></td>
      <td></td>
      <td></td>
      <td></td>
    </tr>


<tr class="min10">
      <td>19:00&#8209;</td>
      <td></td>
      <td></td>
      <td><strong>Banquet</strong></td>
      <td></td>
      <td></td>
    </tr>


</tbody>
</table>
{% endraw %}

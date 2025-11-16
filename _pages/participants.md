---
title: "Participants"
permalink: /participants.html
layout: single
classes: wide
toc: false
sidebar:
    - nav: sitemap
    - nav: contact
other_participants:



    - gname: Jianxin
      fname: Lu
      from: USTC

    - gname: Bin
      fname: Chen
      from: Ningbo University
    
    - gname: Wenli
      fname: Yang
      from: Northeast University

    - gname: Junpeng 
      fname: Cao
      from: Institute of Physics, CAS

    - gname: Kimyeong 
      fname: Lee
      from:  BIMSA

    - gname: Xin
      fname: Sun
      from:  Peking University

    - gname: Yi
      fname: Pang
      from:  Tianjin University

    - gname: Minxin
      fname: Huang
      from:  USTC

    - gname: Xin
      fname: Wang
      from:  USTC

    - gname: Jun
      fname: Nian
      from:  UCSA, CAS

    - gname: Jieqiang
      fname: Wu
      from:  ITP, CAS

    - gname: Cheng
      fname: Peng
      from:  KITS, CAS
  
    - gname: Yang
      fname: Zhou
      from:  Fudan University

    - gname: Sung-Soo
      fname: Kim
      from:  UESTC, Chengdu

    - gname: Song
      fname: He
      from:  Ningbo University

    - gname: Jie
      fname: Gu
      from:  Southeast University

    - gname: Qiang
      fname: Wen
      from:  Southeast University

    - gname: Xin
      fname: Gao
      from:  Sichuan University

    - gname: Peng
      fname: Zhao
      from:  Tianjin University, Fuzhou Campus

    - gname: Ruidong
      fname: Zhu
      from:  Soochow University

    - gname: Yang
      fname: Lei
      from:  Soochow University  

    - gname: Hong
      fname: Zhang
      from:  Shanghai University

    - gname: Xinyu
      fname: Zhang
      from:  Zhejiang University

    - gname: Yen-Kheng
      fname: Lim
      from:  Xiamen University, Malaysia Campus    

    - gname: Hao
      fname: Zou
      from: SIMIS
  
    - gname: Hongfei
      fname: Shu
      from: Zhengzhou University


    - gname: Yiwen
      fname: Pan
      from: Sun Yat-sen University




---

{% comment %}
    speakers are in \_data/navigation.yml
    other_participants are in above claims
{% endcomment %}

{% assign sorted_speakers = site.data.navigation.speakers | sort:'gname' | sort: 'fname' %}
{% assign sorted_participants = page.other_participants | sort:'gname' | sort: 'fname' %}

<table>
<tbody>
    {% for s in sorted_speakers %}
        <tr>
            <td> {{ s.gname }}&nbsp;{{ s.fname }} </td>
            <td> {{ s.from }} </td>
        </tr>
    {% endfor %}
    {% for s in sorted_participants %}
        <tr>
            <td> {{ s.gname }}&nbsp;{{ s.fname }} </td>
            <td> {{ s.from }} </td>
        </tr>
    {% endfor %}
</tbody>
</table>

<img width="469" height="30" alt="image" src="https://github.com/user-attachments/assets/9a9fd31d-8279-4240-8d52-b491093af501" />---
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
      from:  ICTPAP, CAS

    - gname: Jieqiang
      fname: Wu
      from:  ITP, CAS

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

    - gname: Hao
      fname: Zou
      from: SIMIS
  
    - gname: Hongfei
      fname: Shu
      from: Zhengzhou University


    - gname: Yiwen
      fname: Pan
      from: Sun Yat-sen University
      
    - gname: Chushun
      fname: Tian
      from: ITP, CAS

    - gname: Zhaolong
      fname: Wang
      from: Northwest University

    - gname: Wei
      fname: Song
      from: Tsinghua University

    - gname: Hong
      fname: Lu
      from: Tianjin University

    - gname: Fengjun
      fname: Xu
      from: BIMSA

    - gname: Cheng
      fname: Peng
      from: KITS, CAS

    - gname: Jun
      fname: Feng
      from: "Xi'an Jiaotong University"

    - gname: Xing
      fname: Huang
      from: Northwest University


    - gname: Yang
      fname: An
      from: Zhejiang Ocean University/ KITS
    
    - gname: Alexey
      fname: Koshelev
      from: ShanghaiTech University

    - gname: Bin
      fname: Guo
      from: Central South University


    - gname: Hongbao
      fname: Zhang
      from: Beijing Normal University


    - gname: Shi
      fname: Cheng
      from: SIMIS



    - gname: Hai
      fname: Lin
      from: Southeast University


    - gname: Long
      fname: Zhao
      from: Neimunggu University


    - gname: Yuan
      fname: Sun
      from: Central South University





    - gname: Xuyao
      fname: Hu
      from: Tsinghua University


    - gname: Pan
      fname: Li
      from: KITS, UCAS


    - gname: Bowen
      fname: Chen
      from: KITS, UCAS

    - gname: Wen-Xin
      fname: Lai
      from: KITS, UCAS

    - gname: Liangyu
      fname: Chen
      from: Tsinghua University

    - gname: Zixia
      fname: Wei
      from: "Harvard University & Kyoto University" 


    - gname: Shengjia
      fname: Zhou
      from: Tsinghua University


    - gname: Guan-Cheng
      fname: Lu
      from: KITS, UCAS

    - gname: Yichen
      fname: Feng
      from: Tsinghua University

    - gname: Thomas
      fname: Wang
      from: Tsinghua University

    - gname: Jingru
      fname: Lu
      from: Tsinghua University

    - gname: Ming-Xuan
      fname: Liu
      from: USTC

    - gname: Yifan
      fname: Yao
      from: Tsinghua University

    - gname: Sirui
      fname: Shuai
      from: Tsinghua University

    - gname: Shu
      fname: Luo
      from: USTC

    - gname: Minjun
      fname: Xie
      from: Tsinghua University

    - gname: Ziqian
      fname: Hu
      from: ITP, CAS
      
    - gname: Haolin
      fname: Fan
      from: Tsinghua University

    - gname: Qiyuan
      fname: Chen
      from: Tsinghua University

    - gname: Zhengyuan
      fname: Du
      from: Tsinghua University

    - gname: Xianlai
      fname: Wu
      from: Tsinghua University

    - gname: Wenni
      fname: Zheng
      from: ICTPAP, CAS

    - gname: Kangning
      fname: Liu
      from: Tsinghua University

    - gname: Xiao-Shuai
      fname: Wang
      from: ITP, CAS

    - gname: Wenjing
      fname: Chen
      from: "Xi'an Jiaotong University"
      
    - gname: Tingkai
      fname: Chen
      from: Xiamen University

    - gname: Jinghao
      fname: Jin
      from: Xiamen University






      
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

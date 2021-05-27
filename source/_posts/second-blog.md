---
title: second-blog
date: 2020-11-21 10:43:15
tags:
---
## 宝宝的第二篇来啦

hello,there is a long time since my first blog.
today,I like ti introduce something.

```C
#include <stdio.h>
#include <math.h>
#define PI 3.14159
int main()
{
    double x,a,y;
    scanf("%lf",&x);
    a=(1+sin(PI/3))*(1+sin(PI/6))/cos(x*PI/180);
    y=sqrt(a);
    printf("%.2f",y);
    return 0;
}

```
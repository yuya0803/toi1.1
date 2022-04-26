## 説明
scanfでnの値を入力し、計算値を出るようにした。

![](2022-04-22-10-44-45.png)

#include <stdio.h>
#include "sum11.h"

int calc(int k);

int main()
{
    int n,k,sum;

    printf("n=");
    scanf("%d",&n);

    sum=calc(n);


    printf("n=%dの時=%d\n",n,sum);

    return 0;
}
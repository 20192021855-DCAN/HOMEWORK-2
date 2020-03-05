# 作业二
### 2017302580213 彭英杰 软工五班

----------
>## P5
> a. $d~end-end~ =  d~总trans~ + d~总prop~$
> 	$d~总trans~ = 3 \ast 10 \ast 12s = 6min$
> 	$d~总prop~ = 2 \ast 150km \div 100km/h = 180min$
> 	$d~end-end~ =  d~总trans~ + d~总prop~ = 186min$
> 	
> b. $d~总trans~ = 3 \ast 8 \ast 12s = 4.8min$
> 	$d~总prop~ = 2 \ast 150km \div 100km/h = 180min$
> 	$d~end-end~ =  d~总trans~ + d~总prop~ = 184.8min$
---------
>## P6
> a. 传播时延 $d~prop~ = m \div s $
>
> b. 传输时间 $d~trans~ = L \div R$
> 
> c. 端到端时延 $d~end-end~ =  d~trans~ + d~prop~ = m \div s + L \div R$
> 
> d. 该分组的最后一个比特此时刚刚离开主机A
> 
> e. 该分组的第一个比特此时在链路上传播还未到达主机B
> 
> f. 该分组的第一个比特此时已经到达主机B，正在等待其他比特
> 
> g. $d~trans~ = L \div R = d~prop~ = m \div s $
> 代入数据得：$m = L \ast s \div R = 535.71km$
---------
>## P8
>a. $3Mbps \div 150kbps = 20$
>当使用电路交换时，能支持20个用户
>
>b. 某特定用户正在传输的概率为0.1
>
>c. $p = C_{120}^n \ast 0.1^n \ast 0.9^{120-n}$
>
>d. $p =  1 - \sum_{n=0}^{20}C_{120}^n \ast 0.1^n \ast 0.9^{120-n}$
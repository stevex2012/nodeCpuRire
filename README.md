# nodeCpuRire
生存环境 node服务器，cpu持续升高分析记录

##使用atop命名查看不同时间 atop日志，记录cpu使用最高点时间点
2019123 1
* time1 2019/12/31 09:10:01 
CPU | sys       5%  | user    349% |  irq       2% |              |  idle     45% | wait      0%  | steal     0% |  guest     0% |               | ipc notavail | cycl unknown  | curf 3.10GHz |  curscal   ?% |
cpu | sys       1%  | user     89% |  irq	0% |              |  idle      9% | cpu002 w  0%  | steal     0% |  guest     0% |               | ipc notavail | cycl unknown  | curf 3.10GHz |  curscal   ?% |
cpu | sys       1%  | user     89% |  irq	0% |              |  idle      9% | cpu001 w  0%  | steal     0% |  guest     0% |               | ipc notavail | cycl unknown  | curf 3.10GHz |  curscal   ?% |
cpu | sys       1%  | user     86% |  irq	1% |              |  idle     12% | cpu003 w  0%  | steal     0% |  guest     0% |               | ipc notavail | cycl unknown  | curf 3.10GHz |  curscal   ?% |
cpu | sys       1%  | user     84% |  irq	1% |              |  idle     14% | cpu000 w  0%  | steal     0% |  guest     0% |               | ipc notavail | cycl unknown  | curf 3.10GHz |  curscal   ?% |
CPL | avg1    4.10  |              |  avg5    3.96 | avg15   3.94 |               |               | csw  3250154 |               | intr 2035975  |              |               | numcpu     4 |               |

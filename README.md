# CCNP EIGRP

https://github.com/QueenieCplusplus/Static_and_Dynamic (see dynamic routing for private IP)

https://github.com/QueenieCplusplus/Interior_and_Exterior (see interior)

RIP ＆ EIGRP 

https://github.com/QueenieCplusplus/RIP



                   IP (RIP)                  IP (RIP)
                     IPX                        IPX

                    Router    ===========    Router  

                                  EIGRP
                                  
* Router:

![r](https://camo.githubusercontent.com/416623c866865f8b8d0faebe8793da71271df2cd/68747470733a2f2f73636f6e74656e742e66747065382d322e666e612e666263646e2e6e65742f762f74312e302d392f39353232343138325f343233363838363238323939313831345f333238343432333930313432303937383137365f6f2e706e673f5f6e635f6361743d313031265f6e635f7369643d313130343734265f6e635f6f68633d41316c544d44703632686b4158384172584b68265f6e635f68743d73636f6e74656e742e66747065382d322e666e61266f683d6237653861363230613561393034386635316331373333366665646131636436266f653d3545434430394335)
                                  
* DUAL, Diffussing Update Algorithm 擴散演算法

The diffusing update algorithm (DUAL) is the algorithm used by Cisco's EIGRP routing protocol to ensure that a given route is recalculated globally whenever it might cause a routing loop. It was developed by J.J. Garcia-Luna-Aceves at SRI International.

當路徑更改時，DUAL 會傳送更動的部分而非整個路由表，當路由器儲存鄰近路徑表，且路徑異動時，路由器可以快速反應（反應時間）。

------------------------

* Routing Loop, 路由迴圈

A routing loop is a serious network problem which happens when a data packet is continually routed through the same routers over and over. The data packets continue to be routed within the network in an endless circle.

------------------------

* EIGRP has 4 functions:

- [x] build the neighbor table.

- [x] discover routes.

https://github.com/QueenieCplusplus/ND (IPv6) 

- [x] choose routes.

- [x] maintain routes.

------------------------

* EIGRP has 3 tables per router:

在此網路中，每台路由器都需要維護：

- [x] Routing Table, 路徑表

     表單建立基礎是拓樸表，記錄著到達目的地的最佳路徑稱為 Feasible Successor。

- [x] Neighbor Table, 鄰近表

- [x] Topology Table, 拓樸表

     拓樸表記錄所有目的地的路徑。

------------------------



# CCNP EIGRP

https://github.com/QueenieCplusplus/Static_and_Dynamic (see dynamic routing for private IP)

RIP ＆ EIGRP 

https://github.com/QueenieCplusplus/RIP



                   IP (RIP)                  IP (RIP)
                     IPX                        IPX

                    Router    ===========    Router  

                                  EIGRP
                                  

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

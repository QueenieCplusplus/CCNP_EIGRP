# CCNP EIGRP

RIP ＆ EIGRP 


                   IP (RIP)                  IP (RIP)
                     IPX                        IPX

                    Router    ===========    Router  

                                  EIGRP
                                  

* DUAL, Diffussing Update Algorithm 擴散演算法

The diffusing update algorithm (DUAL) is the algorithm used by Cisco's EIGRP routing protocol to ensure that a given route is recalculated globally whenever it might cause a routing loop. It was developed by J.J. Garcia-Luna-Aceves at SRI International.

當路徑更改時，DUAL 會傳送更動的部分而非整個路由表，當路由器儲存附近路徑表，且路徑異動時，路由器可以快速反應（反應時間）。

* Routing Loop, 路由迴圈

A routing loop is a serious network problem which happens when a data packet is continually routed through the same routers over and over. The data packets continue to be routed within the network in an endless circle.

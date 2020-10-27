# FAQ

## 1、高速通道的延时有多大？

UCloud会从全球骨干网中选择延时最低的线路作为用户UDPN底层实际线路，受限于不同线路跨越的实际距离、环境的不同，不同线路之间差延时差距较大，如北京二-上海二和北京二-法兰克福，一个跨大洲一个只在国内，实际距离差别也很大，这些因素会导致两条线路的延时有很大的差距。具体线路延时可联系技术支持或客户经理咨询。

## 2、高速通道是否需要两边购买？

不需要。假如购买了北京二-法兰克福的2M大小UDPN线路，那么可以实现北京与法兰克福之间双向峰值2M的带宽，即北京向法兰克福带宽为2M同时能够法兰克福向北京带宽为2M。

## 3、为什么UDPN两地监控数据不一致？网络出口峰值是什么？

UDPN是双向带宽，当购买了2M大小UDPN带宽时，A地发往B地、B地发往A地的带宽能同时到达2M，分别监控的是每个地域的出向带宽，所以监控数值不一定相同。
---
title: Odroid Hadoop Cluster
layout: entry
description: 오드로이드를 사용한 하둡 클러스터 구축
tags: [Odroid, Hadoop, Cluster, 오드로이드, 하둡, 클러스터]
published: false
comments: true
---

하둡을 공부하면서 완전분산모드를 사용하기위한 클러스터를 구축할때 일반 PC를 사용하기에는 비용이나 공간이 부족한 경우가 많다. 그렇기 때문에 싱글보드를 사용하여 저비용 클러스터를 구축하고 최적화하여 하둡을 공부하는데 충분한 클러스터를 구축하려고 한다. Raspberry Pi를 사용하여 구축하는 방법은 다른 블로그나 구글에 검색하면 많은 방법이 나오기 때문에 가지고 있던 Odroid C1+를 사용하여 하둡 클러스터를 구축하는 방법을 기록하였지만 Raspberry Pi에서도 비슷하게 적용 할 수 있을거라 생각된다.

<img src="/assets/2017-09-08/cluster-server.png" style="margin: 0 auto;">
<figcaption>
	구축한 Odroid C1+ Cluster, 이상태로 사용하였다ㄴ
</figcaption>

1. Ubuntu 16.04 설정


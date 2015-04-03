**GitBook GrViz Plugin**
==============

This is a sample plugin for GitBook. Gitbook GrViz plugin is used to select from markdown dot and converting it into a picture format svg.

**Example:**

*Text format dot:*
---dot
digraph g {

	overlap=false;
	rankdir = BT;
	node [shape=record];
	subgraph Atlantis {
		Tour;
		Order;
		CollectionPoint;
		TakePointTourist;
		TransportOwner;
		BusItem;
		ReturnPointTourist;

		Tour -> Order[label="" len=4.00];
		Order -> Tour[label="" len=4.00];
		CollectionPoint -> TakePointTourist[label="" len=4.00];
		TransportOwner -> BusItem[label="" len=4.00];
		CollectionPoint -> ReturnPointTourist[label="" len=4.00];
	}
}
---


***Image dot.***

**How to use it:**
--------------
安装gitbook

npm install codepiano/gitbook -g

要在工程目录里面运行gitbook
比如 gitbook server ../test

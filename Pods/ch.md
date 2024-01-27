<h1>POD?</h1>

Pod is single instace. ポットはシングルインスタンス。

The Container is encapsulated known as Pods.

Pod is small object you can create in kubernetes.

What if the user base further increases and current node has no sufficient capacity? 
1. Add new POD in current cluster.
2. Add new POD in new node to expand the cluster's physical capacity.

The point is that Pods usually have a one-to-one relationship with container


<h1>Multi-Container PODs</h1>
In face, Pod can have multiple containers. this mean that pod have helper conatiner. 
Two containers can also communicate with each other directly by referring to each other as local host. 

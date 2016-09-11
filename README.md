# cicmi
Cloud Infrastructure Common Management Interface - CICMI

Just like a router or switch device, also like a linux box, users can use the terminal to manage them, what should we have in a public cloud env in this period?

在当今的云计算领域，貌似还没有一个统一的接口，去兼容，哪怕是把各家的 API 统一到一个程序里来，创建资源啥的还是需要去 WEB 页面，费时费力，如果有这么个玩意儿，把云计算的基础设施当成了一个基础操作系统，类似于 linux 管理 PC ， cicmi 会来管理云计算资源。

| command | description |
| -- | -- |
| ssh xxx@xxx | connect the cloud management interface |
| show infrastrutures | list the Machine clusters that have its own vms and the firewall |
| use infrastruture my1 | enter the context of the one infrastrues |
| show vms | list the vms in the my1 |
| show routers | list the router in the my1|
| show firewall | list the firewall config that what port open or what port close in my1 |
| create infrastrutures my2 | create a new cluster |
| use my2 | enter the new infrastructures |
| create new vm myvm2-1 | create a new vm |
| create new vm myvm2-2 | create a new vm |
| create new router my2-router | create a router |

#面向中小汽车零部件企业的BOM明细表系统#
##需求：##
+   1.实现BOM明细的分权限查询；
+   2.实现BOM明细的添加、修改、保存、和删除，基于权限管理；
+   3.BOM明细应该是产品系列->按总成->分总成->零部件 的结构；
+   4.尽量不适用sql服务器，或者使用sqlite3，便于小型化管理；
+   5.基于B/S结构，便于部署。

##产品/零部件数据结构（对象构成）：##
+   1.[产品的定义](./public/product.md)
+   1.[Product]:    ./public/product.md "产品的定义"
+   1.[Part]:  ./public/part.md  "部件的定义"
+   2.[Element]:    ./public/element.md "零件定义" 

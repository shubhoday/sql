# sql
select productname, oi.quantity, oi.unitprice from orders 0, products p, orderitem oi where o.orderid=oi.orderid and p.productid=oi.productid;

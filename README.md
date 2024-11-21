SQL> create table order(
SQL> create table orders(
SQL> select*from sxe3130.customer;
SQL> select * from sxe3130.customer;
SQL> create table orders(
SQL> select * from kxs1446.driver;
SQL> select * from wxs5823.employee;
SQL> insert into driver values(10000103,'50012365','02-MAY-2024','NYP 1546');
SQL> insert into kxs1446.driver values(10000103,'50012365','02-MAY-2024','NYP 1546');
SQL> grant all on kxs1446.driver where in(kxs1446,sxe3130,hxs2723,wxs5823);
SQL> grant all on kxs1446.driver to kxs1446,sxe3130,hxs2723,wxs5823;
SQL> select * from kxs1446.driver;
SQL> select* from kxs1446.sales_rep;
SQL> select * from kxs1446.sales_rep;
SQL> desc sxe3130.customer;
SQL> desc sxe3130.customer;
SQL> desc sxe3130.customer;
SQL> select * from sxe3130.customer;
SQL> desc sxe3130.customer;
SQL> desc sxe3130.customer;
SQL> insert into sxe3130.customer values(7103,'23 bowen st', 'arlington',76310,'Mike jackson',6459327612,'MNGC');
SQL> insert into sxe3130.customer values(7103,'23 Bowen','arlington',76310,'Mike jackson',6459327612,'MNGC');
SQL> grant all on sxe3130.customer to kxs1446,sxe3130,hxs2723,wxs5823;
SQL> select * from sxe3130.customer;
SQL> select * from sxe3130.customer;
SQL> desc orders;
SQL> alter table orders modify del_address varchar2(30);
SQL> alter table orders modify del_address varchar2(30) disable table lock;
SQL> insert into orders values(41003,7103,10000102,'NYP 1546', '05-MAY-2023','Dropoff','10-MAY-2023','23 Bowen arlington 76310');
SQL> desc sxe3130.item;
SQL> select * from sxe3130.item;
SQL> select * from orders;
SQL> insert into sxe3130.item values(03,'Moniter',120,50);
SQL> grant all on sxe3130.item to sxe3130,wxs5823,kxs1446,hxs2723;
SQL> select * from sxe3130.item;
SQL> select * from sxe3130.item;
SQL> select * from sxe3130.item;
SQL> select * from sxe3130.item;
SQL> create table order_item(
SQL> ALTER TABLE ORDERS ENABLE TABLE LOCK;
SQL> create table order_item(
SQL> grant all on orders to kxs1446,wxs5823,sxe3130,hxs2723;
SQL> select * from order_item;
SQL> grant all on order_item to kxs1446,wxs5823,sxe3130,hxs2723;
SQL> insert into order_item values(41003,03,150,7);
SQL> grant all on order_item to kxs1446,wxs5823,sxe3130,hxs2723;
SQL> select * from order_item;
SQL> alter table order_item add constraints primary key where column ='item_code';
SQL> alter table order_item drop primary key(order_id);
SQL> drop table order_item;
SQL> create table order_item(
SQL> grant all on order_item to kxs1446,wxs5823,sxe3130,hxs2723;
SQL> select * from order_item;
SQL> insert into order_item values(41003,03,150,3);
SQL> insert into order_item values(41003,07,350,3);
SQL> grant all on order_item to kxs1446,wxs5823,sxe3130,hxs2723;
SQL> select * from order_item;
SQL> select * from order_item;

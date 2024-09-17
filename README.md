create database Tbrasileirao;
use  TBbrasileirao;

create table A(
id int primary key,
time1 varchar(50) not null,
pontos int,
golpro int,
golcont int,
saldogol int
);

describe A;

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(1,'Grêmio',114,76,0,76);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(2,'Palmeiras',97,80,10,70);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(3,'Bahia',80,64,23,41);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(4,'Botafogo',77,69,44,25);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(5,'Fluminense',69,32,9,23);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(6,'Flamengo',47,27,15,12);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(7,'Fortaleza',36,38,23,15);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(8,'São Paulo',30,20,11,9);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(9, 'Vitória',15,7,3,4);

insert into A(id,time1,pontos,golpro,golcont,saldogol)
value(10,'Inter',0,0,77,-77);

select * from A;

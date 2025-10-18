<img width="1278" height="590" alt="IMG_1326" src="https://github.com/user-attachments/assets/eb27b1da-2c9e-4731-b4d7-cbaf31995b51" />
)
# hafta4
loan
create database loan;
go

use loan;
go
create table customer(
costomer_name int,
adress varchar);

create table collector(
collector_id int,
collector_name varchar);
create table loanconract(
data_contract_start date,
date_concract_ends date,
interes_rate varchar,
loan_amount smallmoney,
loan_payment_frequency smallmoney,
loan_paymeny_due_date date,);

create table payment_type(
payment_type_code int,
payment_type_description varchar);

create table payment(
payment_id int,
data_of_payment date);

use loan;
go
alter table payment
add collector İd int,customer

after table payment
add contractid int payment;

# Types of Keys in DBMS
---
## *A Sample Database*

| Name | Id 🔑 | Address | Passport No. | Subject |
|:-----|:-----|:--------|:-------------|:--------|
|Pratik|1|Dang|0011|Travel|
|Darshan|2|Kawasoti|0012|Study|

## Super Key
> Super key is a group of single or multiple keys that identifies rows in a table. It includes all other possible keys and is a super set of keys.

**Super Key** = {***Name***,***Id***,***Address***,***Passport No***,***Subject***}

## Candidate Key
> It is a set of key that can uniquely idenitfy a tuple. It containst unique values. It is the set of all possible primary keys.

**Candidate Key** = {***Id***,***Passport No***}

## Primary Key 
> Out of multiple candidate keys, **primary key** is the chosen unique key indentifier which has unique values and identifies the tuple uniquely.

**Primary Key** ={***Id***}

## Alternate Key 
> The candidate key other than the primary key is the
alternate key. It can be the substitute to the primary key if needed.

**Alternate Key** ={***Passport No***}

## Foreign Key
> It is the key which acts as primary key in one table and secondary key in another table.

#### Database 1

| Name | Id 🔑 | Address | Passport No. | Subject |
|:-----|:-----|:--------|:-------------|:--------|
|Pratik|1|Dang|0011|Travel|
|Darshan|2|Kawasoti|0012|Study|

#### Database 2

| Id | Project No 🔑| Project title |
|:--|:--|:--|
|1|101|Robotics|
|2|102|Physics|

**Foreign Key** = { ***Id*** }
<mark>Here, Id is primary key in Database 1 and secondary key in Database 2.

## Composite Key
> It is the combination of unique indentifer key and other key which can be represented uniquely together.

**Composite Key** = { ***Id***, ***Name*** }

## Artificial Key 
> It is the artificially addded key which can uniquely identify data from another table.

#### Database 1

| Name | Id 🔑 | Address | Passport No. |Subject |<mark> Code |
|:-----|:-----|:--------|:-------------|:--------|:--|
|Pratik|1|Dang|0011|Travel|ABC|
|Darshan|2|Kawasoti|0012|Study|XYZ|

##### Database 2

|<mark>Code| Detail |
|:--|:--|
|ABC|fun|
|XYZ|study|

**Artificial Key** = { ***Code*** }






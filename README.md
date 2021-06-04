# PhP Crud

In this Development I can implement the PHP crud System.
Here you can add a Data of Student, Modify Data and Delete the Data.
All this developmet are in core PHP.

For run this program you can need to Create Data Base named "crud".
After creating database you need to add Two tables.
Table1===

student{sid, sname, saddress, sclass, sphone}
}
 


 Table1===

 studentclass{cid, cname}





crud

student

Column			Type		Null	Default	Links to	Comments	Media (MIME) type
sid (Primary)	int(10)		No				
sname			varchar(30)	No				
saddress		varchar(50)	No				
sclass			int(10)	No				
sphone			varchar(10)	No				

Indexes

Keyname		Type	Unique	Packed	Column	Cardinality	Collation	Null	Comment
PRIMARY		BTREE	Yes		No		sid		6			A			No	

studentclass

Column			Type		Null	Default	Links to	Comments	Media (MIME) type
cid (Primary)	int(11)		No				
cname			varchar(15)	No				

Indexes

Keyname	Type	Unique	Packed	Column	Cardinality	Collation	Null	Comment
PRIMARY	BTREE	Yes		No		cid		4			A			No	



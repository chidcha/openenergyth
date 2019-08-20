## Open Energy Data Thailand JSON Web Service Document 

One of example [Android App: 	
Open Energy Data Thailand Technology](https://play.google.com/store/apps/details?id=iniac.ict.scu.psu.energy.statistics.of.thailand) to use and implement an app by using the following services.

Service [1_energy_value](http://interfo-rc.com/energy/energyvalue/1_energy_value.php)

URL : http://interfo-rc.com/energy/energyvalue/1_energy_value.php

Description : แสดงมูลค่าพลังงาน

Type : GET Request

Parameters : 

| ค่าที่ส่ง         | 	  คำอธิบาย	| ค่าที่อนุญาต	     |              ค่าเริ่มต้น |
| ------------- | ------------- | ------------- | ------------- |
|min	 |   ปีเริ่มต้น	  |                  2535 – 2559	         |       2535|
|max	 |   ปีสิ้นสุด	   |                   2535 – 2559	     |           2559|
|type	 | รูปแบบข้อมูล	  |                1 = สรุปค่าใช้จ่ายด้านพลังงาน    |  1|
 |||                                    2 = สรุปค่าใช้จ่ายด้านน้ำมัน||                         
 |||                                  3 = สรุปมูลค่าการนำเข้าพลังงาน	||                               
|all	|   แสดงค่าแบบ 1 label / 1 data	  |0,1	                      |     0|

ตัวอย่าง : '1_energy_value.php?min=2550&max=2555&type=2&all'


Service : [1_energy_value_detail] (http://interfo-rc.com/energy/energyvalue/1_energy_value_detail.php)

URL : http://interfo-rc.com/energy/energyvalue/1_energy_value_detail.php

Description : แสดงมูลค่าพลังงาน > ข้อมูลรายปี (สถิติรายปี)

Type : GET Request

Parameters : 


| ค่าที่ส่ง         | 	  คำอธิบาย	| ค่าที่อนุญาต	     |              ค่าเริ่มต้น |
| ------------- | ------------- | ------------- | ------------- |
|min	 |   ปีเริ่มต้น	  |                  2535 – 2559	         |       2535|
|max	 |   ปีสิ้นสุด	   |                   2535 – 2559	     |           2559|
|subtype|	หมวดหมู่ย่อย	|Electricity|-|
|||Lignite/Coal||
|||Natural Gas||
|||Petroleum Products Renewable Energy|-|
|type	|รูปแบบข้อมูล	|1 = สรุปค่าใช้จ่ายด้านพลังงาน|1|
||2 = สรุปค่าใช้จ่ายด้านน้ำมัน||
||3 = สรุปมูลค่าการนำเข้าพลังงาน	||
|all	|แสดงค่าแบบ 1 label / 1 data	|1|	0|

ตัวอย่าง : '1_energy_value_detail.php?type=1&subtype=Electricity&min=2549&max=2559'


### Support or Contact

Having trouble with Pages? Check out our [Chidchanok Choksuchat](mailto:cchoksuchat@hotmail.com?subject=[GitHub]%20Source%20Thailand%20Open%20Energy%20Data)) and we’ll help you sort it out.

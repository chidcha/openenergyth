## Open Energy Data Thailand JSON Web Service Document 

One of example [Android App: 	
Open Energy Data Thailand Technology](https://play.google.com/store/apps/details?id=iniac.ict.scu.psu.energy.statistics.of.thailand) to use and implement an app by using the following services.

Service [1_energy_value](http://interfo-rc.com/energy/energyvalue/1_energy_value.php)

URL : http://interfo-rc.com/energy/energyvalue/1_energy_value.php

Description : แสดงมูลค่าพลังงาน

Type : GET Request

Parameters : 

ค่าที่ส่ง	  คำอธิบาย	                  ค่าที่อนุญาต	                  ค่าเริ่มต้น

min	    ปีเริ่มต้น	                    2535 – 2559	                2535

max	    ปีสิ้นสุด	                      2535 – 2559	                2559

type	  รูปแบบข้อมูล	                  1 = สรุปค่าใช้จ่ายด้านพลังงาน      1

                                     2 = สรุปค่าใช้จ่ายด้านน้ำมัน
                              
                                     3 = สรุปมูลค่าการนำเข้าพลังงาน	
                               
all	   แสดงค่าแบบ 1 label / 1 data	  1	                           0

ตัวอย่าง : 1_energy_value.php?min=2550&max=2555&type=2&all


### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/chidcha/openenergyth/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

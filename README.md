# Power-BI
Power BI
คำสั่ง DAX ที่จำเป็น
1. การจัดหมวด
- คอลัมน์ใหม่ = SWITCH(
                TRUE(), 
                Table2[Column1] In {"Shirts","Sweaters","Jeans","Shorts"},"Clothes",
                Table2[Column1] In {"Sneakers","Boots","Sandals","Slippers"},"Shoes",
                "Other"
                ) 
2. การคำนวณแบบมีเงื่อนไข ด้วยคำสั่ง Calculate:
- CALCULATE(<expression>[, <filter1> [, <filter2> [, …]]])
  โดย 
  expression	คือนิพจน์ที่ต้องการหาค่า 
  filter1, filter2,…	(Optional) คือ เงื่อนไขทางตรรกศาสตร์เพื่อการกรองข้อมูล หรือฟังก์ชันการกรองข้อมูล 
  ตัวอย่างการใช้งาน
  2.1 dddd
  2.2 kkkk
  








หมายเหตุ คำสั่ง readme.md file (https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

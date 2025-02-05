#  แบบสอบถามความพึงพอใจของร้านค้า ชุมชนคนสุขสยาม

This project, a customer satisfaction survey for stores, is part of the Introduction to Data Science course. It focuses on applying knowledge in Data Preparation and Cleaning, Data Visualization and Data Analysis to ensure the data is clean and ready for in-depth analysis. The project is conducted using Python, which serves as a key tool for data processing and presenting insights in a clear and meaningful way to support decision-making.
<p align="center"><img width="600" src = "https://github.com/user-attachments/assets/09e3d46d-5978-41f0-b1b4-4b512ce0118e"></p>


## Datasets
- **Dataset Name**: แบบสอบถามความพึงพอใจของร้านค้า
- **Size**: 258 แถว 19 หลัก
- **Dataset Description**: ชุมชนคนสุขสยาม แบบสอบถามความพึงพอใจของร้านค้า
<p align="center"><img width="1000" src = "https://github.com/user-attachments/assets/6e1be32c-d800-49b6-b5c9-2ec93e2ccbba"></p>

## Data Preparation and Cleaning
1. ทำการตรวจสอบข้อมูล พบว่าข้อมูลไม่ครบถ้วนทุกแถว ตรงบริเวณของคอลัมน์ “ข้อเสนออื่นๆ” พบว่าข้อมูลมีไม่ครบทุกแถว จึงได้ทำการแทนการไม่มีข้อมูลโดยคีย์เวิร์ด na_values และใช้ keep_default_na = 0
2. ทำการเตรียมข้อมูล โดยการเปลี่ยนชื่อส่วนหัวของข้อมูล เนื่องจากส่วนหัวมีความยาวมากเกินไป โดยส่วนหัวของข้อประเมินทั้ง 10 ข้อเปลี่ยนเป็น bf คือการประเมินก่อนขาย และ bt คือการประเมินระหว่างการขาย และคอลัมน์ของ “ท่านจำหน่ายสินค้าในพื้นที่บริเวณใด(บริเวณพื้นที่” เป็นบริเวณพื้นที่แทน
3. นำข้อมูลที่เตรียมเสร็จเรียบร้อยไปใช้เพื่อหาคำตอบของคำถามที่ตั้ง

## Research Questions
1. จำนวนผู้เข้าร่วมจัดร้านค้าในกรุงเทพมหานครและปริมณฑล ที่มีความสนใจจะมาร่วมจัดงานในครั้งต่อไป
2. เปรียบเทียบจำนวนคนที่มาแน่นอน คนที่ไม่แน่ใจ และคนไม่มา ซึ่งเป็นผู้ประเมิณที่ขายสินค้าในงาน ที่ให้คะแนนการประเมิณ 4 ทุกหัวข้อ  
3. ค่าเฉลี่ยคะแนนความพึงพอใจเจ้าของกิจการกับพนักงานขายมีต่อการจัดงานครั้งนี้

## Visualization
<p align="center"><img width="600" src = "https://github.com/user-attachments/assets/18fb6155-bd3e-44e4-b58f-5905ac871240"><br>
<img width="400" src = "https://github.com/user-attachments/assets/727a61cb-d6d4-4e83-aecb-82a72ff6325a">
<img width="400" src = "https://github.com/user-attachments/assets/0c94cc8d-eba9-4e55-81a0-1f1023d1674d"></p>



## Getting Started
To run this app on jupyter notebook or Google Colab, follow these steps:

1. Clone this repository to your local machine using `git clone https://github.com/mmaitty01/DataAnalysis_satisfaction.git `Alternatively, you can download the project as a ZIP file and extract it.

2. Open the .ipynb file using Jupyter Notebook or any compatible platform.

3. Ensure the survey Excel file is in the same directory as the notebook.

4. Run the notebook cells sequentially to analyze the data.

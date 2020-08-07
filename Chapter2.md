# Types of Data sets
## Record Data 
1. Relational records เป็นการใช้ Index หรือ ID ใช้เชื่อมข้อมูลของตารางนึงไปยังตารางนึง เช่น เลขบัตรประชาชน
2. Data matrix เป็นการเก็บข้อมูลที่ตารางมีหัวข้อสองฝั่ง
3. Transaction data เป็นการเก็บข้อมูลที่ไม่มีหัวข้อ แค่เรียงๆ ขั้นด้วย comma
4. Document data เป็นการเก็บข้อมูลที่มี attributes ด้านบน และ ตัวบอกตัวตนด้านข้าง เหมือน ตารางทั่วไป
## Graphs and network
1. กราฟ
2. แผนที่
3. ข้อมูลเพื่อนในเฟสที่เชื่อมโยงกัน (ไม่แน่ใจ)
## Ordered Data
1. video : ลำดับของรูปภาพ
## Spatial, image and multimedia Data
1. Spatial Data เช่น แผนที่
2. รูปภาพ
3. วิดีโอ
# Important Characteristics of structered Data
Dimensionality เป็นการเชื่อมต่อกันแต่ละมิติ
Sparsity จุดที่ไม่มีข้อมูลก็จะเป็นช่องว่าง มีช่องว่างอยู่
Resolution เป็นเรื่องของรายละเอียดภาพ ที่ต้องปรับสเกลให้มันเท่ากัน
Distribution อธิบายข้อมูลด้วยค่ากลางและการกระจาย
# Data objects
Row = Data objects; Columns = attributes 
Data objects เรียกได้หลายแบบ data points หรือ records
# Attributes 
สามารถ เรียกได้ว่า features หรือ dimensions
ชนิดของ Attributes มีหลายชนิด 
1.Nominal(ไม่เป็นตัวเลข)
2.Binary(มีสองค่าเท่านั้น) เช่น Nominal attributes(0 and 1), Symmetric binary(เพศ น้ำหนักของค่าเท่ากัน) และ Asymmetric binary(ความสำคัญไม่เท่ากัน)
3.Ordinal(เรียงลำดับได้)
4.Numeric เช่น Interval ไม่มีค่าศูนย์แท้ คือเป็นศูนย์ที่ถูกนิยามขึ้น อย่างเช่น อุณหภูมิ, Ratio มีศูนย์แท้
# Discrete Attribute and continous Attributes
ต่อเนื่อง กับ ไม่ต่อเนื่อง

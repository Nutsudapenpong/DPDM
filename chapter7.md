Classification
features = ลักษณะ แทนด้วย x
target = เป้าหมาย แทนด้วย y
 
1. KNN บทที่ 9 (Lazy learner เพราะ มันไม่ต้องสร้างโมเดล)  K เท่ากับ 3 คือเอาตัวใกล้สุด 3 ตัว แล้วโหวตว่าคำตอบไหนเยอะกว่า กำหนดเป็นเลขคี่ดีกว่าจะได้ไม่โหวตเท่ากัน     
Data > Train + Test > K-fold cross validation (k=3) Train จากขั้นตอนก่อนหน้า จะถูกแบ่งเป็น 3 ส่วน รอบที่ 1 Train1 เป็น Test Train2,3 เป็น Train รอบ 2 เปลี่ยน Train2 เป็น Test ที่เหลือเป็น train และ รอบที่ 3 เหมือนเดิม สุดท้ายเอาโมเดลเดียวกันมาเทียบกัน อันไหนดีสุดก็เอาอันนั้น สุดท้ายเอา Train รวมกันอีกและ Train และ Test เดิมมาใช้ ละก็จะได้ความแม่นยำออกมา
2. Decision tree 
3. Logistic regression
4. Neural network

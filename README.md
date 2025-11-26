### สรุปเนื้อหาบทนำสู่ Data Mining
## 1. Data Mining คืออะไร?

* **คำนิยาม:** Data Mining คือการดึง **รูปแบบหรือความรู้ที่น่าสนใจ** (Interesting Patterns) ซึ่งไม่ชัดเจน ซ่อนเร้น ไม่เคยรู้มาก่อน และอาจมีประโยชน์ ออกมาจากชุดข้อมูลขนาดใหญ่
* **ชื่อเรียกอื่น ๆ:**
    * Knowledge Discovery in Databases (**KDD**)
    * Knowledge Extraction
    * Data/Pattern Analysis
    * Business Intelligence
* **กระบวนการ KDD (Knowledge Discovery from Data):**
    * Data Mining เป็นเพียง **ส่วนสำคัญ** ของกระบวนการ KDD ทั้งหมด 


<img width="660" height="472" alt="image" src="https://github.com/user-attachments/assets/cc459e0b-a9f2-494c-9094-6870eaec5145" />


    * กระบวนการเริ่มต้นจาก: **Data Cleaning** (การทำความสะอาด), **Data Integration** (การรวมข้อมูล)
    * ตามด้วย: Selection, Transformation, **Data Mining**, Pattern Evaluation และ Knowledge Presentation

---

### 2. มุมมองหลายมิติของ Data Mining (Multi-Dimensional View)

Data Mining สามารถจำแนกได้ตามมิติต่าง ๆ ดังตาราง:

| มิติ | รายละเอียด (Mineable Data Types / Functionalities / Technologies / Applications) |
| :--- | :--- |
| **2.1 ข้อมูลที่สามารถทำเหมืองได้** | **ฐานข้อมูลแบบดั้งเดิม:** ฐานข้อมูลเชิงสัมพันธ์ (Relational), Data Warehouse<br>**ข้อมูลเชิงธุรกรรม:** Transactional Data<br>**ข้อมูลที่มีมิติเวลาและอวกาศ:** Data Stream, Spatiotemporal Data, Time-Series Data<br>**ข้อมูลโครงสร้างไม่แน่นอน:** Text/Web Data, Multimedia Data<br>**ข้อมูลความสัมพันธ์:** Graphs และ Social/Information Networks |
| **2.2 ฟังก์ชัน/ความรู้ที่ต้องการขุดค้น** | **Descriptive Mining (บรรยาย):** Characterization (จำแนกลักษณะ), Discrimination (เปรียบเทียบ)<br>**Predictive Mining (คาดการณ์):** Association (ความสัมพันธ์), Classification (จัดกลุ่มด้วยโมเดล), Clustering (แบ่งกลุ่มด้วยตัวเอง), Outlier Analysis (วิเคราะห์ข้อมูลผิดปกติ) |
| **2.3 เทคนิคที่ใช้** | Data-intensive computing, Data Warehouse (**OLAP**), **Machine Learning**, Statistics, Pattern Recognition, Visualization, High-Performance Computing |
| **2.4 แอปพลิเคชัน/การประยุกต์ใช้** | ธุรกิจค้าปลีก, โทรคมนาคม, ธนาคาร (การตรวจจับการทุจริต), ชีวสารสนเทศ (**Bio-data Mining**), การวิเคราะห์ตลาดหุ้น, Web Mining |

---

### 3. ประเด็นสำคัญใน Data Mining (Major Issues)

Data Mining ต้องเผชิญกับความท้าทายหลักใน 4 ด้าน:

| ประเด็นหลัก | รายละเอียดความท้าทาย (Issues) |
| :--- | :--- |
| **3.1 ระเบียบวิธี (Methodology Issues)** | - การขุดค้นความรู้ใหม่ ๆ ในมิติที่ซับซ้อน<br>- การจัดการกับข้อมูลที่มีสัญญาณรบกวน (**Noise**), ความไม่แน่นอน (**Uncertainty**), และความไม่สมบูรณ์ (**Incompleteness**)<br>- การผสานรวมความรู้พื้นฐาน (Background Knowledge) เข้ากับกระบวนการ |
| **3.2 ปฏิสัมพันธ์กับผู้ใช้ (User Interaction Issues)** | - การทำเหมืองแบบโต้ตอบ (**Interactive Mining**)<br>- การนำเสนอผลลัพธ์ผ่าน **Visualization** ที่เข้าใจง่ายและมีประสิทธิภาพ |
| **3.3 ประสิทธิภาพและการขยายขนาด (Efficiency and Scalability Issues)** | - Algorithm ที่ต้องรองรับ **Big Data** (ข้อมูลขนาดใหญ่มาก) ได้อย่างมีประสิทธิภาพ<br>- การทำเหมืองแบบขนาน (**Parallel, Distributed**) เพื่อเพิ่มความเร็วในการประมวลผล |
| **3.4 สังคม (Society Issues)** | - ผลกระทบทางสังคมและจริยธรรมของ Data Mining<br>- การทำเหมืองที่รักษาความเป็นส่วนตัว (**Privacy-preserving Data Mining**) |

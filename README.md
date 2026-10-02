# shop_aff_fe

QC Dashboard (Next.js) ของระบบทำคลิปขายสินค้าด้วย AI → Shopee Video
Backend: `shop_aff_be` · แผนเต็ม: `plan.md` (หัวข้อ 3.1)

## หน้าที่จะมี (เฟส 4)

| หน้า | ทำอะไร |
|---|---|
| Login | สิทธิ์ viewer / qc / admin |
| คิวรอ QC | ดูคลิป + caption + สคริปต์ + คำเตือน → อนุมัติ / แก้ / gen shot ใหม่ / ทิ้ง |
| ปฏิทินโพสต์ | คลิปที่ตั้งเวลาไว้ |
| สินค้า | เลือกสินค้า, กรอกข้อมูลยืนยันได้ (ส่วนผสม, เลข อย.) |
| สถิติ | วิว / คลิก / ยอดขาย ต่อคลิป, template, hook |
| ตั้งค่า | งบต่อวัน, โมเดล AI, เสียง, template, คำห้าม, เชื่อมร้าน Shopee |
| Log & ค่าใช้จ่าย | งานล้ม, ต้นทุน |

Stack: Next.js + Tailwind + TanStack Query · type ของ API generate จาก Swagger ของ BE

## สถานะ

⏳ ยังไม่เริ่ม — ทำหลัง BE pipeline + Shopee API (เฟส 4)

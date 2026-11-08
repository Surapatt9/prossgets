# prossgets

## Claude API (Python)

ติดตั้ง Anthropic Python SDK และตัวช่วยโหลดค่าจากไฟล์ environment:

```sh
python -m pip install -r requirements.txt
```

คัดลอก `.env.example` เป็น `.env` แล้วกำหนด `ANTHROPIC_API_KEY` ด้วย API key ของคุณเอง (ห้าม commit หรือแชร์ไฟล์ `.env`). ในแอป Python ให้อ่านคีย์จาก environment เช่น `os.environ["ANTHROPIC_API_KEY"]`; หากใช้ไฟล์ `.env` ในเครื่อง ให้โหลดด้วย `python-dotenv`. ยังไม่มีการเพิ่มการเรียก API หรือฟีเจอร์แชตใน repository นี้
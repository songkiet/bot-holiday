# BOT Holiday

เป็น DB ให้ [Apps Script](#google-apps-script) ทำงาน ส่งข้อมูลไปยัง [Google Calendar](#public-google-calendar-bot-holidays)

และก็ยังเป็นเสมือน API ได้โดยเรียก GET ได้ที่ [bot-holiday.txt](https://raw.githubusercontent.com/songkiet/bot-holiday/main/bot-holiday.txt) หรือ [bot-holiday-yyyyMMdd.txt](https://raw.githubusercontent.com/songkiet/bot-holiday/main/bot-holiday-yyyyMMdd.txt)

เนื่องจาก BOT ไม่มี API หรือ Service ให้เรียกใช้ มีแค่การเผยแพร่ข้อมูลผ่านหน้าเว็บไซต์

**BOT Offical Website:**
- **THA** https://www.bot.or.th/Thai/FinancialInstitutions/FIholiday/Pages/2021.aspx
- **ENG** https://www.bot.or.th/English/FinancialInstitutions/FIholiday/Pages/2021.aspx

# Release Version Number

ตอนนี้ยังไม่มี ความหมาย/รูปแบบ อะไร มีไว้เพียงแค่...

เพื่อให้สามารถกด Watch repo นี้ได้ (GitHub จะช่วยส่งอีเมล์/Notification แจ้งเตือนเมื่อวันหยุดธนาคารมีการเปลี่ยนแปลง)

ทุกครั้งที่มีการเปลี่ยนแปลงวันหยุดธนาคาร GitHub Actions จะทำการออก Release ใหม่เลย เลข Version จะแค่เพิ่ม +1 ที่ตำแหน่ง minor ไปเรื่อย ๆ

# Public Google Calendar (BOT Holidays)

## วิธีเพิ่มปฏิทิน

**ตัวเลือก 1**
1. เปิด [Link นี่](https://calendar.google.com/calendar/u/0?cid=Y3VqdW5wY2hjcG12bWxscDRxdHBndjZjbmdAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ)
2. จะมี Popup ขึ้นมา ก็กดปุ่ม Add

**ตัวเลือก 2**
1. เข้าไป [ที่นี่](https://calendar.google.com/calendar/u/0/r/settings/addbyurl)
2. กรอกที่ช่อง URL of calendar ว่า
  ```
  https://calendar.google.com/calendar/ical/cujunpchcpmvmllp4qtpgv6cng%40group.calendar.google.com/public/basic.ics
  ```

3. กดปุ่ม Add calendar

# Google Apps Script
**(Private Project)**
- https://script.google.com/home/projects/1Zy7YDZRyuNRwfLIem9Lpo7XHPWm9vXuf0S1LrNDYp5i-ssPg9QrDr6m9/edit

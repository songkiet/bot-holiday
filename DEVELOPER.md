# BOT Holiday

Repo นี้ใช้เป็น DB เฉยๆ เพื่อให้ [Apps Script](#google-apps-script) ทำงาน ส่งข้อมูลไปยัง [Google Calendar](#public-google-calendar-bot-holidays)

และก็ยังพอจะใช้เป็น API ได้ โดยเรียก GET request ไปที่ [bot-holiday.txt](https://raw.githubusercontent.com/songkiet/bot-holiday/main/bot-holiday.txt) หรือ [bot-holiday-yyyyMMdd.txt](https://raw.githubusercontent.com/songkiet/bot-holiday/main/bot-holiday-yyyyMMdd.txt)

เนื่องจาก BOT ไม่มี API หรือ Service ให้เรียกใช้ มีแค่การเผยแพร่ข้อมูลผ่านหน้าเว็บไซต์ https://www.bot.or.th/th/financial-institutions-holiday.html

# Release Version Number

ตอนนี้ยังไม่มี ความหมาย/รูปแบบ อะไร มีไว้เพียงแค่...

เพื่อให้สามารถกด Watch repo นี้ได้ (GitHub จะช่วยส่งอีเมล์/Notification แจ้งเตือนเมื่อวันหยุดธนาคารมีการเปลี่ยนแปลง)

ทุกครั้งที่มีการเปลี่ยนแปลงวันหยุดธนาคาร GitHub Actions จะทำการออก Release ใหม่เลย เลข Version จะแค่เพิ่ม +1 ที่ตำแหน่ง minor ไปเรื่อย ๆ

# Public Calendar (BOT Holidays)

## วิธีเพิ่มปฏิทิน

### Google Calendar
กด [Link นี่](https://calendar.google.com/calendar/u/0?cid=Y3VqdW5wY2hjcG12bWxscDRxdHBndjZjbmdAZ3JvdXAuY2FsZW5kYXIuZ29vZ2xlLmNvbQ) ได้เลย
(หรืออีกวิธี อ่านจาก[ที่นี่](https://support.google.com/calendar/answer/37100) แล้วคัดลอก URL "iCal format" ด้านล่างไปใช้)

### Apple Calendar
อ่านวิธีจากที่นี่: https://support.apple.com/th-th/102301 แล้วคัดลอก URL "iCal format" ด้านล่างไปใช้

### URL "iCal format"
สำหรับคัดลอกไปใช้:
  ```
  https://calendar.google.com/calendar/ical/cujunpchcpmvmllp4qtpgv6cng%40group.calendar.google.com/public/basic.ics
  ```

# Google Apps Script
**(Private Project)**
- https://script.google.com/home/projects/1Zy7YDZRyuNRwfLIem9Lpo7XHPWm9vXuf0S1LrNDYp5i-ssPg9QrDr6m9/edit

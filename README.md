# cs2autoexec

autoexec CS2 by babylaaaamp

## วิธีติดตั้ง

1. โหลด `autoexec.cfg`
2. วางไว้ที่:
   `Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\`
3. Steam > CS2 > Properties > Launch Options ใส่:
   ```
   +exec autoexec
   ```
4. เปิดเกมใหม่ หรือพิมพ์ในคอนโซล: `exec autoexec`

## คำเตือน

ไฟล์เริ่มด้วย `unbindall` ลบปุ่มที่ bind ไว้ทั้งหมด แล้ว bind ใหม่ตามไฟล์นี้
ไม่อยากให้ล้าง ลบบรรทัดนั้นทิ้ง

## ในไฟล์มีอะไร

| หมวด | ทำอะไร | แก้อะไร |
|---|---|---|
| MOUSE | เซนซิทิวิตี้ ซูม | `sensitivity` ใส่ค่าตัวเอง |
| MOVEMENT | WASD, ctrl ย่อ, shift เดินช้า, กระโดดด้วย space + เลื่อนล้อลง | ปุ่ม |
| GRENADE BINDS | ระเบิดบนปุ่มเมาส์/คีย์ (`slot6`-`slot10`) | เลข slot |
| BINDS | ซื้อของ, use, ทิ้งปืน, radio, voice, demo ฯลฯ | ปุ่ม |
| Crosshairs | ว่าง ใส่ crosshair ตัวเองตรงนี้ | ทั้งหมด |
| Radar | ขนาด หมุน อยู่กลาง | ค่า scale |
| VIEWMODEL | fov, ตำแหน่งปืน x/y/z, ปิด recoil | ตามชอบ |
| SETTINGS | gamma, rate, fps_max, HUD, ตั้งค่า client อื่นๆ | `fps_max`, `hud_scaling` |
| SOUND | ระดับเสียงแต่ละชนิด `volume` หลักตั้งต่ำมาก (0.022) | `volume` |
| COMMUNICATION | ตัวเลือก mute | flag mute |
| GRENADE CROSSHAIR | crosshair ตอนถือระเบิด เปิด/ปิด | เปิด/ปิด |
| TELEMETRY | โชว์ frametime / ping | ค่า show |
| BACKGROUND | แมพพื้นหลังเมนู | ชื่อแมพ |
| DEMO | ลูกศรข้าม 5 วิ, `p` หยุด | ปุ่ม |
| FUN | bind พิมพ์แชท (`k`, `h`) | ลบหรือเปลี่ยนข้อความ |

## เคล็ดลับ

- ปุ่มเป็นของฉัน เช็คว่าชนกับปุ่มของตัวเองไหม
- บรรทัดสุดท้าย `host_writeconfig` เซฟ config หลังโหลด
- `practice.cfg` สำหรับซ้อม พิมพ์ในคอนโซล `exec practice`

## เครดิต

ได้แรงบันดาลใจจาก config ของ EliGE

## License

GPL-3.0

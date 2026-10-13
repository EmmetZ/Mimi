<div align="center">
  <img src="../../src-tauri/icons/128x128@2x.png" width="96" alt="mimi">
  <h1>Mimi</h1>
  <p>คำบรรยายแปลสดจากเสียงคอมพิวเตอร์หรือไมโครโฟน</p>
  <p>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/github/v/release/yuxino/mimi?style=flat&amp;logo=github&amp;logoColor=white" alt="รุ่นล่าสุด"></a>
    <a href="https://github.com/yuxino/mimi/releases"><img src="https://img.shields.io/github/downloads/yuxino/mimi/total?style=flat&amp;labelColor=a85f82&amp;color=e889b5" alt="ยอดดาวน์โหลดทั้งหมด"></a>
    <a href="https://github.com/yuxino/mimi/actions/workflows/ci.yml?query=branch%3Amain"><img src="https://img.shields.io/github/actions/workflow/status/yuxino/mimi/ci.yml?style=flat&amp;logo=githubactions&amp;logoColor=white&amp;branch=main&amp;event=push&amp;label=CI" alt="สถานะ CI บน main"></a>
    <a href="../../LICENSE"><img src="https://img.shields.io/github/license/yuxino/mimi?style=flat&amp;logo=opensourceinitiative&amp;logoColor=white" alt="สัญญาอนุญาต MIT"></a>
  </p>
  <p>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/macOS-13%2B-555?style=flat&amp;logo=apple&amp;logoColor=white" alt="macOS 13+"></a>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/Windows-x64-0078D4?style=flat&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI%2BPHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0wIDBoMTF2MTFIMHptMTMgMGgxMXYxMUgxM3pNMCAxM2gxMXYxMUgwem0xMyAwaDExdjExSDEzeiIvPjwvc3ZnPg%3D%3D&amp;logoColor=white" alt="Windows x64"></a>
    <a href="https://github.com/yuxino/mimi/releases/latest"><img src="https://img.shields.io/badge/Linux-x86__64-FCC624?style=flat&amp;logo=linux&amp;logoColor=white" alt="Linux"></a>
    <a href="../../android/README.md"><img src="https://img.shields.io/badge/Android-app-3DDC84?style=flat&amp;logo=android&amp;logoColor=white" alt="Android"></a>
  </p>
  <p>
    <a href="../../README_EN.md">English</a> · <a href="../../README.md">简体中文</a> · <a href="zh-TW.md">繁體中文</a> · <a href="ja.md">日本語</a> · <a href="th.md"><strong>ภาษาไทย</strong></a> · <a href="ko.md">한국어</a> · <a href="fr.md">Français</a> · <a href="de.md">Deutsch</a>
  </p>
</div>

![ภาพตัวอย่างคำบรรยายสองภาษาของ Mimi พร้อมบทสนทนาสมมติ](../assets/readme-preview.png)

ภาพจำลองหน้าจอพร้อมบทสนทนาตัวอย่าง [ดูคำบรรยายและโหมดเต็มอารมณ์ (หน้าตาเวอร์ชันเก่า)](../demos/README.md)

## ฟังไป อ่านคำบรรยายไป

- **เข้าใจสิ่งที่กำลังเล่น**: แสดงคำพูดในภาพยนตร์ ไลฟ์ และบทเรียนเป็นคำบรรยายลอย เลือกสองภาษา เฉพาะคำแปล หรือเฉพาะต้นฉบับได้
- **เลือกเสียงที่ต้องการ**: ค่าเริ่มต้นคือเสียงคอมพิวเตอร์ เปิดไมโครโฟนหรือทั้งสองแหล่งเองได้ และเลือกแอปเฉพาะบน macOS / Windows 11 ได้
- **ปรับให้อ่านสบาย**: เปลี่ยนตำแหน่ง ขนาด และสี โหมดเต็มอารมณ์เหลือแค่ข้อความ และการคลิกทะลุช่วยให้ใช้แอปด้านล่างต่อได้
- **บันทึกเมื่อจำเป็น**: บนเดสก์ท็อป บันทึกคำบรรยายหรือเสียงที่เลือกแล้วส่งออก TXT / WAV ได้ การบันทึกทั้งสองอย่างปิดไว้โดยค่าเริ่มต้น

## เริ่มใช้งาน

1. **[ดาวน์โหลด Mimi](https://github.com/yuxino/mimi/releases/latest)** สำหรับ macOS 13+ (ชิป Apple / Intel), Windows x64 หรือ Linux x86_64 หากใช้โทรศัพท์ ดู[วิธีตั้งค่า Android (ภาษาอังกฤษ)](../../android/README.md#start)
2. **เพิ่มการตั้งค่าบริการ** ใน การตั้งค่า → โมเดลและบริการ (เวอร์ชันเก่าใช้ เสียงและการแปล) เลือกบริการและบันทึกข้อมูลรับรอง [คู่มือตั้งค่าบริการ (ภาษาอังกฤษ)](../provider-setup.md#choose) อธิบายตัวเลือกและวิธีรับคีย์
3. **เริ่มคำบรรยาย** เลือกแหล่งเสียง ภาษาที่พูด และภาษาแปล เล่นเนื้อหาแล้วเปิดคำบรรยายสดในหน้าคำบรรยาย พร้อมอนุญาตการเข้าถึงเสียงตามที่ระบบขอ

Mimi ใช้ฟรี แต่บริการคลาวด์อาจมีค่าใช้จ่าย บริการรู้จำเสียงบนคลาวด์จะได้รับเสียง ส่วนบริการแปลข้อความทางไกลจะได้รับข้อความที่รู้จำได้ การประมวลผลในเครื่องต้องใช้บริการ Apple ที่รองรับ ดูเงื่อนไขในคู่มือตั้งค่า

## ต้องการความช่วยเหลือ?

[คู่มือการใช้งาน](../usage.th.md) ครอบคลุมการติดตั้ง สิทธิ์ การแสดงคำบรรยาย และการบันทึก หากไม่มีคำบรรยายหรือเชื่อมต่อไม่ได้ ให้ดู[ข้อผิดพลาดในการรู้จำเสียง](../usage.th.md#errors) ก่อน หากยังไม่หาย [แจ้งปัญหา](https://github.com/yuxino/mimi/issues)ได้

## ผู้ร่วมพัฒนา

หากอยากช่วยพัฒนา เริ่มที่[คู่มือร่วมพัฒนา (อังกฤษ/จีน)](../../.github/CONTRIBUTING.md)

ขอบคุณทุกคนที่เขียนโค้ด รายงานปัญหา ทดลองใช้ Mimi หรือแบ่งปันให้ผู้อื่น (๑•̀ㅂ•́)و✧

ขอบคุณเป็นพิเศษแก่ [@yebuwudong](https://github.com/yebuwudong) สำหรับ [แอป Android](https://github.com/yuxino/mimi/pull/37) และ [@LLLin000](https://github.com/LLLin000) สำหรับ [แอนิเมชันคำบรรยาย](https://github.com/yuxino/mimi/pull/67) และ [การปรับปรุงเสียงบน Windows](https://github.com/yuxino/mimi/pull/89)

ขอบคุณ [@Chtholly000](https://github.com/Chtholly000) ที่ปรับปรุง [คำบรรยายต่อเนื่องของ Gemini และการเปลี่ยนการเชื่อมต่อตามกำหนด](https://github.com/yuxino/Mimi/pull/176)

ขอบคุณ [@EmmetZ](https://github.com/EmmetZ) ที่แก้ไข [ตัวควบคุมที่ไม่ตามหน้าต่างคำบรรยายบน Wayland](https://github.com/yuxino/Mimi/pull/242)

<p>
  <a href="https://github.com/yuxino"><img src="../assets/contributors/yuxino.svg" width="64" height="64" alt="@yuxino"></a>
  <a href="https://github.com/LLLin000"><img src="../assets/contributors/LLLin000.svg" width="64" height="64" alt="@LLLin000"></a>
  <a href="https://github.com/yebuwudong"><img src="../assets/contributors/yebuwudong.svg" width="64" height="64" alt="@yebuwudong"></a>
  <a href="https://github.com/Chtholly000"><img src="../assets/contributors/Chtholly000.svg" width="64" height="64" alt="@Chtholly000"></a>
  <a href="https://github.com/inhome"><img src="../assets/contributors/inhome.svg" width="64" height="64" alt="@inhome"></a>
  <a href="https://github.com/EmmetZ"><img src="../assets/contributors/EmmetZ.svg" width="64" height="64" alt="@EmmetZ"></a>
</p>

[ผู้ร่วมพัฒนาทั้งหมด](https://github.com/yuxino/mimi/graphs/contributors)

## ชุมชน

ขอบคุณผู้ใช้จาก [V2EX](https://www.v2ex.com/), [LINUX DO](https://linux.do/), [Appinn](https://meta.appinn.net/), [NodeLoc](https://www.nodeloc.com/), [Solo](https://solo.xin/), [Xinquji](https://xinquji.com/posts/859305) และ [Eleduck](https://eleduck.com/) ที่ทดลองใช้ Mimi แบ่งปันความคิดเห็น และช่วยบอกต่อ

[MIT](../../LICENSE) © 2026 yuxino

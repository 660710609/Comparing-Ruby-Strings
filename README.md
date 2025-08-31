# Comparing Ruby Strings

ใน Ruby เราจะมีการเปรียบเทียบ(Comparing) ข้อความ(String) ได้หลายวิธีมาก เพื่อการนำไปใช้ต่อ หรือแม้กระทั่งใช้ประโยชน์ในการ เรียงข้อมูล(Sort) ได้ด้วย ซึ่งในบทความนี้จะพูดถึงการ เปรียบเทียบข้อความแบบ Case-sensitive  &#x20;

## การใช้ ==

การใช้ == ในภาษา Ruby เป็นการใช้ตรวจสอบค่า (content) ของ ข้อความ 2 ข้อความ ว่าเท่ากันและเหมือนกันทุกประการหรือไม่

### ตัวอย่างการใช้ ==

> Ruby

```
str1 = "Hello"
str2 = "hello"
str3 = "Hello World!"

puts str1 == str2
```

{% hint style="info" %}
output\
false
{% endhint %}




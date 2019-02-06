# Design patterns

## มันคืออะไร ?
**Design patterns** เป็นแนวคิดในการแก้ปัญหาที่เราเจอบ่อยๆในการออกแบบซอฟต์แวร์ ซึ่งถ้าเรามี `ปัญหา` แล้วปัญหานั้นมีลักษณะตรงกับ `pattern` ไหนก็ตาม เราก็จะสามารถนำแนวคิดของ pattern นั้นๆไปแก้ปัญหาของเราได้เลย  

**Pattern** แต่ละตัวจะเป็นแค่ `แนวคิดในการแก้ไขปัญหา` เท่านั้น ซึ่งมันไม่ได้บอกชัดเจนว่าเราต้องมีทำอะไรบ้างเพื่อจะแก้ปัญหาที่เจอ ดังนั้นวิธีการแก้ปัญหาที่เจอจะขึ้นกับการตัดสินใจของ developer เอง

## 👍 ข้อดี
* เมื่อเกิดปัญหาในการออกแบบซอฟต์แวร์ สามารเอา pattern มาแก้ปัญหาได้เลย
* สามารถรับมือเมื่อเจอกับ business requirement ที่ซับซ้อนได้
* ลดการเกิด coupling, โค้ดยืดหยุ่นขึ้น, โค้ดนำกลับมาใช้ใหม่ได้

## 👎 ข้อเสีย
* Design pattern แต่ละตัวไม่ได้เข้าใจง่ายสำหรับ developer มือใหม่
* Developer ส่วนใหญ่จะนำ design pattern ไปใช้เลย โดยไม่ได้ชั่งน้ำหนักก่อนใช้ให้ดีก่อน ทำให้โค้ดมีความซับซ้อนเพิ่มขึ้นโดยไม่จำเป็น

> **คำเตือน**  
การนำ design pattern ไปใช้ไม่ใช่เรื่องเท่ เพราะมันมี cost (memory, processing overhead & complexity) ของมันค่อนข้างสูง ดังนั้นก่อนใช้ให้ **ชั่งน้ำหนัก** ข้อดี/ข้อเสีย ให้ดีก่อน ไม่งั้นโค้ดจะทำงานได้แต่ maintenance ยากขึ้นโดยใช่เหตุ

## กลุ่มของ patterns ต่างๆ
Pattern ทั้งหมดถูกแบ่งออกเป็น 3 กลุ่ม ตามวัตถุประสงค์ในการแก้ไขปัญหาของมันดังนี้

* **Creational patterns** วัตถุประสงค์ของกลุ่มนี้คือ สร้าง object โดยที่ทำให้โปรแกรมของเรามีความยืดหยุ่นมากขึ้น และ โค้ดสามารถนำกลับมาใช้ใหม่ได้  ซึ่งภายในกลุ่มนี้มี patterns อยู่คือ
  * [Factory method pattern](FactoryMethod.md)
  * [Abstract factory pattern](AbstractFactory.md)
  * [Builder pattern](Builder.md)
  * [Singleton pattern](Singleton.md)
  * [Prototype pattern](Prototype.md)

* **Structural patterns**  
วัตถุประสงค์ของกลุ่มนี้คือ จัดการโครงสร้างของโปรแกรม เช่น class และ object แต่ละตัวจะประกอบกันยังไง โดยที่โปรแกรมจะต้องคงความยืดหยุ่นได้ และ ยังมีประสิทธิภาพเหมือนเดิม ซึ่งภายในกลุ่มนี้มี patterns อยู่คือ
  * [Adapter pattern](Adapter.md)
  * [Bridge pattern](Bridge.md)
  * Composite pattern
  * [Decorator pattern](Decorator.md)
  * [Facade pattern](Facade.md)
  * Flyweight pattern
  * [Proxy pattern](Proxy.md)

* **Behavioral patterns**  
วัตถุประสงค์ของกลุ่มนี้คือ ช่วยในการทำงานร่วมกันระหว่าง object ต่างๆ ซึ่งภายในกลุ่มนี้มี patterns อยู่คือ
  * Chain of responsibility pattern
  * [Command pattern](Command.md)
  * Interpreter pattern
  * Iterator pattern
  * [Mediator pattern](Mediator.md)
  * Memento pattern
  * [Observer pattern](Observer.md)
  * State pattern
  * [Strategy pattern](Strategy.md)
  * [Template Method pattern](TemplateMethod.md)
  * Visitor pattern

# Credit
https://refactoring.guru  
You can buy his book by click the image below.  
[![img](https://refactoring.guru/images/patterns/book/web-cover-en.png)](https://refactoring.guru/design-patterns/book#buy-now)  

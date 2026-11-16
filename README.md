# CP2-Layer5

**تانلی بر پایه لایه 5 ام شبکه، یک تغییر هویت واقعی!**

A tunnel built on Layer 5 of the network — a real identity change!

---

## توضیحات (Persian)

در این تانل بر خلاف لایه ۴ شبکه که یک جعل اتفاق می‌افته، یک تغییر هویت واقعی و منطقی اتفاق می‌افته؛ ترافیک بر اساس UDP با هویت یک منبع وایت‌لیست (آی‌پی‌هایی که توانسته‌اند خود را در وایت‌لیست قرار دهند) و تغییر هویت رد می‌شوند.

## Description (English)

Unlike Layer 4, where a mere spoof takes place, this tunnel performs a genuine and logical identity change: UDP-based traffic is routed under the identity of a whitelisted source (IPs that have managed to get themselves whitelisted), with the identity change applied accordingly.

---

## پیشینه و خاستگاه پروژه

متعاقباً، مشخص شد که برخی از نهادهای ایرانی وابسته به دولت توانستند آدرس‌های IP خاص خود را در لیست سفید قرار دهند و اتصال بین‌المللی خود را با موفقیت بازیابی کنند. این مشاهدات منجر به این فرضیه شد که محدودیت در لایه ۵ اعمال می‌شود، به طور خاص فیلتر بر اساس srcIP و dstIP.

این فرضیه زمانی تایید شد که متوجه شدیم چند آدرس IP خارجی منتخب (مانند محدوده‌های خاص از Hetzner) هنوز هم می‌توانند اتصالات ورودی به ایران برقرار کنند. شواهد به وضوح نشان می‌دهند که بلاک‌اوت یک قطع فیزیکی نیست، بلکه یک خط‌مشی سخت‌گیرانه و مبتنی بر لیست سفید فایروال لایه ۵ است.

---

## Developer

Developed by **zte**

Project: `CP2_Layer5`

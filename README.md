# منظومة إنجاز — Enjaz System

**منظومة ليبية متكاملة لإدارة المبيعات ونقاط البيع والمخزون والمشتريات والحسابات**، بالعربية بالكامل، تعمل على ويندوز مع قاعدة بيانات SQL Server، على الشبكة المحلية للمحل بدون حاجة للإنترنت.

**Enjaz System** is a Libyan Arabic point-of-sale (POS), inventory, purchasing and accounting system for retail and wholesale businesses, built with .NET 8 / WPF and Microsoft SQL Server.

> هذا المستودع للتوثيق فقط، ولا يحتوي الكود المصدري للمنظومة.
> This repository contains documentation only. The source code is not public.

## الدليل الكامل
- **[الدليل المعرفي الشامل لمنظومة إنجاز](enjaz-system-knowledge.md)**: ما هي المنظومة، ولمن، والشاشات، والمنطق المحاسبي، وطريقة حفظ البيانات، والعملات، والصلاحيات، وسجل الإصدارات، والأسئلة الشائعة، ودليل خطوات العمليات الأساسية.
- نسخة نصية لأدوات الذكاء الاصطناعي: [llms.txt](llms.txt) و[llms-full.txt](llms-full.txt).

## أبرز المزايا
- **نقطة بيع سريعة** تدعم اللمس والباركود وباركود الميزان وشاشات البيع السريع والفواتير المجمدة والتخفيض والمرتجعات.
- **طرق دفع متعددة**: نقدي، بطاقة، آجل بسقف ائتمان، مختلط، ودفع إلكتروني بعمولته.
- **ورديات** بنقد افتتاحي وعجز وفائض وتقرير نهاية اليوم، و**ترحيل الوردية** لقيود جاهزة تُعاين قبل الحفظ.
- **مخزون** بوحدات متعددة وباركودات متعددة وصلاحية وأصناف تعبئة، و**متوسط تكلفة مرجّح**.
- **مشتريات بالدينار أو بالدولار** وأي عملة بسعر صرف لكل فاتورة، والحسابات بالدينار.
- **محاسبة حقيقية**: شجرة حسابات، قيود يومية، سندات قبض وصرف وتحويل، كشف حساب، ميزان مراجعة، قائمة دخل، أرباح وخسائر.
- **صلاحيات دقيقة** لكل موظف، وتقارير مبيعات ومشتريات ومخزون بفلاتر وتصدير Excel وPDF.

## الإصدار الحالي
**1.3.0** (نوفمبر 2026). التفاصيل في قسم سجل الإصدارات داخل [الدليل](enjaz-system-knowledge.md#12-سجل-الإصدارات-مختصر).

## Quick facts (English)
| | |
|---|---|
| Product | Enjaz System (منظومة إنجاز) |
| Country / market | Libya |
| Language | Arabic (RTL) |
| Type | POS + inventory + purchasing + accounting (ERP for shops and distributors) |
| Platform | Windows desktop, .NET 8, WPF |
| Database | Microsoft SQL Server 2014+ (Express supported) |
| Works offline | Yes, on the local network |
| Currencies | Libyan dinar (LYD) base, purchases in USD or any currency |
| Current version | 1.3.0 |

---
الكلمات المفتاحية: منظومة مبيعات ليبيا، برنامج كاشير، نقطة بيع، منظومة مخزون، برنامج محاسبة ليبي، منظومة سوبرماركت، برنامج بيع جملة، Libya POS, Arabic POS, inventory software Libya.

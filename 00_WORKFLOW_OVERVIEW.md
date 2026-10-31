# 00 — Workflow Overview

## ترتيب التنفيذ

اتبع المراحل بالترتيب. المرحلتان 07 و08 يمكن تنفيذهما بالتوازي بعد اعتماد 06 بشرط تحديد عقود التكامل. المرحلتان 09 و10 يمكن تنسيقهما بالتوازي جزئياً عندما تتوفر بيئة Staging ومحتوى معتمد. لا تتجاوز بوابة الجودة لكل مرحلة.

| # | المرحلة | المهارات المطلوبة (Skills) | يعتمد على | المخرجات (Deliverables) | معيار الانتقال |
|---:|---|---|---|---|---|
| 01 | Research & Discovery | Market Research, Competitor Analysis, Audience Research, Business Analysis, UX Research | إعدادات المشروع | Market Research Report, Competitor Matrix, Audience Personas, Business Requirements, Project Scope | فهم موثق للسوق والجمهور والمنافسين وأهداف المشروع. |
| 02 | SEO Strategy & Architecture | SEO Audit, Keyword Research, Search Intent Analysis, Topical Mapping, Site Architecture, Internal Linking Strategy | 01 | SEO Audit, Keyword Map, Topical Clusters, Sitemap, URL Map, Internal Linking Blueprint | كل صفحة لها هدف بحثي واضح ومكان محدد في هيكل الموقع. |
| 03 | Content Planning & Writing | Content Strategy, Content Briefs, SEO Copywriting, Content Writing, Semantic SEO, Localization, Editorial Review | 01–02 | Content Plan, Page Briefs, Complete Copy, Metadata, FAQs, Sources, Link Suggestions | المحتوى معتمد ودقيق ويلبي نية البحث وجاهز للتصميم والنشر. |
| 04 | UX Planning & Wireframing | UX Research, Information Architecture, User Journey Mapping, Wireframing, Content Layout, Conversion UX | 01–03 | User Flows, Sitemap Validation, Low-Fidelity Wireframes, Page Layout Specs | كل نوع صفحة له هيكل واضح وتجربة قابلة للاختبار. |
| 05 | UI Design | UI Design, Visual Design, Design Systems, Typography, Color Theory, Responsive Design, RTL/LTR, Figma | 01–04 | Design System, High-Fidelity Screens, Components, Desktop/Mobile Designs, Prototype | التصميم متسق ومكتمل ويستخدم محتوى حقيقياً وقابل للتنفيذ. |
| 06 | Technical Planning | Technical Architecture, CMS Planning, Database Design, Component Architecture, API Planning, Security | 01–05 | Technical Specification, Architecture Diagram, CMS/Data Model, API Specs, Implementation Plan | كل متطلبات النظام والبيانات والتكامل موثقة ومعتمدة. |
| 07 | Frontend Development | HTML, CSS, JavaScript, Selected Framework, Responsive Development, Accessibility, Performance | 04–06 | Implemented Frontend, Reusable Components, Responsive UI, Frontend Documentation | الواجهات تطابق التصميم وتعمل عبر الأجهزة والحالات الأساسية. |
| 08 | Backend & CMS Development | WordPress/PHP or Selected Stack, Database, API Integration, Authentication, CMS Development | 06 + اتفاق التكامل مع 07 | Working CMS, Data Models, APIs, Admin Workflows, Security Controls | إدارة المحتوى والبيانات والوظائف تعمل ويمكن اختبارها. |
| 09 | Technical SEO Implementation | Technical SEO, Schema Markup, XML Sitemap, Robots.txt, Canonical, Hreflang, Core Web Vitals | 02 + 06–08 | SEO Configuration, Schema, Sitemap, Robots, Canonical/Hreflang Rules, Validation Report | الإعدادات صحيحة وتم اختبار الزحف والفهرسة واللغات. |
| 10 | Content Integration | CMS Content Management, Content Formatting, Image Optimization, Internal Linking, Metadata | 03 + 07–09 | Populated Pages, Metadata, Internal Links, Optimized Media, Content QA Report | المحتوى المعتمد منشور أو جاهز على Staging دون أخطاء أو فقدان. |
| 11 | QA & Testing | Manual Testing, Cross-Browser, Mobile Testing, UX Testing, SEO Audit, Performance Testing, Accessibility | 01–10 | Test Cases, Bug Register, SEO/UX/Performance Reports, Retest Evidence | لا توجد عيوب حرجة مفتوحة وجميع نتائج الاختبار موثقة. |
| 12 | Launch & Deployment | Hosting, Domain, DNS, SSL, Git, CI/CD, Backups, Production Deployment | 06–11 | Live Website, Deployment Log, Backup, Rollback Plan, Smoke Test Report | الإطلاق تم بتصريح ونجحت اختبارات الموقع الحي وخطة التراجع جاهزة. |
| 13 | Monitoring & Optimization | Google Search Console, GA4, SEO Reporting, CRO, A/B Testing, Content Optimization | 01–12 + بيانات ما بعد الإطلاق | Tracking Setup, KPI Dashboard, Reports, Optimization Backlog, Content Refresh Plan | القياس يعمل والقرارات مبنية على بيانات فعلية وخطة تحسين واضحة. |

## ملاحظات تنظيمية

- **المدخلات السابقة:** تعني ملفات التسليم المعتمدة، وليس مجرد ملخص المحادثة.
- **المخرجات:** يجب حفظها كملفات أو إعدادات أو كود أو تقارير قابلة للمراجعة، حسب طبيعة المرحلة.
- **المراجعة:** المنفذ لا يعتمد عمله وحده؛ استخدم Reviewer أو مراجعة مستقلة للقرارات عالية الأثر.
- **التوازي:** لا تسمح بالتوازي إذا كان أحد المسارين ينتظر قراراً أو مدخلاً أساسياً من الآخر.
- **التغيير:** إذا تغيرت مخرجات مرحلة سابقة، حدّد المراحل التابعة التي تحتاج إلى تحديث.

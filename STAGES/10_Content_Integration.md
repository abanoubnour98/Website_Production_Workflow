# Stage 10 — Content Integration

**بالعربية:** دمج المحتوى داخل الموقع  
**رقم المرحلة:** 10 من 13

## 1. الهدف

تنفيذ مرحلة **Content Integration** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

CMS Content Management, Content Formatting, On-Page SEO, Image Optimization, Internal Linking, Metadata Implementation, Localization QA

## 3. يعتمد على (Previous Inputs)

Stage 03 approved copy and metadata; Stage 07–08 functional templates/CMS; Stage 09 SEO rules and URL/hreflang configuration.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Prepare a publishing checklist and map each approved content file to its target URL and CMS content type.
2. Enter content without changing approved meaning, claims or structure.
3. Format headings, paragraphs, lists, tables, quotes, captions, FAQs and CTAs correctly.
4. Upload optimized media and implement descriptive alt text where appropriate.
5. Add approved SEO title, meta description, canonical, author/date fields and other CMS metadata.
6. Implement approved contextual internal links, breadcrumbs and language equivalents.
7. Check Arabic/English typography, RTL/LTR layout, punctuation, numerals and formatting.
8. Review pages in staging and compare with content files and approved UI designs.

## 5. المخرجات المطلوبة (Deliverables)

- Content mapped to CMS URLs
- Populated staging pages
- Metadata and image assets
- Implemented internal links and breadcrumbs
- Language/content parity report
- Content integration checklist and issue log

## 6. معايير القبول (Acceptance Criteria)

- [ ] Every approved page is mapped to the correct URL and CMS type.
- [ ] No copy, heading, table, link or CTA is missing or unintentionally changed.
- [ ] Metadata and language versions are correct.
- [ ] Images are optimized and meaningful alt text is used where appropriate.
- [ ] Internal links resolve to the approved relevant destinations.
- [ ] Staging page appearance and RTL/LTR formatting have been checked.

## 7. Tips & Best Practices

- Use a page-by-page publishing tracker to avoid missing URLs.
- Do not paste formatted text blindly; inspect headings, tables, lists and links in the actual CMS.
- Avoid keyword-stuffed alt text; describe informative images accurately.
- Check all internal links after URL changes and redirects.
- Have a native editor review localized content before publication.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior Content Operations Specialist and SEO Publisher. Use only approved content from Stage 03, CMS and frontend functionality from Stages 07–08, and SEO rules from Stage 09. Map each page file to its target URL, language and CMS content type before publishing.

Enter the approved content without altering its factual meaning. Format headings, paragraphs, lists, tables, FAQs, captions, images and CTAs correctly. Implement unique SEO titles and meta descriptions, canonical settings, author/date fields where approved, image optimization, appropriate alt text, breadcrumbs, contextual internal links and language equivalents. Follow the approved URL and hreflang map.

Check each page in staging on desktop and mobile. Verify Arabic RTL and English LTR text flow, typography, punctuation, numerals, layout, links and content completeness. Compare the rendered page against the source content and approved UI design. Do not publish unapproved copy or claim verification without testing. Deliver a page-by-page integration tracker, populated staging URLs, issues and evidence of checks.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.

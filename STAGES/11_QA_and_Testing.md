# Stage 11 — QA & Testing

**بالعربية:** ضمان الجودة والاختبار  
**رقم المرحلة:** 11 من 13

## 1. الهدف

تنفيذ مرحلة **QA & Testing** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

Manual Testing, Functional Testing, Cross-Browser Testing, Mobile Testing, UX Testing, SEO Audit, Performance Testing, Accessibility, Security Testing

## 3. يعتمد على (Previous Inputs)

Stages 01–10: requirements, designs, content, code, CMS, technical SEO and staging pages.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Build test cases from original requirements and approved acceptance criteria.
2. Test all page templates, routes, navigation, buttons, forms, search, menus and integrations.
3. Test mobile, tablet and desktop behavior across agreed browsers.
4. Test Arabic RTL, English LTR, language switching and translated page relationships.
5. Check visual consistency against approved Figma designs.
6. Audit metadata, headings, canonicals, redirects, robots, sitemap, schema, hreflang and internal links.
7. Check accessibility, keyboard navigation, labels, contrast and focus states.
8. Measure performance and inspect console, server and application errors.
9. Log severity, reproduction steps, evidence, owner and fix status; retest fixes.

## 5. المخرجات المطلوبة (Deliverables)

- QA test plan and test cases
- Bug register with severity and evidence
- Visual/UX test report
- SEO and technical validation report
- Performance/accessibility/security findings as in scope
- Retest evidence and launch readiness recommendation

## 6. معايير القبول (Acceptance Criteria)

- [ ] All critical user journeys and priority page templates have been tested.
- [ ] No unresolved critical or high-severity launch blocker remains unless explicitly accepted.
- [ ] Failed and not-tested items are clearly marked; no false PASS status.
- [ ] Fixes have been retested and evidence recorded.
- [ ] Launch blockers and residual risks are approved by the responsible owner.

## 7. Tips & Best Practices

- Test real URLs and real devices/viewports, not just the homepage.
- Separate severity from priority and explain user/business impact.
- Test both normal and failure states for forms and integrations.
- Use automated tests where useful, but manually review visual quality and language rendering.
- Do a final production-like smoke test after deployment too.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior QA Engineer, UX Tester and SEO Auditor. Build your test plan from the approved project requirements, Stage 05 designs, Stage 06 technical specifications, Stages 07–08 implementation, Stage 09 SEO configuration and Stage 10 populated staging pages.

Test every priority page template, route, language, viewport and critical user journey. Check navigation, buttons, forms, search, menus, links, content completeness, CMS output, image loading, responsiveness, visual fidelity, keyboard use, labels, focus, contrast, RTL/LTR and language switching. Audit titles, descriptions, headings, canonicals, indexability, robots, sitemap, redirects, schema, hreflang, breadcrumbs and internal links. Review performance, console/server errors and security issues within the agreed scope.

For every defect, record a unique ID, severity, priority, URL/device/browser, reproduction steps, expected result, actual result, evidence, owner and status. Retest fixes and record evidence. Mark every check PASS, FAIL or NOT TESTED. Do not call the site launch-ready while critical blockers remain unless the authorized project owner explicitly accepts the documented risk. Deliver the test report and a clear launch recommendation.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.

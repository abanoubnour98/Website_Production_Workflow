# Stage 09 — Technical SEO Implementation

**بالعربية:** تنفيذ SEO التقني  
**رقم المرحلة:** 09 من 13

## 1. الهدف

تنفيذ مرحلة **Technical SEO Implementation** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

Technical SEO, Crawlability, Indexability, Schema Markup, XML Sitemap, Robots.txt, Canonical, Hreflang, Core Web Vitals, Redirects

## 3. يعتمد على (Previous Inputs)

Stage 02 SEO architecture; Stage 06 technical specs; Stages 07–08 working routes, CMS and staging environment; Stage 10 may run coordinated checks after content is loaded.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Translate the approved SEO architecture into technical configuration requirements.
2. Configure titles, descriptions, canonical URLs and index/noindex rules.
3. Generate and validate XML sitemap(s) and robots.txt.
4. Implement correct hreflang and language switch behavior for translated equivalents.
5. Implement structured data only where eligible and supported by visible page content.
6. Validate redirects, status codes, pagination, breadcrumbs and URL consistency.
7. Check crawlability, rendered content, duplicate URL variants and internal links.
8. Measure performance/Core Web Vitals and recommend targeted fixes.
9. Run a crawl and structured-data validation on staging; record evidence and limitations.

## 5. المخرجات المطلوبة (Deliverables)

- Technical SEO configuration
- Title/meta/canonical rules
- XML sitemap and robots configuration
- Hreflang map
- Structured data implementation and validation
- Redirect map and status-code report
- Staging crawl and technical QA report

## 6. معايير القبول (Acceptance Criteria)

- [ ] Canonical, indexability and hreflang rules match approved URL architecture.
- [ ] Sitemap contains intended canonical indexable URLs only.
- [ ] Robots.txt does not accidentally block important pages or assets.
- [ ] Schema matches visible content and passes relevant validation checks.
- [ ] Redirects/status codes and rendered content have been tested.
- [ ] Unresolved errors and performance limitations are explicitly documented.

## 7. Tips & Best Practices

- Do not block pages in robots.txt to try to remove them from the index; use the appropriate indexation control.
- Do not add schema that is not supported by visible page content.
- Hreflang needs reciprocal, correct language/region references and canonical consistency.
- Test staging noindex and production indexability carefully to avoid accidental deployment mistakes.
- A green tool score is not a substitute for correct crawl and user experience.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior Technical SEO Engineer. Use the approved Stage 02 URL and SEO architecture, Stage 06 technical specifications, and the working Stage 07–08 implementation. Work on the authorized staging environment unless explicitly instructed otherwise.

Translate the SEO requirements into actual implementation. Configure unique metadata, canonical URLs, index/noindex behavior, XML sitemap generation, robots.txt, breadcrumbs, redirects, status codes, pagination behavior where relevant, structured data, Open Graph metadata and hreflang for translated equivalents. Ensure schema accurately reflects visible page content and is eligible under current search-engine policies. Check URL consistency, crawlability, rendered content, duplicate variants, internal links, mobile behavior and Core Web Vitals.

Run appropriate crawls and validators. Record exact URLs tested, tool/source, date, result and limitations. Never invent a successful test or apply risky indexation, redirect or canonical changes without understanding the consequences. Provide an issue list with severity, evidence, fix recommendation and retest status. Deliver implementation details and a validated technical SEO report for content integration and QA.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.

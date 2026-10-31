# Stage 13 — Monitoring & Optimization

**بالعربية:** المراقبة والتحسين المستمر  
**رقم المرحلة:** 13 من 13

## 1. الهدف

تنفيذ مرحلة **Monitoring & Optimization** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

Google Search Console, GA4, SEO Reporting, CRO, A/B Testing, Analytics, Content Optimization, Performance Monitoring

## 3. يعتمد على (Previous Inputs)

Stages 01–12: business KPIs, SEO targets, live website, analytics events, Search Console and sufficient post-launch data.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Verify analytics and Search Console access, tracking implementation, consent behavior and key conversion events.
2. Define baseline metrics and reporting cadence aligned with Stage 01 business goals and Stage 02 SEO targets.
3. Monitor index coverage, impressions, clicks, CTR, organic landing pages, queries and technical errors.
4. Monitor conversions, engagement and user journeys using privacy-respecting analytics.
5. Review page performance, Core Web Vitals, broken links, crawl anomalies and content freshness.
6. Identify content gaps, pages losing performance, internal-link opportunities and UX friction.
7. Prioritize recommendations by impact, confidence, effort and risk.
8. Run controlled experiments only when volume and measurement are sufficient; document hypotheses and outcomes.
9. Create an optimization backlog and regular review cycle.

## 5. المخرجات المطلوبة (Deliverables)

- Analytics and Search Console validation
- KPI definitions and baseline
- SEO/performance dashboard or report
- Content refresh and internal-link backlog
- CRO hypotheses and experiment plan
- Prioritized growth roadmap and review cadence

## 6. معايير القبول (Acceptance Criteria)

- [ ] Tracking and key events are tested rather than merely installed.
- [ ] Reports distinguish actual data from estimates and explain data limitations.
- [ ] Recommendations tie to business goals and measurable evidence.
- [ ] Experiments have a hypothesis, success metric and decision rule.
- [ ] Optimization actions have owners, priorities and review dates.

## 7. Tips & Best Practices

- Do not overreact to very short or low-volume reporting windows.
- Segment by country, language, device and landing-page type when useful and privacy compliant.
- Use Search Console for search visibility and analytics for on-site behavior; understand their different measurement models.
- Prioritize fixes with meaningful user or business impact over vanity metrics.
- Treat rankings as one signal, not the only measure of success.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior SEO Growth Strategist, Analytics Specialist and CRO Specialist. Use the original business goals from Stage 01, SEO priorities from Stage 02, approved content and UX strategy, and actual post-launch data from Stage 12 onward. First verify that analytics, Search Console, consent settings and conversion events are working. Do not assume tracking is correct because a tag is present.

Define KPIs and a reporting cadence. Analyze available Search Console data, analytics events, organic landing pages, queries, impressions, clicks, CTR, conversions, engagement, device/language/country segments, indexing, technical errors and page performance. Identify content decay, query/page mismatches, internal-link opportunities, UX friction and technical regressions. Distinguish data-backed findings from hypotheses and note date ranges, attribution limitations and sample-size constraints.

Prioritize recommendations by expected impact, confidence, effort and risk. For experiments, define the hypothesis, target audience, primary metric, guardrails, minimum evidence and decision rule before running the test. Do not claim causality or guaranteed ranking gains without evidence. Deliver a KPI report, issue/opportunity backlog, content refresh plan and prioritized optimization roadmap.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.

# Stage 12 — Launch & Deployment

**بالعربية:** الإطلاق والنشر  
**رقم المرحلة:** 12 من 13

## 1. الهدف

تنفيذ مرحلة **Launch & Deployment** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

Hosting, Domain, DNS, SSL, Git, CI/CD, Database Migration, Backups, Security, Production Deployment, Monitoring

## 3. يعتمد على (Previous Inputs)

Stage 06 deployment architecture; Stages 07–10 release candidate; Stage 11 approved QA report and launch decision.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Confirm written launch approval, release version and remaining accepted risks.
2. Verify production hosting, DNS records, SSL, environment variables, file permissions and service dependencies.
3. Create and verify backups of code, database, media and configuration as appropriate.
4. Prepare deployment and migration steps with rollback instructions.
5. Deploy through the approved Git/CI/CD or hosting workflow.
6. Run migrations and cache/CDN configuration safely.
7. Test production HTTPS, redirects, core pages, forms, CMS, languages, analytics, sitemap and robots directives.
8. Verify Search Console/analytics access and monitoring alerts where configured.
9. Document deployment version, time, actions, test outcomes and any incidents.

## 5. المخرجات المطلوبة (Deliverables)

- Production release
- Deployment log and release version
- Verified backup
- Rollback plan
- DNS/SSL verification
- Post-deployment smoke test report
- Monitoring and ownership notes

## 6. معايير القبول (Acceptance Criteria)

- [ ] Authorized approval and a verified backup exist before release.
- [ ] Production deploy completed through the approved method.
- [ ] Critical production pages and user journeys pass smoke tests.
- [ ] HTTPS, DNS, redirects, analytics and search-engine directives are correct.
- [ ] Rollback procedure and post-launch ownership are documented.

## 7. Tips & Best Practices

- Never make destructive production changes without authorization and a tested backup.
- Keep secrets out of Git and logs.
- Use a staging-to-production checklist and record the exact release version.
- Check that staging noindex settings are not accidentally carried into production.
- Monitor immediately after launch and keep the previous release available for rollback where feasible.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior DevOps Engineer and Production Deployment Specialist. Review the approved technical deployment plan from Stage 06, release candidate from Stages 07–10 and signed-off QA report from Stage 11. Confirm authorization, release version, outstanding accepted risks and rollback owner before taking production action.

Verify hosting, DNS, SSL, environment variables, permissions, database, storage, dependencies and monitoring. Create and verify appropriate backups. Prepare the deployment and migration steps, including rollback. Deploy only through the approved Git/CI/CD or hosting workflow. Do not expose secrets or overwrite production data without explicit approval.

After deployment, run production smoke tests for HTTPS, redirects, important pages, forms, navigation, CMS, languages, metadata, sitemap, robots, analytics and critical integrations. Confirm staging-only noindex or access controls are not active on production. Record the release ID, deployment time, actions, test evidence, incidents and rollback instructions. If authorization or backup verification is missing, stop before the consequential action and report the blocker.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.

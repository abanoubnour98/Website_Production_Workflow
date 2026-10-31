# Stage 06 — Technical Planning

**بالعربية:** التخطيط الفني والمعماري  
**رقم المرحلة:** 06 من 13

## 1. الهدف

تنفيذ مرحلة **Technical Planning** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

Technical Architecture, CMS Planning, Database Design, Component Architecture, API Planning, Security, Performance, DevOps Planning

## 3. يعتمد على (Previous Inputs)

Stages 01–05: business requirements, sitemap, content models, wireframes, approved UI designs, technology constraints and hosting information.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Translate business, SEO, content and UI requirements into system requirements.
2. Evaluate the current stack or viable alternatives against cost, hosting, maintainability, scalability, performance and skills.
3. Define frontend/backend/CMS responsibilities and integration boundaries.
4. Design content models, post types, taxonomies, fields, relationships and database requirements.
5. Specify APIs, third-party services, authentication, roles and permissions.
6. Plan reusable UI components, routing, multilingual support and SEO implementation points.
7. Define security, privacy, backups, environments, logging, deployment and rollback requirements.
8. Break implementation into milestones, dependencies and testable acceptance criteria.

## 5. المخرجات المطلوبة (Deliverables)

- Technical architecture document and diagram
- Technology decision record with trade-offs
- CMS/content model specification
- Database schema or data model
- API and integration specification
- Security and environment requirements
- Development backlog and implementation plan

## 6. معايير القبول (Acceptance Criteria)

- [ ] Architecture satisfies approved scope, CMS, hosting and budget constraints.
- [ ] Content model supports planned page types and languages.
- [ ] Frontend/backend integration contracts are clear.
- [ ] Security, backup, deployment and rollback requirements are documented.
- [ ] Major technical decisions have rationale and no critical unknown is hidden.

## 7. Tips & Best Practices

- Choose the simplest architecture that meets real requirements.
- Do not add microservices, queues or extra databases without a demonstrated need.
- Confirm shared-hosting or platform limitations before selecting a framework.
- Define API contracts and data models before separate frontend/backend work begins.
- Keep secrets in environment variables or a secrets manager, never in source code.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior Software Architect and Technical Product Manager. Review the approved business scope, SEO architecture, content models, wireframes, high-fidelity designs, CMS preferences, existing code and hosting constraints. Convert them into a feasible implementation architecture.

Evaluate the current technology stack and alternatives against requirements, hosting compatibility, cost, maintainability, performance, security and team capability. Define system boundaries, frontend/backend/CMS responsibilities, routing, component architecture, content types, taxonomies, fields, relationships, database requirements, APIs, integrations, roles and permissions. Specify multilingual and RTL/LTR handling, SEO implementation points, analytics, caching, media handling and accessibility requirements.

Document environments, configuration, security, backups, migrations, logging, CI/CD and rollback. Define API contracts and frontend/backend integration points so implementation can proceed without guessing. Break work into milestones and acceptance criteria. Avoid unnecessary complexity and justify each major technology decision. Deliver an architecture document, diagrams, schemas, specifications and an implementation backlog. Do not begin coding in this stage.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.

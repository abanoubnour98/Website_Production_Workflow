# Stage 08 — Backend & CMS Development

**بالعربية:** تطوير الخلفية ونظام إدارة المحتوى  
**رقم المرحلة:** 08 من 13

## 1. الهدف

تنفيذ مرحلة **Backend & CMS Development** ضمن منهجية بناء الموقع، وتسليم مخرجات قابلة للمراجعة والاستخدام في المرحلة التالية.

## 2. المهارات المطلوبة (Skills)

WordPress/PHP or Selected Backend, Database, API Integration, Authentication, CMS Development, Security, Data Migration

## 3. يعتمد على (Previous Inputs)

Stage 06 technical architecture and data model; coordinate API contracts and component needs with Stage 07. Existing database and content export if available.

> قبل التشغيل، أرفق الملفات الفعلية للمراحل السابقة. لا تعتمد على افتراض أن الـAgent يتذكر محادثة أو يستطيع فتح ملفات غير مرفقة.

## 4. المهام المطلوبة

1. Inspect the current backend/CMS, repository, database and hosting constraints.
2. Implement approved content types, taxonomies, fields, relationships and editorial workflows.
3. Configure roles, permissions, authentication and admin interfaces.
4. Implement APIs and integrations according to documented contracts.
5. Implement validation, sanitization, error handling, logging and security controls.
6. Support multilingual content relationships and publishing states where required.
7. Plan and test data migration, backups and rollback for existing sites.
8. Provide sample data and stable staging endpoints for frontend integration.

## 5. المخرجات المطلوبة (Deliverables)

- Working CMS/backend
- Database migrations and data model implementation
- Content types, taxonomies and admin workflows
- API endpoints and integration documentation
- Roles and security configuration
- Migration/backup notes and backend tests

## 6. معايير القبول (Acceptance Criteria)

- [ ] CMS editors can create, update, preview and manage approved content types.
- [ ] Data relationships and multilingual behavior work as specified.
- [ ] API responses match documented contracts and are tested.
- [ ] Permissions, input validation and security controls are implemented.
- [ ] Migrations and backup/restore approach are documented and tested where feasible.

## 7. Tips & Best Practices

- Keep editorial tasks simple; editors should not need code changes for routine publishing.
- Use existing platform capabilities before writing custom functionality.
- Validate and sanitize all external/user input.
- Avoid destructive migrations without verified backups and explicit approval.
- Document API fields, response formats, error codes and authentication requirements.

## 8. READY-TO-USE PROMPT

انسخ الـPrompt التالي، وألحق به `00_MASTER_INSTRUCTIONS.md` و`00_PROJECT_CONFIGURATION.md` ومخرجات المراحل السابقة المطلوبة أعلاه.

```text
Act as a Senior Backend Engineer and CMS Developer. Inspect the existing codebase, CMS, database, hosting constraints and Stage 06 technical architecture before changing anything. Coordinate with the frontend implementation and use the agreed API contracts.

Implement the required content models, post types, taxonomies, custom fields, relationships, editorial workflows, user roles, permissions, authentication and admin experience. Build API endpoints and integrations according to the documented specifications. Support multilingual content relationships and publishing states where required. Implement secure validation, sanitization, authorization, error handling, logging and appropriate rate/security controls.

Plan migrations from existing content and data carefully. Create backups before any data-changing operation and document rollback. Provide stable staging endpoints and sample data for frontend integration. Test content creation, updates, preview, permissions, API behavior and data integrity. Do not modify production data or perform destructive actions without explicit authorization. Deliver implementation, tests, API documentation, CMS editing instructions and known issues.

PHASE OUTPUT REQUIREMENTS
Create every deliverable listed in the stage file. Use clear filenames and include the project name, stage number and version/date where appropriate. If file creation is unavailable, provide complete structured content that can be saved as files.

QUALITY GATE
Evaluate every acceptance criterion in the stage file. Mark PASS, FAIL or NOT TESTED. Do not claim completion for unverified work. Fix what you can and document the remaining blockers.

HANDOFF
Prepare a handoff for the next stage. List exact deliverable filenames, key decisions, assumptions, unresolved issues, dependencies and any approvals needed. Do not execute the next stage.
```

## 9. المرحلة التالية

راجع `00_WORKFLOW_OVERVIEW.md` لمعرفة المرحلة التالية والمدخلات التي يجب تسليمها لها.

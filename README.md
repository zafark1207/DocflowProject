Directum RX ga o‘xshash Web Platforma uchun Texnik Topshiriq (TZ)
1. Loyiha nomi

Enterprise Document Management System (EDMS)
Directum RX ga o‘xshash korporativ hujjat aylanishi va biznes jarayonlarini avtomatlashtirish platformasi.

2. Loyiha maqsadi

Tashkilot ichidagi:

hujjatlar aylanishi,
topshiriqlar nazorati,
kelishuv jarayonlari,
elektron imzo,
CRM elementlari,
HR va ichki workflow’larni
raqamlashtirish va avtomatlashtirish.

Platforma web asosida ishlaydi va ko‘p foydalanuvchili bo‘ladi.

3. Platforma turi
Web platforma (SaaS + On-premise)
Multi-user
Role-based access
REST API asosida
Mikroservis arxitekturasi (yoki modular monolith)
4. Texnologiyalar
Backend
Python — Django + Django REST Framework
yoki
Node.js — NestJS
Frontend
React.js (Next.js tavsiya etiladi)
Database
PostgreSQL
Cache
Redis
Queue
RabbitMQ yoki Kafka
File Storage
MinIO / AWS S3
Authentication
JWT + Refresh token
OAuth2
LDAP/Active Directory integratsiyasi
DevOps
Docker
Kubernetes
GitLab CI/CD
5. Asosiy modullar
5.1. Foydalanuvchilar moduli
Funksiyalar
Ro‘yxatdan o‘tish
Login
2FA
Rollar boshqaruvi
Permission system
Tashkiliy struktura
Rollar
Super Admin
Admin
Director
Department Head
Employee
Auditor
5.2. Hujjatlar moduli
Funksiyalar
Hujjat yaratish
Draft holatda saqlash
Versiyalash
File upload
PDF preview
OCR
Metadata
QR code
Barcode
Hujjat turlari
Buyruq
Shartnoma
Ariza
Xat
Dalolatnoma
Ichki memo
Statuslar
Draft
Review
Approved
Rejected
Archived
5.3. Workflow Engine
Funksiyalar
BPMN workflow
Dynamic approval chain
Parallel approval
Sequential approval
Deadline control
SLA monitoring
Workflow misoli
Employee hujjat yaratadi
Department Head tasdiqlaydi
Legal review
Director approval
Archive
5.4. Task Management
Funksiyalar
Task yaratish
Delegation
Priority
Due date
Reminder
Progress tracking
Kanban view
5.5. Elektron Imzo (E-IMZO)
Integratsiyalar
E-IMZO
PKCS#7
OneID
Funksiyalar
Elektron imzolash
Signature verification
Timestamp
5.6. Notification System
Kanallar
Email
SMS
Telegram bot
Push notification
In-app notification
5.7. Search System
Funksiyalar
Full-text search
ElasticSearch integratsiyasi
Filterlar
Advanced search
5.8. Reporting & Analytics
Dashboard
KPI
Pending tasks
Approval statistics
Employee productivity
Export
PDF
Excel
5.9. Audit Log
Funksiyalar
Harakatlar logi
IP address
Device tracking
History
5.10. CRM moduli (optional)
Funksiyalar
Client management
Lead management
Contract lifecycle
6. Non-functional talablar
Performance
10,000+ concurrent users
API response < 300ms
Security
OWASP Top 10 protection
CSRF/XSS protection
AES encryption
HTTPS only
Scalability
Horizontal scaling
Backup
Daily backup
Disaster recovery
7. UI/UX talablar
Dizayn
Modern enterprise UI
Responsive
Dark mode
Asosiy sahifalar
Dashboard
Inbox
Documents
Tasks
Reports
Settings
8. API Talablari
REST API
Endpoint misollar
POST   /api/auth/login
GET    /api/documents
POST   /api/documents
PUT    /api/documents/{id}
DELETE /api/documents/{id}
9. Database struktura
Asosiy jadvallar
users
id
fullname
email
password_hash
role_id
department_id
documents
id
title
type
status
creator_id
created_at
workflows
id
document_id
step
approver_id
status
tasks
id
title
assigned_to
deadline
status
10. Integratsiyalar
Integratsiyalar ro‘yxati
1C
SAP
Oracle
Active Directory
Telegram Bot
Email SMTP
E-IMZO
OneID
11. Deployment
Muhitlar
Development
Staging
Production
Server
Ubuntu 22+
Nginx
Gunicorn
12. Admin panel
Funksiyalar
User management
Role management
Workflow constructor
Logs
System settings
13. Mobile Support
Variantlar
Responsive web
yoki
Flutter mobile app
14. AI funksiyalar (optional)
AI imkoniyatlari
Smart OCR
Document classification
Auto summary
AI assistant
Smart search
15. Loyihaning bosqichlari
Bosqich	Muddat
Analitika	2 hafta
UI/UX	2 hafta
Backend	8 hafta
Frontend	8 hafta
Integratsiya	3 hafta
Test	2 hafta
Deploy	1 hafta
16. Minimal MVP

MVP uchun:

Auth
Roles
Document CRUD
Workflow
Tasks
Notifications
Admin panel
17. Tavsiya etilgan arxitektura
Frontend

React + TypeScript

Backend

Django + DRF

Queue

Celery + Redis

Search

ElasticSearch

Storage

MinIO

18. Kelajakdagi kengaytirish
Multi-company
Multi-language
AI Copilot
BPMN Designer
Low-code constructor
Video approval
Voice commands
19. Taxminiy loyiha hajmi
Team
1 Project Manager
1 Business Analyst
2 Backend
2 Frontend
1 DevOps
1 QA
1 UI/UX
Taxminiy muddat

4–6 oy

20. Yakuniy natija

Tizim:

Directum RX,
DocsVision,
ELMA365,
Bitrix24,
Microsoft SharePoint
kabi enterprise darajadagi platformaga yaqin funksionallikni taqdim etadi.

Shuningdek:

O‘zbekiston E-IMZO tizimlari,
korporativ workflow,
elektron hujjat aylanishi
uchun moslashtirilgan bo‘ladi.
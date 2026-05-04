Tech Component Reference Library

## 1. Project Summary

This is a new project direction, separate from the old portfolio topic.

The website will be a personal/internal web library for collecting reusable UI design components with working code examples. The goal is to use it as a reference when designing or coding other projects.

Reference concept: W3Schools How To, which presents HTML/CSS/JavaScript code snippets grouped by UI/function categories such as modals, progress bars, loaders, cards, alerts, sticky headers, dark mode toggles, and similar how-to patterns.

## 2. Product Goal

Create a management-style component library website where each function/component is easy to find, preview, inspect, and reuse.

Primary goal:

- Store UI component examples with preview and separated code blocks
- Help quickly reuse design patterns and source code in future projects
- Organize components by clear categories
- Make each component understandable before copying code

Secondary goal:

- Build a sci-fi / tech themed design system
- Keep the interface clean, structured, and professional
- Support future growth into many component categories

## 3. Target Users

Primary user:

- Developer or designer who wants quick reference examples for HTML, CSS, and JavaScript components

Secondary users:

- Stakeholder reviewing component structure
- Future project team member who needs reusable UI/function references

View And Copy Component
<img width="5467" height="4005" alt="image" src="https://github.com/user-attachments/assets/00804f9b-ef67-4130-bcbb-0e7ed0910668" />

Login And Permission
<img width="6092" height="4005" alt="image" src="https://github.com/user-attachments/assets/134cfa6b-6d5d-4fb8-9795-c5445226c9c8" />

Full Website Design Support
<img width="7637" height="3255" alt="image" src="https://github.com/user-attachments/assets/aa19f73a-adbb-48a2-bf4d-3eb90dd46f2f" />

ER Diagram - Database Option
<img width="8192" height="5406" alt="image" src="https://github.com/user-attachments/assets/a03ba35f-ee5e-4106-a4a2-86ea55666724" />

Database Notes

- `COMPONENT` คือ master record ของ component
- `COMPONENT_CODE` แยก HTML, CSS, JavaScript, Notes หรือ code type อื่นในอนาคต
- `SNIPPET` ใช้สำหรับ compact snippet view และ popular snippets
- `AI_IMPORT_JOB` เก็บงานที่มาจาก AI agent เช่น URL หรือ clip
- `AI_COMPONENT_CANDIDATE` เก็บผลที่ AI extract มาให้ user review ก่อน save จริง
- `WEBSITE_DESIGN`, `WEBSITE_PAGE`, `WEBSITE_SECTION` รองรับ future feature: full website design
- `ROLE`, `PERMISSION`, `USER_ROLE`, `ROLE_PERMISSION` รองรับ Admin, Guest, Dev, UX/UI Design
- `AUDIT_LOG` ใช้เก็บประวัติ action สำคัญ เช่น add, edit, delete, approve AI candidate

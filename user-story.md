# User Stories

## Overview
This document contains the user stories for the agile-final-project. Each story follows the format:
"As a [user role], I want [goal] so that [reason]."

---

## User Story 1 — Core functionality
- ID: US-001  
- As a: Guest user  
- I want: to view the project landing page and key features without signing in  
- So that: I can understand what the project does and decide to use it  
- Acceptance Criteria:
  - Given I visit the project page, when the page loads then I can see the project title and a brief description.
  - When I click a "Demo" or "Get Started" link then I am taken to the demo or sign-up flow (if implemented).
- Priority: High  
- Estimate: 2 story points

## User Story 2 — Authentication
- ID: US-002  
- As a: Registered user  
- I want: to sign in and sign out of my account  
- So that: my private data and preferences are available only to me  
- Acceptance Criteria:
  - Given valid credentials, when I sign in then I am redirected to my dashboard.
  - Given I click "Sign out", when sign out completes then my session is cleared.
- Priority: High  
- Estimate: 3 story points

## User Story 3 — Create and manage items
- ID: US-003  
- As a: Authenticated user  
- I want: to create, update, and delete items (e.g., tasks, notes)  
- So that: I can manage my workload or content within the app  
- Acceptance Criteria:
  - Given I am logged in, when I create an item then it appears in my list.
  - Given an item exists, when I edit or delete it then changes are persisted.
- Priority: Medium  
- Estimate: 5 story points

## Notes
- Add further acceptance tests as features are refined.
- Link these stories to issues or tasks in GitHub for tracking (e.g., issue numbers).
-Update user-story.md — add user stories and acceptance criteria

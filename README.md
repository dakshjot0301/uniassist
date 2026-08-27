# uniassist
# Campus Connect — Smart Student Support Hub

> A unified digital platform designed to make campus navigation, student assistance, issue reporting, and support tracking simpler and more accessible.

## 🚀 Overview

Campus Connect is a student-focused web platform that brings multiple campus support functions into one interface.

Instead of requiring students to search for the right department, location, or source of information separately, Campus Connect provides a centralized hub where students can:

- 🗺️ Navigate campus locations
- 🤖 Ask questions using Campus Genie
- 🚨 Access emergency/security assistance
- 📝 Report campus issues
- 🔀 Automatically route issues to relevant departments
- 📷 Attach photographs to issue reports
- 🆔 Generate a unique issue ID
- 📊 Track submitted issues

The current implementation is a **front-end prototype** built using HTML, CSS, and JavaScript.

---

## 🎯 Problem Statement

Students frequently face problems on campus but may not know:

- Which department is responsible for an issue
- Where a particular campus facility is located
- How to report a problem
- How to follow up on a submitted complaint
- Where to find quick answers to common campus questions

Traditional support systems can create unnecessary communication gaps and delays.

### Our Approach

Campus Connect provides a single student-facing platform that connects common support requirements through one interface.

The system focuses on reducing friction between:

**Student → Problem → Correct Department → Resolution**

---

## 💡 Key Features

### 1. Campus Navigation

Students can access campus navigation information through the platform, helping them locate important campus facilities and areas.

### 2. Campus Genie

Campus Genie is an integrated student support assistant.

It can respond to common queries using predefined keyword-based knowledge rules covering areas such as:

- Campus map
- Issue reporting
- Issue tracking
- Wi-Fi/internet
- Hostel-related problems
- Security
- Academic support
- Food/cafeteria
- Other student support topics

The current prototype uses a lightweight rule-based approach.

---

### 3. Smart Issue Reporting

Students can submit an issue using:

- Issue title
- Category
- Location
- Description
- Optional photographs

The system validates required information before accepting a report.

---

### 4. Keyword-Based Department Routing

One of the main features of Campus Connect is automated issue routing.

Instead of relying only on a manually selected department, the system examines the issue information and searches for relevant keywords.

For example:

```text
"Issue with Wi-Fi in hostel room"

# ExpenseTracker Demo Guide

This guide demonstrates how to modernize a legacy desktop application using GitHub Copilot and AI-assisted development.

## 🎯 Demo Overview

**Scenario**: Modernizing a legacy VB.NET Windows Forms expense tracking desktop application to a modern ASP.NET Core web application.

**Goal**: Transform the desktop application into a modern, multi-user web application with enhanced features and responsive design.

## 🤖 1. New App Scaffolding Process

### Improved Scaffolding Prompt


```
Scaffold a new base ASP.NET Core 8.0 MVC  expense tracking web application with the following specifications:
Important: 
The scaffold should create the complete structure and skeleton but SHOULD NOT include any business logic implementation. All methods should be empty or contain placeholder comments. 
Create only index.html and DO NOT implement any other views.
Make sure all the packages are compatable with NET 8.0
Make sure the application runs without errors on first startup.


```

**Supporting Document**: `docs/ExpenseTracker_Modernization_Proposal.md` - Contains the modernization requirements and specifications.

## 🤖 2. Troubleshooting an Issue

Issue : Application crashes when adding an expense with decimal amount enter 0.05 in the expense amount and crash.

```
Help me troubleshoot the following issue in this application:

```
Note : Please attached the bug screenshot and logs showing the exception stack trace

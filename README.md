# Birthday-Invitees - Frontend Interview Challenge

A comprehensive frontend engineering interview combining algorithmic optimization with practical React implementation.

## 🎯 Overview

This interview tests candidates on:
1. **Algorithm Analysis & Optimization** - Identifying performance issues and optimizing nested loops
2. **React Development** - Building interactive UI with state management, async operations, and UX considerations


## 📁 Structure

```
Birthday-Invitees/
├── README.md                      ← Project overview
├── INTERVIEW_INSTRUCTIONS.md      ← Give to candidate (Part B)
├── INTERVIEWER_GUIDE.md          ← Complete interview guide
├── EVALUATION_RUBRIC.md          ← Scoring rubric
└── birthday-app/
    ├── SOLUTION.jsx              ← Reference solution
    └── src/
        ├── birthdayInvitees.js   ← Part A: Code to review/optimize
        ├── components/
        │   └── BirthdayInvitees.jsx  ← Part B: Starter component
        ├── utils/
        │   └── birthdayInvitees.js   ← Utility function
        ├── api/
        │   └── invitationsApi.js     ← Mock API
        ├── call_history.json         ← 36 call records
        └── phone_contacts.json       ← 30 contacts
```

## 🚀 Quick Start

### For Interviewers

1. **Start the React app:**
   ```bash
   cd birthday-app
   npm install
   npm run dev
   ```
   The app will run at `http://localhost:5173/`

### For Candidates

If you're a candidate, you should receive:
- Access to this codebase
- `INTERVIEW_INSTRUCTIONS.md` (for Part B)
- Link to running React app

## 📋 Interview Parts

### Part A: Algorithm Optimization (25-30 minutes)

Review and optimize the `print_birthday_invitees` function that finds people who should be invited to a birthday party based on call history.

**Questions:**
1. What does this code do?
2. What do you think about this code?
3. What is the runtime/memory complexity (Big O)?
4. Rewrite it to be more optimized
5. What's the new complexity?

### Part B: React Implementation (15 minutes)

Build an interactive UI to display and send birthday invitations.

**Requirements:**
- Display invitees with checkboxes
- Track selected invitees
- Send invitations via mock API
- Handle loading and error states


**For Candidates:**
- Ask clarifying questions
- Explain your thinking out loud
- Start with functionality, then improve
- Test your code as you go

## 🛠️ Technical Details

**Mock Data:**
- 30 phone contacts
- 36 call history records
- 14 contacts called within last 3 months
- Call history is sorted descending by time

**Technologies:**
- React 19
- Vite
- Node.js 20+

## 📝 License

This is an interview assessment tool. Use freely for your hiring process.

---

**Questions?** See `INTERVIEWER_GUIDE.md` for detailed instructions.

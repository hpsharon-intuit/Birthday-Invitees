# Birthday-Invitees - Frontend Interview Challenge

A comprehensive frontend engineering interview combining algorithmic optimization with practical React implementation.

## 🎯 Overview

This interview tests candidates on:
1. **Algorithm Analysis & Optimization** - Identifying performance issues and optimizing nested loops
2. **React Development** - Building interactive UI with state management, async operations, and UX considerations

**Duration:** 45-60 minutes  
**Target:** Frontend Engineers with 2-3 years experience

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

2. **Review before interview:**
   - Read `INTERVIEWER_GUIDE.md` for complete instructions
   - Check `SOLUTION.jsx` for reference implementation
   - Print or open `EVALUATION_RUBRIC.md` for scoring

3. **During interview:**
   - **Part A (25-30 min):** Algorithm review using `src/birthdayInvitees.js`
   - **Part B (15 min):** React implementation in `src/components/BirthdayInvitees.jsx`

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

**Key Learning:** Can the candidate identify and fix O(n²×m) → O(n+m) optimization?

### Part B: React Implementation (15 minutes)

Build an interactive UI to display and send birthday invitations.

**Requirements:**
- Display invitees with checkboxes
- Track selected invitees
- Send invitations via mock API
- Handle loading and error states

**Key Learning:** State management, async operations, UX patterns

## 🎓 What We're Testing

### Technical Skills
- Algorithm optimization
- Big O analysis
- React hooks (useState)
- Async/await handling
- State management
- Component structure

### Soft Skills
- Communication & explanation
- Problem-solving approach
- Time management
- Debugging skills
- Asking clarifying questions

## 📊 Evaluation

Use `EVALUATION_RUBRIC.md` for structured scoring:
- Part A (Algorithm): 40 points
- Part B (React): 60 points
- Bonus: 10 points
- **Total: 110 points** (scaled to 100)

**Scoring Guide:**
- 90-100: Strong hire
- 80-89: Hire
- 70-79: Maybe
- 60-69: Weak
- <60: No hire

## 💡 Tips for Success

**For Interviewers:**
- Review the `INTERVIEWER_GUIDE.md` thoroughly
- Let candidates think before giving hints
- Focus on thought process over perfect syntax
- Take detailed notes on the rubric

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
## Introduction

Welcome to the **Scrum Sprint Simulation**! This interactive game lets you step into the role of a Scrum Master, managing a virtual software development team through three sprints. Your goal is to deliver maximum value (measured in *story points*) while maintaining high quality and team morale, all within a **$50,000 budget**. You’ll hire a team, select tasks, assign work, respond to challenges, and reflect on your performance to improve.

This manual will guide you through each phase of the game, explain key mechanics, and offer tips for success. Let’s get started!

## Getting Started

- **Open the Game**: Load the HTML file in a modern web browser (e.g., Chrome, Firefox).
- **Dark Mode**: The game automatically adjusts to your system’s dark mode preference.
- **Objective**: Complete as many story points as possible across three sprints while balancing quality and team morale.

## Game Phases

### 1. Introduction (Intro)

- **What You See**: A welcome screen with game objectives and instructions.
- **What to Do**: Click **"Start Your Journey as Scrum Master"** to begin.
- **Purpose**: Understand the game’s rules and goals.

### 2. Team Selection

- **Overview**: Build your team by hiring employees within a $50,000 budget.
- **Steps**:
  1. Browse available employees (e.g., Frontend Engineer, Designer) with Junior, Mid-level, and Senior options.
  2. Check details:
     - **Cost**: How much they deduct from your budget.
     - **Capacity**: Story points they can handle per sprint.
     - **Efficiency**: How effectively they work (e.g., 1.2x for Seniors).
     - **Skills**: Frontend, backend, full stack, or design.
  3. Click **"Hire"** to add an employee to your team. The budget updates instantly.
  4. View your team in the "Your Team" section. Click the red **"X"** to fire an employee and recover their cost.
  5. Click **"Reset Team"** to start over if needed.
  6. When ready (at least one employee hired), click **"Continue to Backlog"**.
- **Tips**:
  - Balance skills (e.g., hire frontend and backend developers for versatility).
  - Seniors are expensive but efficient; Juniors are cost-effective but less productive.

### 3. Backlog Selection

- **Overview**: Choose products (tasks) from the backlog for the upcoming sprint.
- **Steps**:
  1. Review available products (e.g., "User Authentication", "Landing Page").
     - **Story Points**: Effort required (higher = harder).
     - **Skills**: Required expertise (e.g., frontend, backend).
  2. Note any **Carried Over Tasks** from the previous sprint—they’re mandatory.
  3. Click **"Select"** to add a product to your sprint (up to 8 total, minimum 3 including carried-over tasks).
  4. See selected products in the "Selected Products" section. Click **"Select"** again to deselect (except carried-over tasks).
  5. Click **"Back to Team"** to adjust your team, or **"Continue to Task Assignment"** when ready.
- **Tips**:
  - Match products to your team’s skills.
  - Avoid overloading—select tasks your team can realistically complete.

### 4. Task Assignment

- **Overview**: Assign selected products to team members based on their skills and capacity.
- **Steps**:
  1. See your team and their remaining capacity (story points they can handle).
  2. Drag products from "Unassigned Tasks" to team members, or use the dropdown to assign points.
  3. Confirm the task assignment by clicking **"Assign"** near the story point.
  4. You can assign more than one team member to work on a single task.
  5. Ensure skills align (e.g., don’t assign a backend task to a designer).
  6. Click **"Continue to Sprint Strategy"** when all tasks are assigned or you’re ready to proceed.
- **Tips**:
  - Distribute workload evenly to avoid overburdening anyone.
  - Leave some capacity unassigned if you anticipate challenges.

### 5. Sprint Strategy

- **Overview**: Choose strategies to guide your team’s approach during the sprint.
- **Steps**:
  1. Review options (e.g., "Focus on Quality", "Optional Overtime").
     - **Effect**: Impacts speed, quality, or morale (e.g., "Focus on Speed" increases points but risks bugs).
  2. Select up to 2 strategies by clicking them.
  3. Click **"Start Sprint"** to begin.
- **Tips**:
  - "Focus on Quality" reduces defects but slows progress.
  - "Optional Overtime" boosts output but lowers morale—use sparingly.

### 6. Sprint

- **Overview**: Simulate a 14-day sprint (adjustable later), tracking task progress and handling events.
- **Steps**:
  1. Watch the Kanban board (Backlog → In Progress → Testing → Done) as tasks advance daily.
  2. Drag tasks from **"Backlog"** to **"In Progress"** to start working on them.
  3. Respond to random events (e.g., "Team Member Sick"):
     - Read the description and options.
     - Click an option (e.g., "Redistribute Tasks") to proceed.
  4. Monitor progress bars, defects, and team morale.
  5. At the end, proceed to the next phase (Definition of Done or Retrospective).
- **Tips**:
  - Check defects in the Testing stage—tasks may need rework.
  - Events can disrupt plans; choose options that balance morale and progress.

### 7. Definition of Done (After Sprint 1)

- **Overview**: Set quality standards for task completion.
- **Steps**:
  1. Choose one option (e.g., "No more than one medium and two low-severity defects").
     - **Effect**: Stricter rules slow progress but improve quality.
  2. Click **"Select"** to apply it to future sprints.
- **Tips**:
  - "Balanced" is a safe starting point.
  - Adjust later if too many tasks fail to meet the standard.

### 8. Retrospective

- **Overview**: Reflect on the sprint and make improvement decisions.
- **Steps**:
  1. Read team feedback in three sections:
     - **What Went Well**: Successes (e.g., "High quality").
     - **What Could Be Improved**: Challenges (e.g., "Too many defects").
     - **Action Items**: Suggestions (e.g., "Better planning").
  2. Answer questions (e.g., "Adjust sprint length?"):
     - Click an option (e.g., "Increase to 3 weeks").
  3. Click **"Continue to Sprint Summary"** when all decisions are made.
- **Tips**:
  - Extend sprint length if tasks pile up.
  - Hire specialists if skills are lacking.

### 9. Sprint Summary

- **Overview**: Review your sprint’s performance.
- **Steps**:
  1. Check stats:
     - **Story Points**: Assigned vs. completed.
     - **Quality**: Percentage score.
     - **Team Morale**: Team happiness.
  2. Review sprint feedback, completed products, carried-over tasks, and rework.
  3. Click **"View Team"** to adjust your roster, or **"Plan Next Sprint"** (or **"Final Results"** after Sprint 3).
- **Tips**:
  - High quality boosts your score—fix defects early.
  - Low morale hurts the final score—avoid overworking the team.

### 10. Final Results (After Playing Three Sprints)

- **Overview**: See your overall performance after three sprints.
- **Steps**:
  1. Review:
     - **Final Score**: Combines points, quality, and morale.
     - **Total Story Points**: Across all sprints.
     - **Average Quality**: Overall product quality.
     - **Products Completed**: Number of finished tasks.
  2. Click **"View Sprint Summary"** to revisit details, or **"Start New Game"** to play again.
- **Tips**:
  - Aim for a score above 200 for a "Great job!" rating.

## Key Mechanics

- **Budget**: Starts at $50,000. Hiring reduces it; firing recovers costs.
- **Story Points**: Measure task effort. Completed points contribute to your score.
- **Task Stages**: Tasks progress from *Backlog → In Progress → Testing → Done*.
- **Defects**: High, medium, or low severity. Must meet the Definition of Done to finish, or require rework.
- **Team Morale**: Starts at 100%. Drops with overtime or poor results; boosts your final score if high.
- **Scoring**: Sprint score = completed points × quality %. The final score includes a morale bonus/penalty.

## Tips for Success

- **Team Balance**: Hire a mix of skills (frontend, backend, design) and levels (cost vs. capacity).
- **Task Selection**: Pick tasks your team can handle within the sprint length.
- **Quality Focus**: Use strategies like "Intensive Testing" to reduce defects early.
- **Morale Management**: Avoid "Optional Overtime" unless desperate—it hurts long-term performance.
- **Adapt**: Use retrospectives to adjust sprint length or team composition based on feedback.

## Troubleshooting

- **Button Not Working?**: Ensure you’ve met requirements (e.g., hired a team, selected 3+ products).
- **Game Stuck?**: Refresh the page to restart.
- **Slow Performance?**: Use a modern browser for the best results.

---

*Happy sprinting! Enjoy learning Scrum through this simulation.*

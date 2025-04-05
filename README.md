## Introduction

Welcome to the **Scrum Sprint Simulation**! This interactive game lets you step into the role of a Scrum Master, managing a virtual software development team through three sprints. Your goal is to deliver maximum value (measured in *story points*) and number of products while maintaining high quality and team morale, all within a **$50,000 budget**. You’ll hire a team, select tasks, assign work, respond to challenges, and reflect on your performance to improve.

This manual will guide you through each game phase, explain key mechanics, and offer tips for success. Let’s get started!

## Getting Started

- **Open the Game**: Download and load the HTML file in a modern web browser (e.g., Chrome, Firefox).
- **Dark Mode**: The game automatically adjusts to your system’s dark mode preference.
- **Objective**: Complete as many story points as possible across three sprints while balancing quality and team morale.

## Game Phases

### 1. Introduction Page (Intro)

- **What You See**: A welcome screen with game objectives and instructions. The instructions help you understand the game’s rules and goals.
- **What to Do**: Click **"Start Your Journey as Scrum Master"** to begin. 

### 2. Build Your Team Page

- **Overview**: Build your team by hiring employees within a $50,000 budget.
- **Steps**:
  1. Browse available employees (e.g., Frontend Engineer, Designer) with Junior, Mid-level, and Senior options.
  2. Check details:
     - **Cost**: How much is their salaries which they deduct from your budget.
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
  - For a more challenging play, you can try to choose the weakest workers (Junior) or a minimum number of employees.

### 3. Select Product Backlog Page

- **Overview**: Choose products (tasks) from the backlog for the upcoming sprint.
- **Steps**:
  1. Review available products in the "Available Products" section (e.g., "User Authentication", "Landing Page"):
     - **Story Points**: Effort required (higher story points = harder job).
     - **Skills**: Required expertise (e.g., frontend, backend).
  2. Note any **Carried Over Tasks** from the previous sprint—they’re mandatory and unchoiceable.
  3. Click **"Select"** to add a product to your sprint (up to 8 total, minimum 3 including carried-over tasks).
  4. See selected products in the "Selected Products" section. Click **"Remove"** to deselect (except carried-over tasks).
  5. Click **"Back to Team"** to adjust your team, or **"Continue to Task Assignment"** when ready.
- **Tips**:
  - Match products to your team’s skills.
  - Avoid **overloading**—select tasks your team can realistically complete.

### 4. Assign Task Page

- **Overview**: Assign selected products to team members based on their skills and capacity.
- **Steps**:
  1. See your team and their remaining capacity (story points they can handle).
  2. Use the dropdown to select team members to assign points.
  3. Confirm the task assignment by clicking **"Assign"** near the story point.
  4. You can assign more than one team member to work on a single task.
  5. You can adjust the story points that are planned to be assigned to each member by entering a number in the text box below the dropdown.
  6. Ensure skills align (e.g., you cannot assign a backend task to a designer).
  7. Click **"Continue to Sprint Strategy"** when all tasks are assigned or you’re ready to proceed.
- **Tips**:
  - Distribute workload evenly to avoid overburdening anyone.
  - You must assign all story points to proceed to the next page.
  - Leave some capacity unassigned if you anticipate challenges.

### 5. Sprint Planning Page

- **Overview**: Choose strategies to guide your team’s approach during the sprint.
- **Steps**:
  1. Review options (e.g., "Focus on Quality", "Optional Overtime").
     - **Effect**: Impacts speed, quality, or morale (e.g., "Focus on Speed" increases points but risks bugs).
  2. Select up to 2 strategies by clicking them.
  3. Click **"Start Sprint"** to begin.
- **Tips**:
  - Each strategies have different effects; you should carefully choose the desired strategies. It is also good to try different strategies in every sprint.

### 6. Sprint Progress Page

- **Overview**: Simulate a 14-day sprint (adjustable later), tracking task progress and handling events.
- **Steps**:
  1. Watch the Kanban board (Backlog → In Progress → Testing → Done) as tasks advance daily.
  2. Drag tasks from **"Backlog"** to **"In Progress"** to start working on them. Click **"Next"** to proceed with the work.
  3. Defects Generation
     - Each task will generate random defects, including **Low**, **Medium** and **High**.
     - After selecting the definition of "Done" (please reference to part 7), some of the tasks may need to be reworked due to too many defects and failed to meet the definition.
     - When tasks need to be reworked, click **"Move to In Progress"** to move the tasks back to the **In Progress** stage. Click **"Next"** to proceed with the work.
  5. Respond to random events (e.g., "Team Member Sick"):
     - Read the description, members' chat logs and responding options.
     - Click an option (e.g., "Redistribute Tasks") to proceed.
  6. Monitor progress bars, defects, and team morale. After the tasks are defined as **Done** in the **Testing** ("Ready to move to Done"), drag the tasks to the **Done** to record the tasks as finished. Click **"Next"** to proceed with the work.
  7. At the end, proceed to the next phase (Definition of Done or Retrospective).
- **Tips**:
  - Check defects in the Testing stage—tasks may need rework.
  - **Remember** to drag the finished tasks from **"Backlog"** to **"In Progress"**
  - **Remember** to drag the finished tasks to the **Done**.
  - Events can disrupt plans; choose options that balance morale and progress.

### 7. Definition of Done Page (After Sprint 1)

- **Overview**: Set quality standards for task completion.
- **Steps**:
  1. Choose one option (e.g., "No more than one medium and two low-severity defects").
     - **Effect**: Depends on which definition. Will affect the efficiency and quality.
  2. Click **"Select"** to apply it to future sprints.
- **Tips**:
  - "Balanced" is a safe starting point.

### 8. Retrospective Page

- **Overview**: Reflect on the sprint and make improvement decisions.
- **Steps**:
  1. Read team feedback logs in three sections:
     - **What Went Well**: Successes (e.g., "High quality").
     - **What Could Be Improved**: Challenges (e.g., "Too many defects").
     - **Action Items**: Suggestions (e.g., "Better planning").
  2. Answer questions (e.g., "Adjust sprint length?"):
     - Click an option (e.g., "Increase to 3 weeks").
  3. Click **"Continue to Sprint Summary"** when all decisions are made.
- **Tips**:
  - Carefully review the performance and read the feedback, extend sprint length if tasks pile up.
  - Carefully decide process improvement; it will affect the efficiency and team morale of the sprint.
  - Hire specialists if skills are lacking.

### 9. Sprint Summary Page

- **Overview**: Review your sprint’s performance.
- **Steps**:
  1. Check stats:
     - **Story Points**: Assigned vs. completed.
     - **Quality**: Percentage score.
     - **Team Morale**: Starts at 100%. Drops with overtime, poor results or different sprint strategies. It will boost your final score if high
  2. Review sprint feedback, completed products, carried-over tasks, sprint strategies, and rework.
  3. Click **"View Team"** to adjust your team formation, or click **"Plan Next Sprint"** to proceed (or **"Final Results"** after Sprint 3).
- **Tips**:
  - High quality boosts your score—fix defects early.
  - Low morale hurts the final score—avoid overworking the team.
  - Review the sprint strategies and Retrospective Decisions to further analyse the differences.

### 10. Final Results Page (After Playing Three Sprints)

- **Overview**: See your overall performance after three sprints.
- **Steps**:
  1. Review:
     - **Final Score**: Combines points, quality, and morale.
     - **Story Points Completed**: Across all sprints.
     - **Average Quality**: Overall product quality.
     - **Products Completed**: Number of finished tasks.
  2. Review all sprints' performances on the **Sprint Comparison** Table
  3. Review all completed tasks on the **Completed Products** Table
  4. Click **"View Sprint Summary"** to revisit the last sprint details or **"Start New Game"** to play again.
- **Tips**:
  - Aim for a score above 200 for a "Great job!" rating.
- **Scoring**: Sprint score = completed points × quality %. The final score includes a morale bonus/penalty.

## Troubleshooting

- **Button Not Working?**: Ensure you’ve met requirements (e.g., hired a team, selected 3+ products).
- **Game Stuck?**: Refresh the page to restart.
- **Slow Performance?**: Use a modern browser for the best results.

---

*Happy sprinting! Enjoy learning Scrum through this simulation.*

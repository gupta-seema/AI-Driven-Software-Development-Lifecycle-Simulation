# AI-Driven-Software-Development-Lifecycle-Simulation
```markdown
# AI-Driven Software Development Lifecycle Simulation

This project simulates the software development lifecycle (SDLC) using AI agents, each representing a specific role in the SDLC. The simulation generates user stories, calculates effort estimations, and distributes tasks into sprints, providing a comprehensive view of the project lifecycle.

---

## Features

- Role-Based AI Agents: Includes agents for Customer Proxy, Project Manager, Requirement Engineer, System Engineer, Software Engineer, Test Engineer, and Documentation Engineer.
- Dynamic User Story Generation: Automatically generates unique user stories for each role.
- Effort Estimation: Calculates the effort required for tasks using predefined productivity rates.
- Sprint Planning: Assigns tasks to sprints based on effort and capacity.
- Project Summary: Provides an overview of the total effort, project duration, and sprint breakdown.

---

## Technologies Used

- Jupyter Notebook: For interactive coding and execution.
- Python Libraries: 
  - `openai`
  - `langchain`
  - `pandas`
  - `random`
- OpenAI API: Powers the ChatGPT model for agent simulations.

---

## Getting Started

### Prerequisites

1. Python 3.8 or higher.
2. OpenAI API Key (replace the placeholder in the code with your actual key).
3. Install the required Python libraries:

   ```bash
   pip install openai langchain pandas
   ```

### Running the Notebook

1. Clone this repository:
   ```bash
   git clone https://github.com/gupta-seema/AI-Driven-Software-Development-Lifecycle-Simulation.git
    cd AI-Driven-Software-Development-Lifecycle-Simulation
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook AI_SDLC_Simulation.ipynb
   ```

3. Execute the notebook cells sequentially to simulate the SDLC process.

---

## Output Highlights

- Generated User Stories: Dynamically created tasks for each role.
- Sprint Plans: Tasks grouped into sprints with estimated efforts.
- Summary Table: Overview of user stories, including effort, status, and sprint allocation.
- Project Summary: Total sprints, effort, and estimated project duration.

---

## File Structure

- AI_SDLC_Simulation.ipynb: The main notebook containing the simulation code.
- README.md: Documentation for the project.
- GitHub Repository: https://github.com/gupta-seema/AI-Driven-Software-Development-Lifecycle-Simulation

---

## Future Enhancements

- Develop a web-based interface for enhanced interaction.
- Add more SDLC roles or increase the granularity of task breakdowns.
- Incorporate visualizations for project progress and sprint metrics.

---

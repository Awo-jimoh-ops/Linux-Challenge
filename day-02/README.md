# Day 02 - [Topic]

## Objective

What was the goal for today?

The goal for today was to practice organizing and modifying a real-world project using Linux terminal commands. I focused on restructuring a Terraform-based repository, improving file organization, and making configuration updates without executing any infrastructure changes.

---

## What I Learned

- How to efficiently restructure a project using basic Linux commands like mv, cp, and mkdir
- How to perform bulk file edits using tools like sed and search through files using grep
- The importance of organizing infrastructure code into logical directories for maintainability
- How small changes in configuration files (like variables and naming) can improve clarity and scalability

---

## What I Built / Practiced

- Reorganized a Terraform project by separating infrastructure, configuration, and scripts into dedicated folders
- Modified Terraform files by renaming variables and updating configurations using terminal-based tools
- Created supporting directories (infra/, config/, scripts/, docs/) to improve project structure

---

## Challenges Faced

- Ensuring consistency when renaming variables across multiple files without breaking references
- Avoiding accidental overwrites while moving and restructuring files

---

## Key Takeaways

- Clean project structure is critical for scalability and team collaboration
- Linux commands can significantly speed up repetitive file operations
- Careful validation is needed when performing bulk edits across multiple files

---

## Resources

- Linux Command Line Basics
- Terraform Documentation

---

## Output

- Refactored project structure:

```
    .
    ├── infra/
    │   ├── main.tf
    │   └── variables.tf
    ├── config/
    │   └── terraform.tfvars
    ├── scripts/
    │   └── setup.sh
    └── docs/
        └── README.md
```

![Day 02 Output](https://github.com/Awo-jimoh-ops/Linux-Challenge/blob/main/day-02/Screenshot%202026-04-03%20at%2022.44.57.png)

![Day 02 Output](https://github.com/Awo-jimoh-ops/Linux-Challenge/blob/main/day-02/Screenshot%202026-04-03%20at%2022.47.07.png)

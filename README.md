# Eligibility Check System

> A user-friendly system that greets users and prompts them to enter their name for eligibility checks, designed for seamless integration and testing.

## Getting Started

These instructions will guide you on how to set up the development environment and contribute to the project.

### Prerequisites

Before installing the software, make sure you have the following:

- Git installed on your machine
- A working clone of the repository
- Zoom for team collaboration and screen sharing

### Installation

Follow these steps to get the development environment up and running:


```
$ git branch # Check your current branch $ git switch develop # Switch to the develop branch $ git pull # If you cloned before 'develop' was created, run this to retrieve the branch 
$ git checkout -b feature-a # Create and switch to the feature-a branch
```


```
Create two new JavaScript files and add the provided code:

1. `welcome.js`:
```javascript
import { verifyName } from './getName.js';
console.log("=".repeat(35));
console.log("Welcome to eligibility check");
console.log("=".repeat(35));
console.log("\n");
const userName = verifyName(username);
console.log(`Hello ${userName}!\n`);
```

```getName.js

export function verifyName() {
  const input = prompt("Enter your age: ");
  return input;
}
```


## Usage

A few examples of useful commands and/or tasks:

```
$ git pull                      
$ git branch                    
$ git status                   

```

### Branches

* **Main**: The primary branch for the production-ready code.
* **Develop**: The secondary branch for the production-ready code.
* **Feature**: Branches for adding new features, such as feature-a.





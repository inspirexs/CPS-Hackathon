# CPS Hackathon

## Task
Create a **Project Structure** for **TRIP Cascading Logic**  
Scope: **NEW NCPT Cascading Logic (from 12.01.2026)** 
Docs: https://globalblue.atlassian.net/wiki/spaces/UoVTP/pages/2178220243

---

## Process
- Split randomly into **teams**
- **Q&A + DEVs**

---

## How

### Execution
- Each team creates a **High-Level Project Structure**
- The project **must be buildable**
- Focus on **structure and contracts**, not implementation

---

### Artifacts (Contracts)

Create **skeletons only** for:

- **Config** (Spring Security / RMQ config – structure only)
- **DTOs** (do not need to be complete)
- **Services**
- **Interfaces**
- **Business Logic classes / packages / high-level method calls**
- **Repositories**
- **REST Clients**
- **Specific methods with high-level INPUT / OUTPUT**
- **Comments (useful comments and short)**

---

### What Is NOT Needed
- Actual functionality implementation
- Specific SQL statements
- Helpers / utils
- Infrastructure setup  
  (RMQ queues, Spring Security, etc.)
- Low-level code
- Optimizations

---

### Focus
- Feature boundaries
- Package names
- Class names
- Module placement
- DTO names
- Artifact placement
- Flow readability
- Easy onboarding for newcomers

---

## Output
- Buildable project skeleton
- Clean slate → new console application
- Structure aligned with existing diagrams
- Clear feature ownership and contracts

---

## Initial Project Structure
- **1 project**
- Top-level packages represent **modules**

---

## Repository
- GitHub: `https://github.com/inspirexs/CPS-Hackathon.git`
- Branch: `cps-hackathon-base`
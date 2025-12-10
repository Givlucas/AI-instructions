# Claude Instructions

Personal development philosophy and working principles.

## Core Philosophy

### On Design
- Code should be explicitly designed, not thrown at a wall to see what sticks
- Always verify core assumptions—it is dangerous to assume anything
- There is a huge difference between what a program is designed to do, what it should do, and what it currently does
- Before starting an algorithm, ask: what information do you want to know?
- Start by figuring out what a service does, then figure out what it needs to know

### On Services
- If a service call always returns the same result for the same parameters, make it a library instead
- Services only make sense when they change something in the world
- State and state changes are unavoidable concerns in service-based architecture
- Business entities going through milestones can be viewed as different things at each state, not a single entity with booleans

### On Documentation
- Documentation should capture the *what*, the *why*, and the *how*
- If something is not immediately obvious, document it
- The why and goal of code should be captured in comments around that code—comments provide context
- Use concise and specific wording; imprecise language makes reasoning difficult
- Never document other people's systems beyond overview or introductions
- If you can Google it or read it in a dictionary, you don't need to explain it
- Architecture documentation should explain what tools are used and what features are relied upon

### On Code Quality
- Refactor code before implementing new features—ask "can I make implementing this easier?"
- Clean up as you go; don't generate large messes to clean later
- Consistency reduces cognitive load and allows safer assumptions
- Programmatic solutions are better—they are more robust and can be proven correct

### On Assumptions
- Just because something is popular doesn't mean it's right
- Just because something already exists doesn't mean it was a good idea
- Open source software IS designed—just because they aren't using your idea doesn't mean it's bad
- Never assume competence

## Working Preferences

### File Organization
- When creating file structures, add a README to each directory describing purpose of subdirectories (unless painfully obvious)
- Architecture documents should be stored consistently and alongside source code for version control

### Code Style
- Logs should be one line if not written to logging software or following structure for parsing
- Writing code is easy; knowing what to write is the hard part

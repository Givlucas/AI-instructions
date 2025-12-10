#action
#published 

# Notes

# Statement of action

# Statement of inputs

# Statement of specifications
- Must be file based.
# Statement of design

## Output: action lite file based system

#### Design
Action lite is similar to the action design system in goal but reduced in scope to accommodate the restrictions of its medium. Action lite is a file based task tracking system that uses acyclic directed meta graphs to track task requirements. Action lite uses a main directory to store all of its actions. Each action is stored in a markdown file and has the following tags \#action, \#(state), \#(project name). This allows for easier identification and sorting. If an action has a meta-graph a directory sharing the same name as the file will be stored at the same level. All actions belonging to the meta-graph are stored here. A meta-graph directory can exist without an associated action.

The structure and types of status are unchanged from normal action, with the action title as its file name.
1. Notes - general notes on the task
2. Statement of Action - The task to be performed, more in depth than title, may include why the action is needed
3. Statement of Inputs - a markdown bullet list of .md links to other action files. or wiki links
4. Statement of Design - One output and design section per output
	1. Output - the action produced by the design
		1. Design - A detailed design for how to proceed.
5. Analysis of Impact

sections are denoted by a markdown "#", with a space and the name of the section following.

Below are the possible states for an action. Each tag should be lowercase.
6. discovery - all actions start here
	- outputs: Title, Notes, Statement of action, statement of inputs, statement of specifications
7. design 
	- outputs: Statement of design
8. implementation - Follow design to completion
9. test - go back to design if tests fail
10. document - Statement of Analysis
11. publish - Deploy changes / make available
12. published - Available for use.

State tags may be present at any point of the file

Actions may also be tagged with \#priority to mark them as important. But the tag should be removed once completed.

Actions can stay uncompleted for an infinite amount of time.
#action #action #priority #AI
#Discovery

# notes
This should live in the other repo not here.
## sonnet 4.5 action cli - post mortem Attempt 2
How it failed. Application worked and code appeared to be written well. However it did not meet specifications\. I did a tree again instead of the proper behavior.

Also of note. it seemed to expand on action ALOT. It would write alot of code in the design and was a overly verbose in its testing.

### What could have been done better
- removed statement of impact, it didn't really need this. Seems extra for action anyway
- Use git frequently
- VM for fully autonomous agent self management 
- rust project guidelines skill
- nix project guideline skill
	- needs to know that its on a nix system
- reproducibility guidelines skill
- researcher agent
- Instead of action orchestrator main agent should be action orchestrator?
- Action orchestra-tor still asked me too many questions. Probably need to give it more guidance. More structured workflow. Was not autonomous enough
- wouldn't use agents unless specifically asked
-  #harness based systems. Ledger stuff giving it a memory. I think the "notes" section is incredibly important here. But maybe a larger scale ledger would also be useful? This is called "Domain memory"
- see how far you can go only using opus 4.5
- should action have a fomatter header for metadata.
- Need to fully define action light
- Need define a agent workflow that's uses action ( this could go somewhere else )
## what went right
- no crashes on the first run after the AI said it was finished meaning test based development worked.

# statement of action
Using create strategy for building with LLMs to explore and learn about the systems. Use this system to build the action light CLI tool to evaluate its effectiveness.

# Statement of inputs
- 
# Statement of specifications
- tool must have the following features 
	- Built in rust
	- contains a nix flake for development and packaging
	- features
		- list all actions and their status
		- list priority items
		- list continuous items
		- list items by status
		- create a new empty action with all sections
		- add new inputs to an action
		- move actions and update all input references to them
		- change the status of an action
		- graph the actions in terminal as a flow chart for a single level. Allow user to enter a actions metagraphs if present. Should take over entire terminal screen.for a sing
		- colored output
	

# Statement of Design
## Output
### design
using Claude code to create CLI helper tools for working with the action lite framework ... 
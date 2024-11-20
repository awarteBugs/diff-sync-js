## Q&A
- [ ] which implementation of diff-patch-Algorithm
	- **semantic diff and patch algorithms** (aim is to find changes in terms of the semantic meaning of text, rather than purely syntactical or character-level differences.)
- [ ] Where are the documents & the shadows
	- API, line 46
	- client, line 115
	- src/index.js Line 68: `const { shadow, backup } = container;`
- [ ] How and why can we adjust the sync-cycle? What are the dis-& advantages?
	- sync cycle can be adjusted to balance system responsiveness and network traffic
	- Shorter intervals improve responsiveness but increase computational load and network usage
	- Longer intervals reduce these factors but may lead to higher merge conflict rates and slower synchronization
	- paper suggests adaptive timing that modifies the update frequency based on current activity​
- [ ] Where/How is the edit-Stack implemented
- [ ] Is it possible to deploy a Peer-to-Peer Version of Mr. Wei'S implementation
- [ ] How is it possible to use the API in other JS-Projects
- [ ] Are the JSON-Docs interchangeable with other kind of Docs?
- [ ] How is Mr. Wei solving the conflicts?
- [ ] What are the possible enhancements of Mr. Wei's Code? Should you suggest a pull-request?


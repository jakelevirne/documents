## The Goal
i type more and more I keep typing

how often does the right thing happen??


SpecStory is your trusted guide in this transformation from code-driven development to Spec-driven Development

## Major components

The work surface (**gathering intent \- implicit or explicit**)

- VSC Extension Maintenance  
- Cursor Extension  Operating  
- SpecStory CLI Delivering  
- BearClaude Delivering  
- Mobile app Contemplating  
- Grammarly-style overlay (for ChatGPT Desktop and Claude Desktop) Contemplating

Cloud (**collaborating around that intent across projects and/or with your team**)

- One aggregate place for all your chats, docs, and stuff Shaping   
  - Similar idea of the “messy bin” vs. the decision log  
  - Three streams (distinct types of content)  
    - AI chat history \- Delivering   
    - Planning docs (CRDT micro-versioning) \- 2nd  
    - Code (git for mortals, VibeVersion) \- 3rd  
  - **API first** \- build what you want on the log stream  
- Value from the Exhaust  
  - Insurance / feel good Operating  
  - Search Delivering  
  - Social proof \- badges, etc Contemplating  
    - Tellit  
  - Discussion Guide Shaping  
  - Ready-to-paste context Contemplating  
  - Share context with my teammates to help them Contemplating  
    - GOOD  
    - **Resume** someone else’s Claude Code chat session

GTM / Distribution (**build it, but they won’t come**)

The overarching theme for Distribution is **education (or is it open intent?)**. The way software gets built is changing. 

- Get lightning talks out in the world week of Jul 14, 2025  
- Get the Maven course launched by Aug 9, 2025

Most interesting experiment:  
Tny Studio (**our app production company)**

- (Internal) tnyats (applicant tracking) \- Operating [specstory.com/admin](http://specstory.com/admin) – needs packaged  
- (External) Tny.dev (links) \- Delivering  
- (External) tnyats  \- Shaping  
- [Tny Domains ](https://docs.google.com/spreadsheets/d/1J6lOnVKWEnJYn5y3RBtMhblU48fADJybFUAuoUK_1ow/edit?usp=sharing)  
- Create apps for learning and courses  
- Create apps to sell to startups and small businesses

Educational deliverables:


- [\[Maven Course 3-day Remote Intensive\] PMing agents to build software - Second Draft - July 2025](https://docs.google.com/document/d/1PU8Y8N1KeLaqK2o8gFZ7EDNCzP33K__Gjxf0YTFhIGs/edit?tab=t.0) Shaping

## 

Spec’ing Tools (**getting better at expressing / refining intent as an individual**)

- Blank page Shaping \- target   
- Dependent living documents (Stencils)  Contemplating  
  - Generating Discussion Doc from Chat History, Workplans, and Git  
- The counsel of elders  Contemplating  
- Hemingway or Grammarly style overlay on spec docs Contemplating  
- Commenting / proposed changes Contemplating  
- The messy “idea bin” vs. the refined spec. Contemplating

## 

## BEARCLAUDE GTM

### Main distribution channels 

(How will people initially find out about Bearclaud & new CC wrapper)

- Our e-mail list from the extension  
- Social posts on LinkedIn / X  
  - Personally (jake, greg, sean) and on LinkedIn SpecStory and  
  - Via retweets or specific posts from close friendlies (Tom Doerr, Hamel, Eugene Yan, Others)  
  - PAID X influencer multi-tweet posts  
- On r/ClaudeAI  
  - On very specific Claude Code github issues (example: [print mode last messages · Issue \#873 · anthropics/claude-code](https://github.com/anthropics/claude-code/issues/873))  
- Updates to SpecStory Extension docs themselves  
  - In the READMEs of the extension  
  - In and on our docs site “Try this\!”  
- Plugs in our newsletters (Intent Driven, Meditations on Tech)  
  - reletter.com  
    

### Activities

- Actually update our tracker once we’ve rundown this list[\[SpecStory\] Launch Tracker - Last Updated March 25 2025](https://docs.google.com/spreadsheets/d/1n6KFO8urzXYuv3aHcSL4ImEM6Q5_VIn6Et5U_NpPWJ0/edit?gid=1377325767#gid=1377325767)  
- Tola: ask to kick the tires w/ anthropic surreptitiously re: partnership around driving usage to bearclaude (and name ofc)  
- Marketing Sites & Docs  
  - Polish bearclaude.com w/ product imagery, download links, all working links  
  - Update docs.specstory.com with a how to and overview of bearclaude and cli wrapper  
  - Update specflow.com examples to “open/download in bearclaude  
- GitHub repos and org page	  
  - Update to reflect 3 “extensions”, bearclaude tool, etc  
- Marketing Copy  
  - Write e-mails for distribution announcement for resend  
  - Update Extension README and Changelog  
    - Add a link in the settings panel of specstory.com extension that links to bearclaude.com  
  - Write social posts (linkedin, twitter, reddit (for announcement)  
  - Write launch post for specstory.com blog (verbiage can be used  
- Marketing video?  
  - We should probably make *something* for Bearclaude, even if its a small version of us using it etc  
    - We can save the more polished launch video that we pay for when we launch first paid product

## BEARCLAUDE Proto Roadmap

### V0 BEARCLAUDE \- aka alpha in the dark

- Feels like:  
  - The missing notebook to complement Claude Code’s minimalism  
- Stands out because:  
  - Beautiful Focused Experience  
  - Nice though not *great* Markdown  
  - Auto-saved docs and chats (from Claude Code)

V0.25 (Now) \- aka widely pushed alpha

- \[\#1\] Great spec authoring guidance  
  - Jake shaping  
- \[\#2\] Claude Code history experience  
  - Sean implementing  
- Tablestake Claude Code experience  
  - Sean implementing  
  - Quality bar: run Claude Code in Apple Terminal on a Mac  
- Tablestake markdown experience  
- Copy/Paste  
  - Select all in BearClaude, copy, paste into VSCode. Select all in VSCode, copy, paste into BearClaude. Nothing changes.  
  - Select all in VSCode, copy, paste into BearClaude. Make one edit. Copy, paste into VSCode. Diff and ensure you get only the expected edit.  
- Basic editor actions  
  - Keys/Clicks  
    - Cmd-A \- Select all  
    - Cmd-up \- Top of doc  
    - Cmd-down \- Bottom of doc  
    - Cmd-left \- beginning of line  
    - Cmd-right \- end of line  
    - Arrow keys \- move as expected  
    - Shift \+ any of the above \- select text  
    - Double click \- select word  
    - Triple click \- select line  
  - Scrolling  
    - Smooth  
    - Distortion free  
  - Typing  
    - Smooth  
    - Distortion free  
- Undo / Redo  
  - Works as expected  
  - Even works after closing and opening the file  
- Fonts / styles  
  - Current font in BearClaude is good  
  - Current line spacing in BearClaude is good  
  - Specific improvements for specific items noted below  
- Paste rich text from ChatGPT or Claude  
  - No words are lost  
  - Rich text formatting is converted to Markdown  
- Lists  
  - Continuation (enter at the end of one item creates the next item)  
  - Correct auto-numbering  
    - Even with intervening text  
  - Tab/Shift-tab to indent/unindent  
    - Multi-line indent/unindent  
- Checkboxes  
  - Type to create or check off/on  
    - Click to check off/on  
  - Inline code  
- Links  
  - Ability to follow links (within project and external)  
- Images  
- Tables  
- Code blocks  
- Future: Mermaid diagrams

### V0.5 BEARCLAUDE (Next)- aka beta

- Feels like:  
  - The missing **masterful** notebook to complement Claude Code  
- Stands out because:  
  - Great live preview Markdown  
  - Your docs and chats are auto-versioned locally  
  -  Co-author *helps* you write better (BYOK)

### V1.0 BEARCLAUDE (Future) (when we ship paid)

- Feels like:  
  - The missing **magical** notebook to complement Claude Code  
- Stands out because:  
  - Your docs and chats (and code?) are synced everywhere  
  - You can access and work on them via iOS app  
  - Your docs are dependent on one another and update based on Stencils

—
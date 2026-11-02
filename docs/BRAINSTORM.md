# Agent - Broski

- an "everything" agent
- stored as an app or program on my computer
- it opens whenever the computer OS boots
- has access to my whole file system
- model: deepseek v4 flash
- has the following parts
    - tasks
    - calendar
    - notes
- detailed memory
- it has access to the web
- it has a personality
- it will be hosted on vercel so i can connect through my phone
- i will be able to talk to it
- all sessions will be saved, and when the session closes, it renames itself to something better

## Coding

### Planner

- this is where i will plan projects
- no code will be written
- uses: opus 5.5 through api key

### writer

- this is where code will be written
- uses: gpt-6-luma, or deepseek-flash

### Code reviewer
- reviews the code that the inferior models wrote

### Coding loop

```
1. Plan   --->   2. write   --->   review   --->   approval   --->   approved   ---> commit>push>merge
                      |                               |
                      <---         user input     <---<

```
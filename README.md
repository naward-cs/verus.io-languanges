
# verus.io-languanges
Repository for the multi-language features to support the Verus.io website

## How to contribute
 - This repository contains a `template` branch containing the English language supporting verus.io website. The JSON files contain a `key` that is referenced in each page with the contents in the language that will be created.
 - A branch will be created for each language to maintain continuity and prevent unnecessary changes to the main branch.
 
 The following processes will be done to ensure proper incorporating of the language into Verus' website:
 1. Create new branch for language contributing to.
 2. Initialize newly created language branch
 3. Make edits
 4. Submit language for use
 
 ### Steps to create a language branch
 5. Pull repository to local host `git clone https://github.com/nwardFoleum/verus.io-languanges.git`
 6. Run the command `git checkout template`. 
 7. Run the command `git checkout --orphan <languange>`

### Initialize the the language branch
1. change the directory from language to the approved html abbreviation (e.g. en => english, es => spanish, etc.)
2. Run the command `git add .` to add the new named directory to the language branch you created.
3. Run the command `git commit -a` as this will be to initialize the language branch.

### Make edits
When making edits, do not change the value of the key or the language support will not work

### Submit language for use
After completing all edits, ensure you commit all changes `git commit -a` then setup the ability to push those changes to github with `git push --set-upstream origin <language>` and push the language for submission `git push`

Notify one of our team members via twitter or discord, as the team will pull the new language into the main branch for languages and add the language option to the website.
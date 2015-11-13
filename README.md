# whiteflagcongress
Website being constructed for Americans for Limited Government, Eagle Forum project.

Workflow: Dev -> gh-pages -> master
NEVER WORK IN MASTER.

# Branches
---
## Master 
Everyone clones from here.  PRs are merged into master once passing tests and approved fixes.  For the love of god do NOT commit edits to master. Work in dev.  God help you if you do work in Master.  Your shit will get reverted faster than....something really fast.

## gh-pages
**Consider this the 'staging' branch.** PRs are merged here once fixes are ready for live.  This is the site live.  This is for client viewing and QA.  Merge to master upon approval of changes.

## development
Build here.  Merge into gh-pages for review.  If passes review, merge into master.

---

If you need to clone this repository, create a branch called wfc-YOURNAMEHERE.  Do your shit, create a pull request from the development branch.  garzo will inspect and merge accordingly.  Cut off for commits to gh-pages is 0100 EST.

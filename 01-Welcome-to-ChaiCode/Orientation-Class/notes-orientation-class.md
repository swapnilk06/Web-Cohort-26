# Orientation Class

<small>[27-12-2025]</small>

### ❓Questions

- **Q:** How to work on it? How to start on it?

> <strong>"Just Do What You Are Told"</strong>

<br>

# Git & Github

> <strong>`Why?`</strong>

### ❓Questions

- **Q:** Why we can learn?
- **Q:** What problem to learn git? What reason for git invent? Why is it IMP for us?

- [x] "Why" always present for anything we can start to learn.

## Git - Why should learn it? (Problem statment way)

Imagine Story - Pendrive problem

### Before or without any git or another version control system..

[X] Piyush Sir - Can try to make project with some project code files - Project always overtime grow phase - Piyush sir, need little help form Hitesh sir for adding some adding (that feature unknown for P'Sir) - Project code are in MAC book -> for transpfer ZIP or direct code through `PenDrive`-> & its give to Hitesh sir

[X] Hitesh Sir

- He will plugin the PenDrive, Shift their feature in that code
  - Hitesh sir add new code & return back PenDrive to Piyush sir

[X] Piyush Sir - He didn't required their old own code -> deleted it - From PenDrive there are new code present more than old code - Piyush sir don't know about `what changes are done by hitesh sir?` `what code they removed or add?` `what code changes?`

> Final code are gives from Hitesh sir but `small problem they can faced`

[x] Hitesh Sir

- Hitesh sir, realise some bug in their code & fix it.
- but that code not goes to Piyush sir.
- Communicate Hitesh sir to Piyush sir for he required PenDrive to fixed for gives their updated code.
- Piyush sir give PenDrive to Hitesh sir & they can remove old code from PenDrive & `patch`(quickly update some code) bug free code.
  - Updated PenDrive gives to Piyush sir.

[x] Piyush Sir - Patch code are bug free, but Piyush sir don't know bug in that code - Piyush sir don't know what difference in between or what changes in that `old code & new code`.

#### We can face small problem

> - We `can't track` which code that can change.
>   Updated code are present both side Hitesh sir, Piyush sir( but PenDrive present Piyush sir)

- Piyush sir make changes in PenDrive
- Hitesh sir can't update code beacuse PenDrive present in their Piyush sir.
- Hitesh sir has also present code copy they can also change code, but Hitesh sir & Piyush sir have goes to `out of sync`.
- PenDrive present which ever side Piyush side `at a time only one developer can work`.
- That means `collabration doesn't exist`.

> - Collabration not possible.(at time one developer can work)

- By chance Hitesh sir changes done in their own code.
- Hitesh sir & Piyush sir have two different version of same product code (feature divides both side) -> `Now its total are miss`.

[x] - Both are decide to overcome problem we can't edit in their code

- At a time one developer can work on it (Collabration not possible)
- Not conflict the code.

> Does that solve the problem kind of yes `not any conflict`. -> at a time one user work on it & don't out of sync that.

- But not completetly right answer.
- <strong>That problem face in between two developer</strong>

- [x] Anirudh Sir
- They came in that game, `they more difficult in three developer`

> All they have own seperate copies of code -> they can update own code (without PenDerive)

> Now we have three different copy of same code & we have no way to `track` which code, which sir.

> One condition that code more big & buggy we don't know -> which changes of Piyush sir, Hitesh sir, Anirudh sir

> [x] Collabration is big problem

- for single person that is not big problem
- problem came when we can try to work as soon as with collabration

- We can identify problem -> to solve that particular problem `we need some kind of system`.

#### We can build system to solve that problem

- `ChaiCode Code Tracker`(CCCT) We can build it -> `to track our changes`
- We can install CCCT in our PenDrive -> any developer can change any thing in code CCCT can track that every file.

- [x] We solve code Tracking problem
- Through that we can knows who can change, what change, change time...
  - We can catch any bug, we can easily track & revert that because know of -> `diff`

> We have still one problem of collabration that can not possible in that.

    - Which one have PenDrive they can only work (not work all developer at time)

- [x] We solve Collabration problem
- We can required `central server` as we can assume -> `Single Source Of Truth`

> PenDrive problem -> which one have PenDrive, only they can have access.

- Required cloud -> `Single Source Of Truth` -> We can trust to you which ever data is our latest data.
- Assume PenDrive -> `Source Of Truth`
- Hitesh sir, Anirudh sir -> both have own copy, but which code on PenDrive.

> But PenDrive not can access from multiple places, then we can make Source Of Truth is -> `Server`

- Hitesh sir, Anirudh sir, Piyush sir both's are connected with server

- [x] CCCT are installed on the `server` then -> ChaiCode Code Tracker Server

> Pendrive logic are ended.

### Changes push on -> `ChaiCode Code Tracker Server`

- We can push on server means, Hitesh sir, Piyush sir, Anirudh sir -> all for pull code from it.

#### Two main components -

- [x] Server i.e.`Server`
  - Server act as a central source of truth
- [x] CCCT i.e. `ChaiCode Code Tracker`
  - On the server CCCT are installed on it.

> All collabration problem can solve from `ChaiCode Code Tracker Server`

- [x] ChaiCode Code Tracker -> its our `Git`
  - Git as only work for a `tracking`
- [x] We don't have server, we can't collabration done -> i.e. our `Github`

> Github is a -> server, they can host -> `Git`

- [x] for host `Git` multiple provider are available
  - Own Server e.g. Swapnil K, Bitbucket, GitLab, GitTea
  - All have server can host git

[x] What is Git ?

- `Aactual Version Controlling System` -> Tracker
- Git work as -> `track changes of code`, which one can do which thing

### We can use Git on local system?

- [x] Piyush sir
  - They have big code with only they have developer
  - CCCT we can used in local? -> yes
  - Benefit of that we can track own changes
  - We can use also only `Git` -> independently use it also locally.

### Github come to

> Git don't about any Github like server present

- Git build first time for local system only -> `for tracking self chsnges only`(own project tracking)
- Git is a `independent` Software

> We can face collabration problem through PenDrive then we can shift to -> `Server`

> Two persons can't collabration at time on internet then host into `server`

- That is when Github(Server Host) came into the picture

#### How to Git envalution

- [x] Linus Torvalds -> Linix & Git founder
  - They can difficult to track self linux project while growing stage
  - They build side project of `Git` to track the code of the linux

## Techical way of Git

- [x] VCS - Version Control System -> `GIT`
  - VCS (tracker not word VCS is that) -> GIT
  - e.g. Apache, Mercurial, Subversion...

> `Git` -> most poular one

> Gitlab - <i>`Not VCS`</i> Its server VCS server

- [x] VCS Remote -> `Remote Server`
  - Github, Gitlab, GitTea(for self host of Github), AWS CodeCommit, BitBucket

> Don't learn anyone Github i.e. server we can learn `Git` that is VCS or tracker

## How to track git internally? - logic behind that git

### Git system -
- Linux Torvalds start to building Git problem faced `where to store changes of tracking of code`

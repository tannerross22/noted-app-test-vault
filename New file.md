# Test Case 1

Testing but no sync button appearing

<br />

<br />

Sync

<br />

New  changes, smanges

<br />

Sync attempt 3

<br />

<br />

\[gitStatus] Current status:

(no changes)

\[gitStatus] Current status:

&#x20;M "New file.md"

\[gitSync] ========== STARTING SYNC ==========

\[gitSync] Vault: C:\Users\tanne\Downloads\Not\_a\_repository

\[gitSync] Message: vault sync: 2026-05-13 18:23:32

\[gitSync] git add -A completed

\[gitSync]   stdout: ""

\[gitSync]   stderr: "warning: in the working copy of 'New file.md', LF will be replaced by CRLF the next time Git touches it

"

\[gitSync] >>> Files staged, creating commit...

\[gitSync] git commit completed

\[gitSync]   stdout: "\[master 9b65f4b] vault sync: 2026-05-13 18:23:32

&#x20;1 file changed, 7 insertions(+), 1 deletion(-)

"

\[gitSync]   stderr: ""

\[gitSync] >>> Commit created, pushing to remote...

\[gitSync] git push -v completed

\[gitSync]   stdout: ""

\[gitSync]   stderr: "fatal: The current branch master has no upstream branch.

To push the current branch and set the remote as upstream, use

&#x20;   git push --set-upstream origin master

To have this happen automatically for branches without a tracking

upstream, see 'push.autoSetupRemote' in 'git help config'.

"

\[gitSync] Error in git push: Command failed: git push -v

fatal: The current branch master has no upstream branch.

To push the current branch and set the remote as upstream, use

&#x20;   git push --set-upstream origin master

To have this happen automatically for branches without a tracking

upstream, see 'push.autoSetupRemote' in 'git help config'.

\[gitSync]   Full error: Error: Command failed: git push -v

fatal: The current branch master has no upstream branch.

To push the current branch and set the remote as upstream, use

&#x20;   git push --set-upstream origin master

To have this happen automatically for branches without a tracking

upstream, see 'push.autoSetupRemote' in 'git help config'.

&#x20;   at genericNodeError (node:internal/errors:985:15)

&#x20;   at wrappedFn (node:internal/errors:539:14)

&#x20;   at ChildProcess.exithandler (node:child\_process:417:12)

&#x20;   at ChildProcess.emit (node:events:509:28)

&#x20;   at maybeClose (node:internal/child\_process:1124:16)

&#x20;   at Socket.\<anonymous> (node:internal/child\_process:481:11)

&#x20;   at Socket.emit (node:events:509:28)

&#x20;   at Pipe.\<anonymous> (node:net:350:12) {

&#x20; code: 128,

&#x20; killed: false,

&#x20; signal: null,

&#x20; cmd: 'git push -v'

}

Error occurred in handler for 'git:sync': Error: Command failed: git push -v

fatal: The current branch master has no upstream branch.

To push the current branch and set the remote as upstream, use

&#x20;   git push --set-upstream origin master

To have this happen automatically for branches without a tracking

upstream, see 'push.autoSetupRemote' in 'git help config'.

&#x20;   at genericNodeError (node:internal/errors:985:15)

&#x20;   at wrappedFn (node:internal/errors:539:14)

&#x20;   at ChildProcess.exithandler (node:child\_process:417:12)

&#x20;   at ChildProcess.emit (node:events:509:28)

&#x20;   at maybeClose (node:internal/child\_process:1124:16)

&#x20;   at Socket.\<anonymous> (node:internal/child\_process:481:11)

&#x20;   at Socket.emit (node:events:509:28)

&#x20;   at Pipe.\<anonymous> (node:net:350:12) {

&#x20; code: 128,

&#x20; killed: false,

&#x20; signal: null,

&#x20; cmd: 'git push -v'

}

\[gitStatus] Current status:

(no changes)

<br />

<br />

<br />

<br />

<br />

<br />

<br />

<br />

<br />

<br />


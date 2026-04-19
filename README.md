2026-04-19T17:27:23.3446336Z Current runner version: '2.333.1'
2026-04-19T17:27:23.3465715Z ##[group]Runner Image Provisioner
2026-04-19T17:27:23.3466326Z Hosted Compute Agent
2026-04-19T17:27:23.3466761Z Version: 20260213.493
2026-04-19T17:27:23.3467225Z Commit: 5c115507f6dd24b8de37d8bbe0bb4509d0cc0fa3
2026-04-19T17:27:23.3468027Z Build Date: 2026-02-13T00:28:41Z
2026-04-19T17:27:23.3468532Z Worker ID: {e78f9d09-8aaf-4eb1-9b63-3bdeb466d674}
2026-04-19T17:27:23.3469068Z Azure Region: westcentralus
2026-04-19T17:27:23.3469594Z ##[endgroup]
2026-04-19T17:27:23.3470603Z ##[group]Operating System
2026-04-19T17:27:23.3471086Z Ubuntu
2026-04-19T17:27:23.3471606Z 24.04.4
2026-04-19T17:27:23.3471998Z LTS
2026-04-19T17:27:23.3472345Z ##[endgroup]
2026-04-19T17:27:23.3472789Z ##[group]Runner Image
2026-04-19T17:27:23.3473196Z Image: ubuntu-24.04
2026-04-19T17:27:23.3473663Z Version: 20260413.86.1
2026-04-19T17:27:23.3474724Z Included Software: https://github.com/actions/runner-images/blob/ubuntu24/20260413.86/images/ubuntu/Ubuntu2404-Readme.md
2026-04-19T17:27:23.3475912Z Image Release: https://github.com/actions/runner-images/releases/tag/ubuntu24%2F20260413.86
2026-04-19T17:27:23.3476662Z ##[endgroup]
2026-04-19T17:27:23.3477466Z ##[group]GITHUB_TOKEN Permissions
2026-04-19T17:27:23.3479137Z Contents: read
2026-04-19T17:27:23.3479588Z Metadata: read
2026-04-19T17:27:23.3479961Z ##[endgroup]
2026-04-19T17:27:23.3481548Z Secret source: None
2026-04-19T17:27:23.3482065Z Prepare workflow directory
2026-04-19T17:27:23.3737124Z Prepare all required actions
2026-04-19T17:27:23.3770377Z Getting action download info
2026-04-19T17:27:23.7177115Z Download action repository 'actions/checkout@8e8c483db84b4bee98b60c0593521ed34d9990e8' (SHA:8e8c483db84b4bee98b60c0593521ed34d9990e8)
2026-04-19T17:27:23.9301386Z Complete job name: local-dev
2026-04-19T17:27:23.9855675Z ##[group]Run actions/checkout@8e8c483db84b4bee98b60c0593521ed34d9990e8
2026-04-19T17:27:23.9856539Z with:
2026-04-19T17:27:23.9856866Z   repository: github/docs
2026-04-19T17:27:23.9857402Z   token: ***
2026-04-19T17:27:23.9857954Z   ssh-strict: true
2026-04-19T17:27:23.9858290Z   ssh-user: git
2026-04-19T17:27:23.9858618Z   persist-credentials: true
2026-04-19T17:27:23.9858987Z   clean: true
2026-04-19T17:27:23.9859314Z   sparse-checkout-cone-mode: true
2026-04-19T17:27:23.9859710Z   fetch-depth: 1
2026-04-19T17:27:23.9860030Z   fetch-tags: false
2026-04-19T17:27:23.9860370Z   show-progress: true
2026-04-19T17:27:23.9860709Z   lfs: false
2026-04-19T17:27:23.9861019Z   submodules: false
2026-04-19T17:27:23.9861353Z   set-safe-directory: true
2026-04-19T17:27:23.9861908Z ##[endgroup]
2026-04-19T17:27:24.0604768Z Syncing repository: github/docs
2026-04-19T17:27:24.0606192Z ##[group]Getting Git version info
2026-04-19T17:27:24.0606826Z Working directory is '/home/runner/work/docs/docs'
2026-04-19T17:27:24.0607610Z [command]/usr/bin/git version
2026-04-19T17:27:24.0624284Z git version 2.53.0
2026-04-19T17:27:24.0639056Z ##[endgroup]
2026-04-19T17:27:24.0650048Z Temporarily overriding HOME='/home/runner/work/_temp/6f4bc824-c4f8-4b40-8c8e-8990b3416868' before making global git config changes
2026-04-19T17:27:24.0651935Z Adding repository directory to the temporary git global config as a safe directory
2026-04-19T17:27:24.0653832Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/docs/docs
2026-04-19T17:27:24.0681577Z Deleting the contents of '/home/runner/work/docs/docs'
2026-04-19T17:27:24.0684786Z ##[group]Initializing the repository
2026-04-19T17:27:24.0688001Z [command]/usr/bin/git init /home/runner/work/docs/docs
2026-04-19T17:27:24.0773383Z hint: Using 'master' as the name for the initial branch. This default branch name
2026-04-19T17:27:24.0774615Z hint: will change to "main" in Git 3.0. To configure the initial branch name
2026-04-19T17:27:24.0775395Z hint: to use in all of your new repositories, which will suppress this warning,
2026-04-19T17:27:24.0775964Z hint: call:
2026-04-19T17:27:24.0776402Z hint:
2026-04-19T17:27:24.0776861Z hint: 	git config --global init.defaultBranch <name>
2026-04-19T17:27:24.0777568Z hint:
2026-04-19T17:27:24.0778416Z hint: Names commonly chosen instead of 'master' are 'main', 'trunk' and
2026-04-19T17:27:24.0779548Z hint: 'development'. The just-created branch can be renamed via this command:
2026-04-19T17:27:24.0780128Z hint:
2026-04-19T17:27:24.0780441Z hint: 	git branch -m <name>
2026-04-19T17:27:24.0780919Z hint:
2026-04-19T17:27:24.0781431Z hint: Disable this message with "git config set advice.defaultBranchName false"
2026-04-19T17:27:24.0782610Z Initialized empty Git repository in /home/runner/work/docs/docs/.git/
2026-04-19T17:27:24.0783876Z [command]/usr/bin/git remote add origin https://github.com/github/docs
2026-04-19T17:27:24.0838764Z ##[endgroup]
2026-04-19T17:27:24.0841577Z ##[group]Disabling automatic garbage collection
2026-04-19T17:27:24.0842129Z [command]/usr/bin/git config --local gc.auto 0
2026-04-19T17:27:24.0863818Z ##[endgroup]
2026-04-19T17:27:24.0864471Z ##[group]Setting up auth
2026-04-19T17:27:24.0865103Z Removing SSH command configuration
2026-04-19T17:27:24.0869454Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-04-19T17:27:24.0893762Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-04-19T17:27:24.1137276Z Removing HTTP extra header
2026-04-19T17:27:24.1142093Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-04-19T17:27:24.1167330Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-04-19T17:27:24.1341463Z Removing includeIf entries pointing to credentials config files
2026-04-19T17:27:24.1345827Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-04-19T17:27:24.1371188Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-04-19T17:27:24.1552056Z [command]/usr/bin/git config --file /home/runner/work/_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config http.https://github.com/.extraheader AUTHORIZATION: basic ***
2026-04-19T17:27:24.1581106Z [command]/usr/bin/git config --local includeIf.gitdir:/home/runner/work/docs/docs/.git.path /home/runner/work/_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:27:24.1605436Z [command]/usr/bin/git config --local includeIf.gitdir:/home/runner/work/docs/docs/.git/worktrees/*.path /home/runner/work/_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:27:24.1629989Z [command]/usr/bin/git config --local includeIf.gitdir:/github/workspace/.git.path /github/runner_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:27:24.1655068Z [command]/usr/bin/git config --local includeIf.gitdir:/github/workspace/.git/worktrees/*.path /github/runner_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:27:24.1677064Z ##[endgroup]
2026-04-19T17:27:24.1678373Z ##[group]Fetching the repository
2026-04-19T17:27:24.1684092Z [command]/usr/bin/git -c protocol.version=2 fetch --no-tags --prune --no-recurse-submodules --depth=1 origin +14824a56ec5ce9f2858178edbf01bfa3f6765485:refs/remotes/pull/43840/merge
2026-04-19T17:27:34.2858698Z From https://github.com/github/docs
2026-04-19T17:27:34.2859395Z  * [new ref]         14824a56ec5ce9f2858178edbf01bfa3f6765485 -> pull/43840/merge
2026-04-19T17:27:34.2881663Z ##[endgroup]
2026-04-19T17:27:34.2882198Z ##[group]Determining the checkout info
2026-04-19T17:27:34.2884393Z ##[endgroup]
2026-04-19T17:27:34.2888925Z [command]/usr/bin/git sparse-checkout disable
2026-04-19T17:27:34.2928333Z [command]/usr/bin/git config --local --unset-all extensions.worktreeConfig
2026-04-19T17:27:34.2950787Z ##[group]Checking out the ref
2026-04-19T17:27:34.2953978Z [command]/usr/bin/git checkout --progress --force refs/remotes/pull/43840/merge
2026-04-19T17:27:35.3346946Z Updating files:  95% (11204/11709)
2026-04-19T17:27:35.3626575Z Updating files:  96% (11241/11709)
2026-04-19T17:27:35.3718381Z Updating files:  97% (11358/11709)
2026-04-19T17:27:35.3776979Z Updating files:  98% (11475/11709)
2026-04-19T17:27:35.4039361Z Updating files:  99% (11592/11709)
2026-04-19T17:27:35.4039875Z Updating files: 100% (11709/11709)
2026-04-19T17:27:35.4040200Z Updating files: 100% (11709/11709), done.
2026-04-19T17:27:35.4132165Z Note: switching to 'refs/remotes/pull/43840/merge'.
2026-04-19T17:27:35.4132889Z 
2026-04-19T17:27:35.4133151Z You are in 'detached HEAD' state. You can look around, make experimental
2026-04-19T17:27:35.4133810Z changes and commit them, and you can discard any commits you make in this
2026-04-19T17:27:35.4134377Z state without impacting any branches by switching back to a branch.
2026-04-19T17:27:35.4134713Z 
2026-04-19T17:27:35.4134940Z If you want to create a new branch to retain commits you create, you may
2026-04-19T17:27:35.4135520Z do so (now or later) by using -c with the switch command. Example:
2026-04-19T17:27:35.4135816Z 
2026-04-19T17:27:35.4135961Z   git switch -c <new-branch-name>
2026-04-19T17:27:35.4136218Z 
2026-04-19T17:27:35.4136350Z Or undo this operation with:
2026-04-19T17:27:35.4136551Z 
2026-04-19T17:27:35.4136698Z   git switch -
2026-04-19T17:27:35.4136868Z 
2026-04-19T17:27:35.4137129Z Turn off this advice by setting config variable advice.detachedHead to false
2026-04-19T17:27:35.4137529Z 
2026-04-19T17:27:35.4138194Z HEAD is now at 14824a5 Merge cc89c15c10fc6c04ff3eb7dd0818c643bf80b4b4 into 97bc4dd23191c7f6dc53a80f00e982a4c9118dfd
2026-04-19T17:27:35.4214757Z ##[endgroup]
2026-04-19T17:27:35.4251947Z [command]/usr/bin/git log -1 --format=%H
2026-04-19T17:27:35.4272828Z 14824a56ec5ce9f2858178edbf01bfa3f6765485
2026-04-19T17:27:35.4510857Z Prepare all required actions
2026-04-19T17:27:35.4511232Z Getting action download info
2026-04-19T17:27:35.6608369Z Download action repository 'actions/cache@v4' (SHA:0057852bfaa89a56745cba8c7296529d2fc39830)
2026-04-19T17:27:36.1945150Z Download action repository 'actions/setup-node@2028fbc5c25fe9cf00d9f06a71cc4710d4507903' (SHA:2028fbc5c25fe9cf00d9f06a71cc4710d4507903)
2026-04-19T17:27:36.6549600Z ##[group]Run ./.github/actions/node-npm-setup
2026-04-19T17:27:36.6549840Z ##[endgroup]
2026-04-19T17:27:36.7607145Z ##[group]Run actions/cache@v4
2026-04-19T17:27:36.7607350Z with:
2026-04-19T17:27:36.7607507Z   path: node_modules
2026-04-19T17:27:36.7608241Z   key: Linux-node_modules-9f1e90b1ef33f381c43ce0806deebf28f87f2d560469ee6857227e34277b8586-d88af40c925a91f83840c1976a6e4b0f53ff09c6bfd29f5d75aa8db079030b40
2026-04-19T17:27:36.7608810Z   enableCrossOsArchive: false
2026-04-19T17:27:36.7609003Z   fail-on-cache-miss: false
2026-04-19T17:27:36.7609193Z   lookup-only: false
2026-04-19T17:27:36.7609414Z   save-always: false
2026-04-19T17:27:36.7609560Z env:
2026-04-19T17:27:36.7609711Z   SEGMENT_DOWNLOAD_TIMEOUT_MINS: 1
2026-04-19T17:27:36.7609906Z ##[endgroup]
2026-04-19T17:27:37.0720928Z Cache hit for: Linux-node_modules-9f1e90b1ef33f381c43ce0806deebf28f87f2d560469ee6857227e34277b8586-d88af40c925a91f83840c1976a6e4b0f53ff09c6bfd29f5d75aa8db079030b40
2026-04-19T17:27:38.2987975Z Received 37748736 of 214224001 (17.6%), 36.0 MBs/sec
2026-04-19T17:27:39.2733244Z Received 214224001 of 214224001 (100.0%), 103.3 MBs/sec
2026-04-19T17:27:39.2734466Z Cache Size: ~204 MB (214224001 B)
2026-04-19T17:27:39.2818838Z [command]/usr/bin/tar -xf /home/runner/work/_temp/29a5606b-0a11-46c7-a174-68dce15878a7/cache.tzst -P -C /home/runner/work/docs/docs --use-compress-program unzstd
2026-04-19T17:27:43.7757041Z Cache restored successfully
2026-04-19T17:27:43.7906249Z Cache restored from key: Linux-node_modules-9f1e90b1ef33f381c43ce0806deebf28f87f2d560469ee6857227e34277b8586-d88af40c925a91f83840c1976a6e4b0f53ff09c6bfd29f5d75aa8db079030b40
2026-04-19T17:27:43.8040388Z ##[group]Run actions/setup-node@2028fbc5c25fe9cf00d9f06a71cc4710d4507903
2026-04-19T17:27:43.8040827Z with:
2026-04-19T17:27:43.8040991Z   node-version-file: package.json
2026-04-19T17:27:43.8041189Z   cache: npm
2026-04-19T17:27:43.8041344Z   always-auth: false
2026-04-19T17:27:43.8041515Z   check-latest: false
2026-04-19T17:27:43.8041771Z   token: ***
2026-04-19T17:27:43.8041935Z   package-manager-cache: true
2026-04-19T17:27:43.8042120Z ##[endgroup]
2026-04-19T17:27:43.9121576Z Resolved package.json as ^24
2026-04-19T17:27:43.9173490Z Found in cache @ /opt/hostedtoolcache/node/24.14.1/x64
2026-04-19T17:27:43.9176774Z (node:2143) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-04-19T17:27:43.9177591Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-04-19T17:27:43.9179373Z ##[group]Environment details
2026-04-19T17:27:45.2827548Z node: v24.14.1
2026-04-19T17:27:45.2828102Z npm: 11.11.0
2026-04-19T17:27:45.2828335Z yarn: 1.22.22
2026-04-19T17:27:45.2828943Z ##[endgroup]
2026-04-19T17:27:45.2844173Z [command]/opt/hostedtoolcache/node/24.14.1/x64/bin/npm config get cache
2026-04-19T17:27:45.4948387Z /home/runner/.npm
2026-04-19T17:27:45.6952540Z Cache hit for: node-cache-Linux-x64-npm-a1a62a1bd013c56fed171f049b53f265b420d7934c938deedbca74eea863ab4c
2026-04-19T17:27:45.7027309Z (node:2143) [DEP0169] DeprecationWarning: `url.parse()` behavior is not standardized and prone to errors that have security implications. Use the WHATWG URL API instead. CVEs are not issued for `url.parse()` vulnerabilities.
2026-04-19T17:27:46.8984106Z Received 41943040 of 229894751 (18.2%), 40.0 MBs/sec
2026-04-19T17:27:47.8909876Z Received 229894751 of 229894751 (100.0%), 110.0 MBs/sec
2026-04-19T17:27:47.8910894Z Cache Size: ~219 MB (229894751 B)
2026-04-19T17:27:47.8934795Z [command]/usr/bin/tar -xf /home/runner/work/_temp/e1e10f68-9729-4c0c-b343-96bd577e03e2/cache.tzst -P -C /home/runner/work/docs/docs --use-compress-program unzstd
2026-04-19T17:27:48.2752144Z Cache restored successfully
2026-04-19T17:27:48.2853297Z Cache restored from key: node-cache-Linux-x64-npm-a1a62a1bd013c56fed171f049b53f265b420d7934c938deedbca74eea863ab4c
2026-04-19T17:27:48.3035638Z ##[group]Run npx next telemetry disable
2026-04-19T17:27:48.3035952Z [36;1mnpx next telemetry disable[0m
2026-04-19T17:27:48.3522681Z shell: /usr/bin/bash -e {0}
2026-04-19T17:27:48.3522909Z ##[endgroup]
2026-04-19T17:27:50.5163629Z Attention: Next.js now collects completely anonymous telemetry regarding usage.
2026-04-19T17:27:50.5164208Z This information is used to shape Next.js' roadmap and prioritize features.
2026-04-19T17:27:50.5164865Z You can learn more, including how to opt-out if you'd not like to participate in this anonymous program, by visiting the following URL:
2026-04-19T17:27:50.5165328Z https://nextjs.org/telemetry
2026-04-19T17:27:50.5165481Z 
2026-04-19T17:27:50.8298926Z Your preference has been saved to /home/runner/work/docs/docs/cache/config.json.
2026-04-19T17:27:50.8299698Z 
2026-04-19T17:27:50.8303513Z Status: Disabled
2026-04-19T17:27:50.8304070Z 
2026-04-19T17:27:50.8304545Z You have opted-out of Next.js' anonymous telemetry program.
2026-04-19T17:27:50.8305241Z No data will be collected from your machine.
2026-04-19T17:27:50.8305521Z 
2026-04-19T17:27:50.8305779Z Learn more: https://nextjs.org/telemetry
2026-04-19T17:27:50.8689928Z ##[group]Run # Start server in background
2026-04-19T17:27:50.8690218Z [36;1m# Start server in background[0m
2026-04-19T17:27:50.8690487Z [36;1mnpm start > /tmp/stdout.log 2> /tmp/stderr.log &[0m
2026-04-19T17:27:50.8690745Z [36;1mSERVER_PID=$![0m
2026-04-19T17:27:50.8690923Z [36;1m[0m
2026-04-19T17:27:50.8691119Z [36;1m# Wait for server to be ready and test homepage[0m
2026-04-19T17:27:50.8691525Z [36;1mif curl --fail --retry-connrefused --retry 10 --retry-delay 2 http://localhost:4000/; then[0m
2026-04-19T17:27:50.8691971Z [36;1m  echo "✅ Local dev server started successfully and serves homepage"[0m
2026-04-19T17:27:50.8692292Z [36;1m  kill $SERVER_PID 2>/dev/null || true[0m
2026-04-19T17:27:50.8692662Z [36;1melse[0m
2026-04-19T17:27:50.8692882Z [36;1m  echo "❌ Local dev server failed to start or serve content"[0m
2026-04-19T17:27:50.8693146Z [36;1m  echo "____STDOUT____"[0m
2026-04-19T17:27:50.8693357Z [36;1m  cat /tmp/stdout.log[0m
2026-04-19T17:27:50.8693575Z [36;1m  echo "____STDERR____"[0m
2026-04-19T17:27:50.8693768Z [36;1m  cat /tmp/stderr.log[0m
2026-04-19T17:27:50.8693973Z [36;1m  kill $SERVER_PID 2>/dev/null || true[0m
2026-04-19T17:27:50.8694182Z [36;1m  exit 1[0m
2026-04-19T17:27:50.8694338Z [36;1mfi[0m
2026-04-19T17:27:50.8712629Z shell: /usr/bin/bash -e {0}
2026-04-19T17:27:50.8712845Z ##[endgroup]
2026-04-19T17:27:50.9492807Z   % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
2026-04-19T17:27:50.9493572Z                                  Dload  Upload   Total   Spent    Left  Speed
2026-04-19T17:27:50.9493944Z 
2026-04-19T17:27:50.9494382Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:50.9494969Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:50.9495792Z curl: (7) Failed to connect to localhost port 4000 after 0 ms: Couldn't connect to server
2026-04-19T17:27:50.9496438Z Warning: Problem : connection refused. Will retry in 2 seconds. 10 retries 
2026-04-19T17:27:50.9496743Z Warning: left.
2026-04-19T17:27:52.9509651Z 
2026-04-19T17:27:52.9513075Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:52.9513681Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:52.9514397Z curl: (7) Failed to connect to localhost port 4000 after 0 ms: Couldn't connect to server
2026-04-19T17:27:52.9515213Z Warning: Problem : connection refused. Will retry in 2 seconds. 9 retries left.
2026-04-19T17:27:54.9533890Z 
2026-04-19T17:27:54.9536626Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:54.9537258Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:54.9538297Z curl: (7) Failed to connect to localhost port 4000 after 0 ms: Couldn't connect to server
2026-04-19T17:27:54.9539116Z Warning: Problem : connection refused. Will retry in 2 seconds. 8 retries left.
2026-04-19T17:27:56.9558233Z 
2026-04-19T17:27:56.9560609Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:56.9561209Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:56.9562055Z curl: (7) Failed to connect to localhost port 4000 after 0 ms: Couldn't connect to server
2026-04-19T17:27:56.9562876Z Warning: Problem : connection refused. Will retry in 2 seconds. 7 retries left.
2026-04-19T17:27:58.9579604Z 
2026-04-19T17:27:58.9581996Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:58.9582756Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:27:58.9583620Z curl: (7) Failed to connect to localhost port 4000 after 0 ms: Couldn't connect to server
2026-04-19T17:27:58.9584446Z Warning: Problem : connection refused. Will retry in 2 seconds. 6 retries left.
2026-04-19T17:28:00.9604128Z 
2026-04-19T17:28:00.9719488Z   0     0    0     0    0     0      0      0 --:--:-- --:--:-- --:--:--     0
2026-04-19T17:28:00.9720582Z 100    25  100    25    0     0   2169      0 --:--:-- --:--:-- --:--:--  2272
2026-04-19T17:28:00.9732965Z Found. Redirecting to /en✅ Local dev server started successfully and serves homepage
2026-04-19T17:28:00.9798063Z Post job cleanup.
2026-04-19T17:28:00.9869088Z Post job cleanup.
2026-04-19T17:28:01.0965675Z (node:2339) [DEP0040] DeprecationWarning: The `punycode` module is deprecated. Please use a userland alternative instead.
2026-04-19T17:28:01.0966937Z (Use `node --trace-deprecation ...` to show where the warning was created)
2026-04-19T17:28:01.0968513Z Cache hit occurred on the primary key node-cache-Linux-x64-npm-a1a62a1bd013c56fed171f049b53f265b420d7934c938deedbca74eea863ab4c, not saving cache.
2026-04-19T17:28:01.1992754Z Post job cleanup.
2026-04-19T17:28:01.3067243Z Cache hit occurred on the primary key Linux-node_modules-9f1e90b1ef33f381c43ce0806deebf28f87f2d560469ee6857227e34277b8586-d88af40c925a91f83840c1976a6e4b0f53ff09c6bfd29f5d75aa8db079030b40, not saving cache.
2026-04-19T17:28:01.3156319Z Post job cleanup.
2026-04-19T17:28:01.3827508Z [command]/usr/bin/git version
2026-04-19T17:28:01.3859987Z git version 2.53.0
2026-04-19T17:28:01.3890857Z Temporarily overriding HOME='/home/runner/work/_temp/223a92de-34a1-4b91-9456-04b6e99a091e' before making global git config changes
2026-04-19T17:28:01.3892216Z Adding repository directory to the temporary git global config as a safe directory
2026-04-19T17:28:01.3895500Z [command]/usr/bin/git config --global --add safe.directory /home/runner/work/docs/docs
2026-04-19T17:28:01.4267477Z Removing SSH command configuration
2026-04-19T17:28:01.4279837Z [command]/usr/bin/git config --local --name-only --get-regexp core\.sshCommand
2026-04-19T17:28:01.4323857Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'core\.sshCommand' && git config --local --unset-all 'core.sshCommand' || :"
2026-04-19T17:28:01.4581788Z Removing HTTP extra header
2026-04-19T17:28:01.4586803Z [command]/usr/bin/git config --local --name-only --get-regexp http\.https\:\/\/github\.com\/\.extraheader
2026-04-19T17:28:01.4640619Z [command]/usr/bin/git submodule foreach --recursive sh -c "git config --local --name-only --get-regexp 'http\.https\:\/\/github\.com\/\.extraheader' && git config --local --unset-all 'http.https://github.com/.extraheader' || :"
2026-04-19T17:28:01.4856175Z Removing includeIf entries pointing to credentials config files
2026-04-19T17:28:01.4862974Z [command]/usr/bin/git config --local --name-only --get-regexp ^includeIf\.gitdir:
2026-04-19T17:28:01.4881161Z includeif.gitdir:/home/runner/work/docs/docs/.git.path
2026-04-19T17:28:01.4882017Z includeif.gitdir:/home/runner/work/docs/docs/.git/worktrees/*.path
2026-04-19T17:28:01.4884570Z includeif.gitdir:/github/workspace/.git.path
2026-04-19T17:28:01.4885530Z includeif.gitdir:/github/workspace/.git/worktrees/*.path
2026-04-19T17:28:01.4889627Z [command]/usr/bin/git config --local --get-all includeif.gitdir:/home/runner/work/docs/docs/.git.path
2026-04-19T17:28:01.4907073Z /home/runner/work/_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:28:01.4915437Z [command]/usr/bin/git config --local --unset includeif.gitdir:/home/runner/work/docs/docs/.git.path /home/runner/work/_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:28:01.4970876Z [command]/usr/bin/git config --local --get-all includeif.gitdir:/home/runner/work/docs/docs/.git/worktrees/*.path
2026-04-19T17:28:01.4989252Z /home/runner/work/_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:28:01.4996148Z [command]/usr/bin/git config --local --unset includeif.gitdir:/home/runner/work/docs/docs/.git/worktrees/*.path /home/runner/work/_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:28:01.5150866Z [command]/usr/bin/git config --local --get-all includeif.gitdir:/github/workspace/.git.path
2026-04-19T17:28:01.5169280Z /github/runner_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:28:01.5176986Z [command]/usr/bin/git config --local --unset includeif.gitdir:/github/workspace/.git.path /github/runner_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:28:01.5248940Z [command]/usr/bin/git config --local --get-all includeif.gitdir:/github/workspace/.git/worktrees/*.path
2026-04-19T17:28:01.5270249Z /github/runner_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:28:01.5277623Z [command]/usr/bin/git config --local --unset includeif.gitdir:/github/workspace/.git/worktrees/*.path /github/runner_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config
2026-04-19T17:28:01.5453768Z [command]/usr/bin/git submodule foreach --recursive git config --local --show-origin --name-only --get-regexp remote.origin.url
2026-04-19T17:28:01.5660951Z Removing credentials config '/home/runner/work/_temp/git-credentials-7dc9063c-e301-4831-818e-59bf9f978555.config'
2026-04-19T17:28:01.5785224Z Cleaning up orphan processes
2026-04-19T17:28:01.6051174Z Terminate orphan process: pid (2226) (MainThread)
2026-04-19T17:28:01.6077542Z Terminate orphan process: pid (2233) (MainThread)
2026-04-19T17:28:01.6176603Z Terminate orphan process: pid (2303) (sh)
2026-04-19T17:28:01.6205146Z Terminate orphan process: pid (2304) (MainThread)
2026-04-19T17:28:01.6234095Z Terminate orphan process: pid (2316) (MainThread)
2026-04-19T17:28:01.6254629Z ##[warning]Node.js 20 actions are deprecated. The following actions are running on Node.js 20 and may not work as expected: actions/cache@v4. Actions will be forced to run with Node.js 24 by default starting June 2nd, 2026. Node.js 20 will be removed from the runner on September 16th, 2026. Please check if updated versions of these actions are available that support Node.js 24. To opt into Node.js 24 now, set the FORCE_JAVASCRIPT_ACTIONS_TO_NODE24=true environment variable on the runner or in your workflow file. Once Node.js 24 becomes the default, you can temporarily opt out by setting ACTIONS_ALLOW_USE_UNSECURE_NODE_VERSION=true. For more information see: https://github.blog/changelog/2025-09-19-deprecation-of-node-20-on-github-actions-runners/

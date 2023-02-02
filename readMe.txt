COMMANDS IN TERMINAL TO:
run the tests: "npx playwright test"

show the report (& see in browser): "npx playwright show-report"

run multiple workers in parallel (etc 3 browsers): 
"npx playwright test --workers 3"

run a specific file: 
"npx playwright test specificFileLocationOrName.js" vs "npx playwright test ./tests/example.spec.js"

run multiple specified files: 
"npx playwright test 1-specificFileLocationOrName.js 2-specificFileLocationOrName.js"

run a file with just the name: 
"npx playwright test example"

run a test by test title: "npx playwright test -g 'has title' "

execute one test on a single browser: 
"npx playwright test --project=chromium"

run tests with the physical head on the screen: 
"npx playwright test --headed"

debuging option & open playwright inspector window with browser
(see watch and trouble shoot [resume, pause, step over]): 
"npx playwright test --project=chromium --debug"

debug a specific test file (same as above plus debug): 
"npx playwright test fileName.js --debug"

debug starting with a specific file & line (same as above plus:line):
"npx playwright test ./tests/example.spec.js:21 --project=chromium --debug"


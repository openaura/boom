exec = require('child_process').exec

task "test", "Run tests with mocha", ->
  run "mocha --compilers coffee:coffee-script -R nyan -u tdd"

run = (command, cb = ->) ->
  exec command, (err, stdout, stderr) ->
    if err
      console.log err
    process.stdout.write stdout
    process.stderr.write stderr                                       
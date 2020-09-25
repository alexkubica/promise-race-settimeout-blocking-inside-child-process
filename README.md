# How to run
Run `node index.js`.  

# Expected
`Promise.race` should immediately resolve and print "resolved".

# Actual
Output hangs until `setTimeout`'s callback is called.
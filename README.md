# apiblueprint
api blueprint  mock  doc  test 
## Install Require Software
npm install -g api-mock
npm install -g drakov
npm install -g aglio

aglio -i hello.md -o hello.html
api-mock ./hello.md --port 3000
drakov -f ./hello.md -p 3000
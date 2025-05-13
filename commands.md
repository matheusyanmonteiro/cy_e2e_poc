# Cypress for beginners 

## fist part 

this part i will show how the commands lines for create a new project cypress for testing E2E application 

1. `node -v` for verify the node version in your computer. 
2. `npm init -y` for initialize the node project.
3. you have to config the `package.json` for facilitated the installation for the others persons, "type:module" and "engines:{node: version}".
4. install the cypress in the version 13.7.2 
5. in the `package.json` do you have to create two scripts for initialize cypress, cypress:web (Browser) and cypress:headless (Terminal way).
6. install the package ntl for list the scripts on the package.json.
7. add configs in the cypress config: 1.chromeWebSecurity false 2. baseURL (your url) 3. testIsolation false for the cypress not clean the testings stage.
8. do you need to redirect the cypress for you URL in my case i will use a local site on "http://localhost:3000" 
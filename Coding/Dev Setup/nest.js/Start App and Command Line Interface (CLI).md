- install
	- `npm i -g @nestjs/cli`
- create app
	- `nest new project-name`
- run app
	-  set port to 8000 or something in the `main.ts` file as react app also uses 3000 by default
		- change `await app.listen(3000);` to `await app.listen(8000);`
	- `npm run start` in directory with `package.json`
		- in scripts of `package.json` you can see `start:dev` does `nest start` which starts the nest application
- run app in dev mode
	- `npm run start:dev`
		- in scripts of `package.json` you can see `start:dev` does `nest start --watch` which is just going to restart automatically as you make changes to code. Makes development quicker as you can see your changes quicker
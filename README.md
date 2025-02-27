# PROJECT ARCHIVED
I've never used a template repo before and after trying to create PRs just to have it default back to my template repo, I realized there was a reason for that and that I'd made a mistake by not using the template repo _as a template_. Lesson learned!


# Branch Dictator 👑
Oh, you thought this was a democracy? Guess again... in this kingdom, branches are micromanaged and admins have less power ¯\\\_(ツ)\_/¯

## Development
### Environment Variables
Project environment variables should first be defined in `.env.sample` without real values for their data (that file is tracked by git). After cloning, make sure to duplicate `.env.sample` as `.env` and then fill in all required variables.

### Dependencies
This project is reliant on the installation of the following dependencies:
- [Node (LTS)](https://nodejs.org/en/download/) (v12.0+)

After downlodaing the dependencies above, install all NPM dependencies by running `npm i`.

### Starting the App
The best way to start the app and work on it is by using `npm run dev`, which will start the app and then restart the app whenever a TypeScript file changes. After modifying a non-Typescript file, restart the app by typing `rs` into the same terminal you ran `npm run dev` from and then hitting return.

After the app starts, it will be accessible on `localhost:3000` (unless the port was modified via `.env`).

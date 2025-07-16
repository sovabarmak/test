1. Copy this folder to the root of local site
2. Add to `.gitignore` file in root of site this line: `!.github`
3. Update branches names in each yml file to match the corresponding github branch. For example: `main.yml` might have `main` or `master`; `stage.yml` might have `stage` or `staging`; `dev.yml` might have `dev` or `develop`. Choose the right one for the environment.
4. Replace in each file value for `WPE_ENV` according to wpengine environment slug   

# Introduction
  1. In the `src` folder, you'll find `custom-settings`. Just replace them with your values.  
  2. To check Git user settings (like "Alice"), run: 'code ~/.gitconfig'.
  3. Official Parcel website: https://parceljs.org/ 

# Parcel

  ## 1. Quick start
    1. Copy or clone this starter project.
    2. Delete the `.git` folder to unlink the remote repository.
    3. Install dependencies: 'npm install'.
    4. Initialisation git for working with remote repo: 'git init'.
    5. (Optional) Update Parcel, Prettier and Rimraf to the latest versions: 'npm run update'.
    6. Clear old build and cache: 'npm run clean'.
       If npm run clean does not remove everything (sometimes Parcel gives errors about missing cache),  delete manually:
         'The folders dist/ and .parcel-cache/'.
         '(Optional) node_modules/'.
    7. Start development server: 'npm start'.

  ## 2. Package.json commands
    1. 'npm run start' = Start dev server and open browser.
    2. 'npm run build' = Build project to dist/ folder.
    3. 'npm run clean' = Delete dist/ and .parcel-cache/ folders.
    4. 'npm run update' = Update Parcel to latest version.
    5. 'npm run format' = Format code with Prettier.

  ## 3. Extra Commands (Not in package.json)
    1. 'npx parcel --version' = parcel version.
    2. 'npm remove parcel-bundler' = remove parcel.

# Notes
  1. `rimraf` is used instead of `rm -rf` for cross-platform compatibility (especially on Windows).
  2. This setup uses `prettier` for consistent code formatting.
  3. You can customize the "format" script to include other file types if needed.

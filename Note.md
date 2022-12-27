# vercel deploy

> Error: The file "/vercel/path0/apps/aptos/.next/routes-manifest.json" couldn't be found. This is normally caused by a misconfiguration in your project.

 1. If present, be sure your `build` script in "package.json" calls `next build`.  
 2. Navigate to your project's settings in the Vercel dashboard, and verify that the "Build Command" is not overridden, or that it calls `next build`.  
 pancake-frontend-aptos/settings > Build Commmand 改取消 Override button 選取  
 3. Navigate to your project's settings in the Vercel dashboard, and verify that the "Output Directory" is not overridden. Note that `next export` does **not** require you change this setting, even if you customize the `next export` output directory.  
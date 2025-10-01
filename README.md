# Description
This `user.js` file fixes most privacy and performance issues in Firefox without breaking websites.  

It comes **without any support**, as I assume you know what you are doing if you choose to use it. Updates will be released whenever a new version of Firefox is available.  

## Key Features
- Improved network performance  
- Resistance to fingerprinting  
- Disabled telemetry  
- Disabled disk cache and optimized memory cache  
- Disabled website prefetching  
- Disabled automatic update checks for extensions  
- Disabled AI features  

## Installation / Updating
1. Close Firefox.  
2. Create a backup of your profile in case you want to revert to your old settings.  
3. Download and copy the `user.js` file to your Firefox profile folder. Overwrite it if you are updating.  
4. (Optional) Apply your own settings by creating a `user_overwrites.js` file.  
5. Restart Firefox. The new settings will be applied automatically.  

## Changing Preferences
You can customize any preference using a `user_overwrites.js` file.  

1. Create a file named `user_overwrites.js` in your Firefox profile folder.  
2. Add your custom preferences to `user_overwrites.js`.  
3. Open a shell or command line in your Firefox profile folder, then append your preferences to the `user.js` file.

On Linux shell:
```
cat user_overwrites.js >> user.js
```
On Windows command line (cmd):
```
type user_overwrites.js >> user.js
```
4. Restart Firefox.  
5. Repeat steps 3–4 each time you update the main `user.js`.  

## Technical Note
Some settings in this `user.js` are not strictly necessary, as they are already set by default or automatically adjusted through related preferences. However, including them simplifies maintenance and ensures consistency across updates.

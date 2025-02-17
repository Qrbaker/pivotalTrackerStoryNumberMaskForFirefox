# pivotalTrackerStoryNumberMaskForFirefox

This firefox plugin helps to display last 4 digits of story number in story name field in collapse field. This provides a display mask to Users and do not dirty existing data's. By default, Pivotal Tracker do not display story number in story name field in collapse mode.

Example:

 Default:
   - Story name in collapse mode: `This is sample story`

 With this plugin:
   - Story name in collapse mode: `1234 - This is sample story`  
       - 1234 - last 4 digits of story number

-----
# How to install: Firefox
- Click the following link:
  - https://addons.mozilla.org/en-US/firefox/addon/pivotal-story-mask/
- Click `Add to Firefox`
- Approve the extension when prompted

You will now see the story short code prepended to each story on your projects.

-----
# How to install: Chrome

 - Open below web store extension link in your chrome browser
   - https://chrome.google.com/webstore/detail/pivotal-tracker-story-num/ienephhenhijhhfadgobajpepoipobfc
 - Click `Add to Chrome` button
 - Open pivotal tracker and navigate to your project
 - Notice the story number display in story name field

-----

# Unit test 
  - Jest framework
      - `./node_modules/.bin/jest`    

-----

# References:
  - https://medium.com/@karthidec/how-to-display-the-story-number-in-story-name-field-in-collapse-mode-for-pivotal-tracker-projects-774c70b6a950
  - https://www.pivotaltracker.com/integrations/story-ID-display

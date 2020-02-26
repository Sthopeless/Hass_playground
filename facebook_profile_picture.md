# How to use Facebook Profile Picture as `entity_picture:`
  
1. Open facebook profile page
2. Click on the page with right button of the mouse and choose `View Page Source`
3. Find `profile_id:` and copy the value
4. Add this url as your `entity_picture` in Home Assistant: https://graph.facebook.com/<FacebookID>/picture?type=normal
5. Replace <FacebookID> with step3 value
6. Reboot Home Assistant

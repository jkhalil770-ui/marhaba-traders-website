================================================================
  MARHABA TRADERS WEBSITE — INFINITYFREE DEPLOYMENT GUIDE
================================================================

WHAT TO UPLOAD
--------------
Upload the entire contents of this "deploy" folder.
Do NOT upload the folder itself — upload what's INSIDE it.

FILES & FOLDERS TO UPLOAD:
  index.html                  <-- Main website (homepage)
  investor-form.html          <-- Investor signup form
  startup-form.html           <-- Startup application form
  premium-startup-form.html   <-- Premium startup form
  privacy-policy.html         <-- Privacy policy page
  terms-and-conditions.html   <-- Terms & conditions page
  assets/                     <-- Avatar images
  cs-hi/                      <-- Founder/testimonial photos
  uploads/                    <-- Company logo images

WHERE TO UPLOAD
---------------
1. Login to InfinityFree at: https://app.infinityfree.com
2. Go to your hosting account → Control Panel
3. Click "Online File Manager"
4. Open the "htdocs" folder (this is your website root)
5. Delete any existing files in htdocs (if starting fresh)
6. Click "Upload" and select all files from this deploy folder
   OR use "Upload Zip" — zip this folder's contents first

FASTEST METHOD (Recommended for beginners):
  a) Select all files in this deploy/ folder
  b) Right-click → Send to → Compressed (zip) folder
  c) Name it: marhaba-site.zip
  d) In InfinityFree File Manager → htdocs → Upload Zip
  e) After upload, click "Extract" on the zip file
  f) Delete the zip file after extracting

HOW TO OPEN YOUR WEBSITE
-------------------------
After uploading, your site will be live at:
  http://yourdomain.infinityfree.net/
  (replace "yourdomain" with your InfinityFree subdomain)

The homepage is index.html — it loads automatically.
All other pages link to each other correctly.

COMMON BEGINNER MISTAKES
-------------------------
1. WRONG: Uploading the deploy/ folder itself instead of its contents
   RIGHT:  Open deploy/ folder, select everything inside, upload that

2. WRONG: Uploading to the wrong folder (not htdocs)
   RIGHT:  Always upload to the "htdocs" folder only

3. WRONG: Expecting site to work immediately
   RIGHT:  DNS can take up to 24 hours. Usually ready in 5-15 minutes.

4. WRONG: Renaming index.html to something else
   RIGHT:  index.html MUST stay named index.html — it's the homepage

5. WRONG: Skipping image folders
   RIGHT:  Upload assets/, cs-hi/, and uploads/ folders too — not just HTML

6. WRONG: Uploading files one by one slowly
   RIGHT:  Use the ZIP method described above for speed

MISSING IMAGE FOLDERS (ACTION REQUIRED)
-----------------------------------------
The following folders were NOT found in your project:
  - casestudy/     (portfolio screenshot images)
  - testmonils new/ (testimonial gallery images)

These are referenced in your website's JavaScript. Without them,
those gallery sections will appear empty on the live site.

If you have these image folders somewhere on your computer,
copy them into this deploy/ folder before uploading.

================================================================
  Support: hello@marhabatraders.online | WhatsApp: 03719222195
================================================================

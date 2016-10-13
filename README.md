# unist-theme-edx
Theme for the open edx instance of UNIST

# Installation:

Add a folder to your /themes and edit the file: 

   /edx/app/edxapp/lms.env.json 

adding:

  "COMPREHENSIVE_THEME_DIR": "/full/path/to/theme",

Then restart site. If you edit theme files, run update like this:

   paver update_assets lms

Both of these steps should be done for studio/cms. Only replace lms with cms.

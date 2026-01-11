# danielroberts_frontend
# Social Care Wales interview task

## Approach:
- I believe in being honest, transparent and accountable
- I set myself aside 6 hours to complete this task and ran over by about 30 minutes
- To keep it simple to review I have completed the task using a index.html and unminified vanilla CSS file
- 
- I wanted to set all common values as CSS custom properties but could not access the Figma variable name values
- Where possible I have used a fontset for the icons to allow for flexibility when styling

## Things to note:
- I do not have an Adobe CC account so could not get Gibson to render as the main typeface
- I had issues exporting the Social Care Wales icon that is used for the main content background detail which is why it is rendering differently to the design
- When initially reviewing the Figma file I thought all property values were available but after getting started I could not find the values used for each variable name. This means some of my spacing, sizing and border-radius may not be 100% correct
- I do not have access to a testing platform like browserstack so was only able to test on MacOS

## Improvements
- If full access to Figma was available I would create an accurate styleguide based on the variables setup by the design team
- Change the form field group setup to allow the focus state to change the label colour shown in the design prototype
- Collapse the navigation under screen widths of 992px and provide users with a mobile menu trigger button

## Next steps if making production ready
- Full browser and device testing
- Break CSS sections into their own files and use an NPM package to compile and minify to make it easier for other devs to work on the files

# information-foraging

Changes 
- Curriculum Overview Navigation added - Jonas
- PDF Curriculum document info was reformatted into pages under above nav tab - Jonas
- Formatted different categories from the orginal pdf with bolded headers - Jonas
- Switch link for spanish aka enrichment program in Intellectual Dev - Jonas
- Removed extra images from curriculum overview pages, put them on bear cub and fixed Bear Cub Photos label on page bear_cubs_photos.html- Jonas
- Added Bear Tracks link to Classrooms page - Jonas
- Change link colors to make links visible on Classrooms page. - Jonas
- Added Curriculum Flexibility page - Jonas
- Added Home & School Communication page - Jonas
- Change H1-4 to be bold to medium to increase hierarchy in common.css - Jonas
- CHANGE LINKS TO CLASSES TO BE RED - Jonas
- EDIT LANGUAGE LINK IN INTELLECTUAL DEV - Jonas
- Bear Tracks on the sidebar takes you to Bear Cubs - Jonas
- Side navbar on curriculum overview pages is redundant - remove - Jonas
- Sticky navbar added - Sylvia
- Hero images removed on landing pages for now (just commented out- some are just placeholder divs called "image container" and some are actual image tags) - Sylvia

Classrooms Changes:
- Repetitive sidebar taken out
- images moved to right side of each classroom
- Teddy Bears (AM), class times specified in parenthesis, clicking on it will also take you to that specific classes page
- Added links to classroom schedules - Jonas
- "Our classes" paragraph was a general classrooms overview that was in Teddy Bears. I moved that to the top of Classrooms page. 
- Teddy Bears changes I started: teachers will be displayed in right sidebar rather than the old sidebar
- images on all classrooms images will be moved to the Photos page for that specific classroom
- Class Schedule moved up as I think it's more important and parents would want to see that

9.23 | 3:45p (Luke)
- Removing past parent reviews from panda bear classroom page
- Recreated the reviews slideshow in the apply tab
- On homepage added link to classroom overview with icon to help it stand out
- Minor adjustments to teddy bear page: a more details-based paragraph moved down the page, font sizes adjusted on certain elements, teachers aside css adjustments- top: 100px added so teacher header is visible, css for the whole aside to be scrollable added in teddy_bears.css but commented it out since it isn't working exactly as intended
- Goal of above minor changes: make Teddy Bear page the "model" page that once we all agree is designed well we can replicate on all other classroom pages
- Announcements column on homepage made scrollable with a max height

9.25 | 12:43am (Jalen)
- Created new 'hours of operation' page under 'about'
- Added as sub-menu item in header modular component
- Wrote CSS for th and table displaying hours info
- Added hours of operation to side navbar on about, parent handbook, and staff pages
- Created new div tag and added ID to it for Spanish section on enrichments program page
- Attempted to link to aforementioned div-id section from the intellectual development page where it says "language", but instead simply linked to enrichment programs page (fix later)

9.25 | 11:10am (Luke)
- Removed slideshow parent reviews from additional pages
- Added footer back to homepage
- Removed hours of operation- could be confusing to those looking for class schedules and force bad paths
- Adjusted sidebar on About page
- Removed sidebar from tuition and parent handbook pages
- Tuition moved back under About instead of parent resources

Livia
- Added Apply for the Nursery School back to the footer
- Fixed footer entirely changed sizing and spacing and made it look cleaner
- Changed dropdown to Home and School Communication instead of home-school communication
- Fixed styling of about page so picture is in line and not messing with text

9.29 | 8:06am (Jalen)
- Added more info from parent handbook into parent-staff communication section in communication.html or "orientation, assessments, and communication" page
- Changed menu name from "orientation, assessments, and communication" to "orientation, communication, and assessments" to match the order of sections on the page
- Updated page title (within <head> tag) and header (displayed on website) in communication.html
- Made it easier to find science curriculum
- Started to split up "Orientation, Communication, and Assessments" into 3 separate pages
- Renamed combined page to "communication"
- Added direct link to enrichment programs on Teddy Bears page
- Added "(Art, Music, Spanish, Science)" to hyperlink text instead of only having the hyperlink say "Enrichment Programs"
- Reformatted "Enrichment Programs (Art, Music, Spanish, Science)" header (h3 + hyperlink) by adding div tag around it because there was no whitespace between "Enrichment Programs (Art, Music, Spanish, Science)" and "Additional Information"
- Created/added new "enrichment_programs" class to div tag
- Added CSS to properly format h3 text in the enrichment_programs class (set margin-bottom attribute to 1em)

9.29 | 2:02pm (Jalen)
- Created orientation page
- Added orientation info onto that page
- Created assessments page
- Added assessments info onto that page
- Added them to menu under parent resources
- Renamed existing combined submenu item to "Communication"

9.29 | 3:11pm (Jalen)
- Added link to enrichments on Panda Bears page
- Moved enrichment_programs class CSS from teddy_bears.css to common.css to allow the Panda Bears and other classroom pages to access it
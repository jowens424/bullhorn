# Bullhorn Web Page

Thank you for the opportunity to work on this project!

I wanted to build the Web page on WordPress, so my first intention was to use my digital ocean WordPress server and domain (http://comedycrow.com) to accomplish this task.

Once the WordPress page was active, I set out on choosing a theme and considering what CSS framework I wanted to use to allow for maximum customization.

# WP Bootstrap Starter

I elected to use WP Bootstrap Starter as my theme. This theme appeared as the simplest way to allow for Bootstrap customization and a clean design on a WordPress page.

In order to avoid losing any customization due to a theme update, I decided to create a child theme using the plugin Child Theme Configurator. Once activated, I began building out the template.

I also installed the plugin Simple Custom CSS to ensure easy styling.

# Image Overlay

Using the bootstrap component "Card --> Image overlay" I was able to build the initial image-based segment of the Web page I refered to as "Changing the World." 

CSS styles using the selector .card-img-overlay were primarily to ensure the text appeared centered within the image like in the template. 

# Text Left Container

Using the bootstrap component "Card --> Groups" I was able to build a working version of the second image and text container of the Web page. 

After styles to remove visible lines proved difficult, I used the Wordpress container function to create a cleaner looking row.

CSS styles using the selector .wp-bootstrap-blocks-row.row ensured appropriate sizing and spacing.

# Center Card 3 Bulls

Using the bootstrap component "Card --> Groups" I was able to build rough version of the bullhorn logo "One Team, One Truth, One Platform" container of the Web page.

CSS styles using the selector .wp-bootstrap-blocks-row.row ensured appropriate sizing and spacing. 

Using the selector .card-group > .card I was able to change the background color to midnight blue.

Selector .card-group img border-radius allowed for image editing to better reflect the image on the template

**final update** added "text-align: center" to reflect template text.

# Navigation Bar

Using bootstrap component Navs, I was able to create a flex-box starting with the Ownership item. I added a .nav-list:hover selector to simulate the underlined text.

.nav-bar: justify content to center the items and padding to create width close to the template's desired width.

# Bottom Container

I experimented with including the Navigation bar, both top and bottom, inside of the lower container. This created styling and resposiveness issues, so I elected to separate the containers.

I also experimented with using both the bootstrap components "Jumbotron" and "Carousel" before having more success with "Card --> Groups". Due to their being text on the right-hand side, this seemed appropriate.

# Bottom Navigation

Using bootstrap component Navs, I was able to create a flex-box and used font awesome icons to create the filled in bubble. CSS selector .bottom-nav justify content allowed for centering.

**final update** added font awesome circle icons




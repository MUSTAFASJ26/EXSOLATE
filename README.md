# EXSOLATE


The website was designed with multiple sections, each serving a unique purpose. The homepage featured a sleek background video that immediately set the tone for a luxury automotive experience, leading users to different sections such as Community News, Events, Resources, and Directories. The Directory section allowed users to browse through trusted businesses offering car customisation, spare parts, and detailing services, while the Community News section kept them updated on the latest in high-performance cars and industry trends. We also created an Events section where users could explore upcoming car expos, test drive events, and networking opportunities with fellow enthusiasts. Additionally, the Resources page provided expert insights into car tuning, high-performance modifications, and brand specific upgrades.


One of the most interesting challenges we tackled was implementing a dark and light mode switch entirely in CSS, without using JavaScript. Instead of toggling classes dynamically through scripts, we opted for a file switching approach where separate CSS files were created for dark and light themes. The default pages, such as `contact.html`, were linked to `style.css` for the dark theme, while duplicate versions like `contactwhite.html` used `stylewhite.css` for the light theme. We allowed users to switch between modes simply by clicking a button that redirected them to the corresponding version of the page, such as `Light Mode`, and vice versa for switching back to dark mode. This provided an intuitive user experience without the need for JavaScript.

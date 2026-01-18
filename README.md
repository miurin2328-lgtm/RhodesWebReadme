# Justifications for implementation decisions

### Navigation structure
![image of sticky header](<../assets/images/navigation structure.png>)
My micro-website has a total of 4 pages:
- Home page
    - This is the landing page, where users can navigate most information from. The hero-section creates impact, encouraging users to scroll through the pages.
- Events page
    - Users can navigate to this page either by clicking on the above 'Events' button visible in the sticky navigations, or the activities section after the users have scrolled down the home page.
- Transport page
    - Users can navigate to this page either by clicking on the above 'Transport' button visible in the sticky navigations, or the transport section after the users have scrolled down the home page.
- Sub-event page
    - This page is visible when the users have clicked on the specific event (Korean Calligraphy) visible in the events page.

I have kept the page numbers minimal, as I believe crucial informations for users to understand Rhodes Foreshore are: General information, What happens at Rhodes Foreshore, and How to get there.

### Typography
The three fonts I have used throughout my websites are:
- Tangerine
    - Script 
    - Used for the website title 'Rhodes Foreshore' in the sticky header
- Schoobell
    - Handwritten
    - Used as the headers in each section
- Nunito 
    - Sans Serif
    - Used for buttons or paragraphg texts that are not the heading

I have used these three fonts with varied font styles, as a way of portraying the diversity of the location. Using varied fonts—script, handwritten, and sans serif creates visual hierarchy and enhances readability across the site.

### Colours
Below are all the colours I have used throughout my website:

![image of all colours used in the website](../assets/images/colour.png)

I have used large amounts of blue and green, to emphasise how Rhodes Foreshore focuses on living with the environment, with many the trees and river accompaying the location. To create depth within the website to avoid a bland style, I have incorporated a darker shade of the green. For contrast within the website, I have added a hint of orange and pink for the purpose of showing interactive elements and adding diversity, respectively.

My aim for using these combination of colours were to present how flourished the location was with natural elements, while hinting the users of the diversity. By using playful colours such as the orange and pink, users are encouraged to become curious of what the website and location has to offer. 

### Layout & composition
![Image showing the margins of the webpage](../assets/images/margin.png)
Throughout my website, I have made great focus on keeping similar margin spaces to either left, and right, sides of the page. By focusing on maintaining a coherent visual balance using white spaces, I am able to create breathing space for users to avoid users feeling crammed by information. By doing this, I was able to maintain consistency through the pages.

### Interactivity - animation & motion 
The main reasons why I used animations or motions within my websites are to show interactivity and response to user interactions, and to portray the website to look lively and playful like Rhodes Foreshore. By making use of the animations and transition features in html and css code, I am able to make user interactions smoother. Below are examples of where, and why, I have used animations or transitions:


**Landing page**
![Image of the landing page, annotated with the interactivity of each image with 'Enlarge' and 'Pulse'](../assets/images/animations.png)
Here, I have used both transition and animation on the images. Some images pulse with no user interactions, making the page look alive. The other images respond to users hover, where the images become larger for users to view the images closer. By doing this, users are able to wonder the page with their cursor, encouraging curiosity. This results in users wanting to scroll further down to the page, allowing them to uncover what the location has to offer.

**Buttons**
![Image of the navigations buttons](../assets/images/enlarge.png)
Here is a screenshot of what happens to a button when a user hovers over them. As shown on the right button, the texts become larger and bolder, changing its colour to a darker shade. This visually tells the users that they are hovering over this button, and that they are able to interact with it, in this case, press the text. By visualising a response to user interactions, their experiences with the website becomes smooth and easy, with minimal confusions or questions.

**Clickable**
![Image of the Event cards on the Events page](../assets/images/clickable.png)
As shown above in the buttons explanations, users are informed of interactivity through visual cues. When users search around the website with their cursor, contents enlarge, or become bolder, showing that contents are clickable. Here is another example. This is visible in the events page, where event images and names are lined vertically. Here, I have hovered ovver the 'Baby Rhymetime' content, showing the box to have become larger then the other boxes, with a slightly different glow strength around the rims of the box. These sublte changes create a significant difference in usability, allowing for a smoother interactivity.

### Consistency in interactions – making buttons, links, and forms behave predictably.
Through all pages of the website, I have ensured that similar working interactive elements have a familar design style to it. Below is an example:
![alt text](../assets/images/predictability.png)
Here are three different buttons in different sections of the page, serving a similar purpose - to navigate the user to another section of the website. Having similar purposed, I have made the buttons look almost identical to one-another. When a user is navigates somewhere after clicking this button, they are able to predict that clicking on an almost-identical button will do the same. In other words, users are able to familiarise themselves with how certain elements of the website behaves.

# Usability testing
To reveal any pain-points or areas of improvement in my website prototype, I have performed two Think-aloud usability methods on one user, at two different timeline. One was performed earlier in the iteration stages, when the website was a draft. The final testing was performed later in the iterations, before all features were finalised.

## Below is the transcript from the first testing:

| Verbal | Action |
| ------ | ------ |
| Ohh ok so we got a cool landing page, the header is sort of in the way tho.. | Looks closely at landing page, moves curser around |
| Wow this photo is sort of big... This button layout is nice tho the dot between is nice, nice colour too.. I'm just gonna skip clicking on these for now | Scrolls down |
| Ok so we got the activities section?? I'm not sure if this is the final title for this part but I think you should change it haha .... And this button is meant to go to another page i'm assuming, which it still doesn't. | Scrolls around activities page, attemps to press buttons which are currently inactive |
| Ummm and then we have the transport section... Quite clean and simple, the buttons are super clear and easy to understand. | Scrolls to transport section, doesn't click on button |
| Ok I'm just gonna umm.. scroll up again. yea here (navigations button), I wanna know what happens if you press on it | scrolls back up to navigations button |
| Ok so it kinda warpped me back down here.. I think here if you make it like... smoother it'll be nice.. | presses 'Things to do' |
| I think thats it..?? Maybe one thing is like.. the buttons here (points at the top right buttons) like is it necessary?? I dont know I just cant tell if its necessary or not |  |

After conducting my first user testing, I was able to understand the following:
- Header on the landing page is too large and distracting
- User scrolls around the landing page for 2-4 seconds
- Navigations to sections of the page should be smoother
- Sticky button on the top right is unnecessary

To improve the website, I have changed the following:

### Making the sticky header less distracting
The original sticky header takes up a lot of space, with a vision of using many colours for the blocks. However, distracts users. To make the landing page and the overall website easy on the eye for users, I have sized down the height of the sticky navigations, as well as changing the entire designs of the sticky header. Further informations are written under **Comparisons between wireframes and prototype**.

### Creating impact on the landing page
The landing page plays a crucial role in a user’s decision to continue exploring the website. During the user testing, I had found out that the longest page the users had looked at was the landing page. With this insight, I have decided to create a more impactful landing page that creates a stronger impression for the website. 

To do this, I have made use of the animations and transitions feature on html coding. Below is the code that I have used for creating the hovering interactions and pulse animations from the images on the landing page. By adjusting the way the image is displayed, the website’s presentation is significantly altered, resulting in a more playful and engaging user experience.

```
.hover-zoom {
  transition: transform 0.6s ease;
}
.hover-zoom:hover {
  transform: scale(1.4);
  z-index: 10;
}

@keyframes subtlePulse {
  0%, 100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.05);
  }
}

.pulse {
  animation: subtlePulse 3.5s ease-in-out infinite;
}
```

### Smooth scroll
When the user clicked on a navigation button, it had transported them to a new page. However, the user seemd puzzled as they were unsure of which part of the website they were navigated to. 

To avoid confusion, I have implemented a smooth scroll-behaviour to all pages of the html to ensure that all navigations of the users are smooth, allowing users to visually understand where they are navigated to:

```
 html, body {
  overflow-x: hidden; /* make sure all overflow is hidden*/
  scroll-behavior: smooth;
}
```

## Below is the transcript from the second testing:

| Verbal | Action |
| ------ | ------ |
| Ok so the first thing I notice is the header... its like... smaller?? thinner?? takes up less space.. It helps me breath if that makes sense | Observes landing page |
| Ooohhh and the photos... it moves... like this one.. and when i hover over.. oh... oh.. oh ok so this one moves but this one doesnt.. and this one.. ok i got it some of them get bigger but others dont.. I don't really know why some moves and others dont but i think it works | moves curser around |
| ok im gonna scroll.. ok so the image size is the same... and ok the buttons here (navigations) they reduced in number?? I think there were more but now theres only three... i think thats good, very concise | Scrolls to navigations section |
| I think i might click on them this time... ok one thing.. I think it'll be nice to like have the... when you hover over, the buttons could change colours or get bigger or get bolder, just so i know im hovering over, or so that i know i can like click on it?? like i know to click.. because last time i clicked it and i knew from then |  |
| Oh nice its very smooth, i feel very smooth like not rigid haha... | clicks on 'Things to do' |
| Umm i think i can click on this button now?? can i?? [yes] ok i'm going to click on the events button | clicks 'view event' |
| Ok so here again, I would prefer to have like the... change in colour?? on the button so i think if you have time... that'll be nice to have |  |
| I've never seen this page before, it looks cute and super simple | Opens Event html page |
| Hmm... I think.. not much to say here?? I'm just scrolling up and down, its quite a short page actually... Ummm maybe like can i click on the events.. lke here?? I dont know like if its an event page.. maybe i want to see the details | Hovers over event box |
| Also here, I know you said you're going to get rid of it i think?? But yea it's a bit confusing like it looks like a button and its meant to be?? but I cant click on it | Talks about the 'View past events gallery' button |
| And I'm just gonna click on this so i can see all the pages | Clicks on 'Transport' button |
| Ok so this one is quite simple as well.. I cant scroll though are you going to put like.. more content?? | Opens transport html page |
| This is cool though | Selects different buttons for car, train, and bus |
| I think maybe.. you could have like a short explanation of how to get there like for the train, you could say like to use Rhodes station on the specific train line |  |

After conducting my second user testing, I was able to understand the following:
- Making buttons change its appearance when hovered improves user flow and understanding
- Remove unnecessary buttons, for example the 'View Past Events Gallery'
- More explanations to support image helps user understanding

To improve the website, I have changed the following:

### Hovering over buttons
When users are searching through the website with their cursor, it is important for the website to visually inform them what is interactive, and what is not. To do this, I have made sure that all elements of the website that are interactive changes its appearance when the user hovers over them. 

For example, I have made use of the transition feature of the html coding to create the effect of the button changing colours when hovering over, as shown below:
```
.commonbutton {
  transition: background-color 0.8s ease;
  cursor: pointer;
  background-color: #fff;
}

.commonbutton:hover {
  background-color: #f0e6da;
}
```
This code allows the button to change its background colour when the user hovers over the item. By doing this, users are able to identify which elements of the websites are interactive.

### Adding more texts
During the end of the think-aloud session, the user had mentioned that there were very minimal texts which confused the users on what some sections were about. This issue showed that I lacked accomodating for the *Help and Documentation* usability heuristics. To improve the website, I have included a section below the transport page giving written explanations on how users can navigate the area.
![Image of the transport page, with text explanations on the bottom of the image](../assets/images/text.png)

# Comparisons between wireframes and prototype
An extensive number of iterations occurred between the wireframe and prototype phases as the design evolved. While it’s not possible to document every iteration, the following outlines the key developments.

### Sticky header
![Image of the sticky header wireframe and prototype](../assets/images/difference.png)
Originally, I have planned for the sticky header to take larger space within the landing page. This decision was made as I wanted the sticky header to act as a 'whitespace' when viewed together with the page content. However, during the prototyping stage, I realised that this idea was not feasible, as it ultimately resulted in a cluttered layout. 

To tackle this challenge, I have reflected back to my moodboard created during the previous assignment. Below is the image of my moodboard:
![Image of moodboard](../assets/images/moodboardex.png)
After careful reflection of the website design style, I had noticed that I had not made use of the 'wave' pattern enough to emphasise the Parramatta river accompanying Rhodes Foreshore. With this, I had referred to an AI software (Microsoft Copilot) to help me create a wave structure. The wave patterns were made using the below html coding:

```
<svg viewBox="0 0 1200 100" preserveAspectRatio="none" xmlns="http://www.w3.org/2000/svg">
        <path d="M0,50 C150,0 300,100 450,50 C600,0 750,100 900,50 C1050,0 1200,100 1350,50" 
              stroke="#7387A4" stroke-width="20" fill="none" />
```
This structure allowed me to adjust the stroke colour and width of the wave, encouraging originality in the design. With this code, I was able to implement 4 waves in the sticky header to reflect the Parramatta river, while maintaining whitespace.

### Navigations
![Image of the navigations button, wireframe and prototype](../assets/images/difference2.png)
Here is a subtle, yet crucial iteration I had made to the navigation buttons located in the landing home page. 

Initially in my wireframe, I had included 5 buttons which navigates to different parts of the website. During the wireframing stage, I believed that these button selections effectively guided users in understanding what information to provide about the location.

Moving into my prototyping stages and iterating the prototype to become highly interactive, I had realised that the destinations for the navigations were highly limited, due to the low page number. Although navigation pages such as the 'Map' will be effective in users quickly gaining spacial knowledge of the location, the maps of the location were located in different areas of the website, for different purposes. Similarly, "Things to do" and "Events" seemed extremely similar to one another which could result in user confusion when lining them side-by-side. 

With these observations, I was able to filter through which buttons were truly necessary for users. I had removed the 'Map' button. Rather than completely removing the 'Events' button, I had moved it up to the sticky header for users to check any time.

### Transport options
![Imge of the transport page, wireframe and prototype](../assets/images/difference3.png)
Here, I have removed the 'Navigate Rhodes Like a Pro' section from the transport page, replacing it with an option for users to access Google Maps. 

When looking over all sections of the website, I had realised that this feature overlapped another part of the website, shown below:
![Image of the Map view from activities section on landing page](../assets/images/difference4.png)
This part of the website is located in the homa page, where users are able to select the 'trail', 'map', or 'list' button to view activities in their desired way. When the 'map' is selected, a map of Rhodes Foreshore is visible, along with activities layered over the map to visualise where these activities can take place. This part of the code played an almost-identical purpose with the removed wireframe section, where users were able to view where each activities were in the map. The only visible difference were the format and location of the section, one being in the landing home page along with activities, and the other being in the transport page.

After removing this feature, the final page felt empty and short. To fix this issue, I had created a new feature where users are able to navigate to Google Maps, to properly see the best way they can navigate to Rhodes Foreshore.


# Discussion of any further iterations/improvementse

### Colours
I have iterated a few of my colours, using the Contrast Checker introduced in class during week 9.
Below are the changes I made for the purpose of creating a stronger contrast between the white background:
![Image of changes in colour](../assets/images/colourchange.png)

Although I was happy with the original colours, they did not contrast well with the white background of the website, especially the orginal soft pink. My original aim for the orange colour was to portray the playfulness and creativeness of Rhodes, with the soft pink reflecting a sense of accomodation, like a mother's love, accepting all diversity. However, this had backfired the website to look weak, with low impressions on users. 

To improve the visual aesthetics of the website, I had adjusted the above three colours to have a stronger impression contrasting the white background. Ensuring that each element of the website has a strong, bold identity was motivated by the goal of improving accessibility. This design choice helps individuals with visual impairments distinguish between sections and interact with the content more easily.

### Error Preventions
It is crucial in a website that users are informed of significant changes that will be made with their interactions. In the case of this website, pressing the 'Google Maps' button will navigate them to the official google maps website. Users should be notified of this drastic change.

![Image of confirmation on navigating to Google Maps](../assets/images/iterations.png)

To address *error preventions* from the **10 usability heuristics**, I have implemented an additional step before navigating the user. Above is a screenshot of the confirmation that will become visible when the user pressed on the 'Google Maps' button. Asking if the user would like to open a new tab for google maps, they are able to choose to open the new tab, or go back to the previous page. By introducing this additional layer, I aimed to prevent users from performing unintended or surprising actions.

### Events description
When reflecting on the informativeness of the website, I realised that users lacked understanding of what the displayed events were about. Although there were lists of what events took place at the location, there were no information about the dates, time, or detailed descriptions of these events. Without this additional information, the events page was pointless.

![Image of the Korean Calligraphy events description page](../assets/images/iterations1.png)

To recover from this issue, I had implemented a new page specific for informing the specifics of each events. This new page has the title of the event, an enlarged image of the event from the Events page, as well as the location, date, time, and descriptions of the event. By implementing this change, users are now given insights on what the events are and are able to join these events if they wish to. I have also ensured to address the **usability heuristics** of *User Control and Freedom* by including the 'Back to event' button on the top left corner. At the same time, I believe that my design decisions incorporate the heuristics of *Matching Between the System and the Real World* by including an arrow in the button. By doing this, users are able to quickly recognise that by clicking on the top-left button, they are able to navigate themselves back to where they came from without having to read the text.

To create the effect of going back to the previous page, I have used the below html code:
```
    <div class="back-button">

  <a href="events.html">← Back to Events</a>

    </div>
```

# A list of browsers and screen resolutions you have tested and confirmed are working correctly

**Laptop & Google**
![Image of laptop resolution on Google](../assets/images/laptop.png)
![Image of laptop resolution on Google](../assets/images/laptop1.png)
![Image of laptop resolution on Google](../assets/images/laptop2.png)

**Laptop & FireFox**
![Image of laptop resolution on Firefox](../assets/images/firefox.png)
![Image of laptop resolution on Firefox](../assets/images/firefox1.png)
![Image of laptop resolution on Firefox](../assets/images/firefox2.png)

**Iphone 14 Pro Max**
![Image of Iphone resolutions](../assets/images/iphone.png)
![Image of Iphone resolutions](../assets/images/iphone1.png)
![Image of Iphone resolutions](../assets/images/iphone2.png)

**Ipad Mini**
![Image of Ipad resolution](../assets/images/ipad.png)
![Image of Ipad resolution](../assets/images/ipad1.png)
![Image of Ipad resolution](../assets/images/ipad2.png)

# References

### Images used:

AllTrails. (n.d.). Putney Park [Image]. AllTrails. https://www.alltrails.com/parks/australia/new-south-wales/putney-park/photos

Campbelltown City Council. (n.d.). Playgroup at the Bicycle Education Centre [Image]. Campbelltown City Council. https://www.campbelltown.nsw.gov.au/Whats-On/Playgroup-at-The-Bicycle-Education-Centre

City of Canada Bay. (n.d.). What’s on [Image]. City of Canada Bay. https://www.canadabay.nsw.gov.au/whats-on?keys=&field_date_value=today&field_date_end_value=&field_event_categories_target_id%5B237%5D=237

City of Stonnington. (n.d.). Pets in the Park [Image]. City of Stonnington. https://www.stonnington.vic.gov.au/Community/Arts-and-culture/Festivals-and-events/Pets-in-the-Park

DC Property. (n.d.). 10 Cropley Street, Rhodes [Image]. DC Property. https://dc.com.au/672/10-cropley-street-rhodes

DogPack. (n.d.). Rhodes Foreshore Park [Image]. DogPack. https://www.dogpackapp.com/parks/australia/new-south-wales/sydney/rhodes-foreshore-park

Google. (n.d.). Google Maps [Map]. Google. https://www.google.com/maps

Kyora Landscapes. (n.d.). Foreshore Park, Rhodes [Image]. Kyora. https://kyora.com.au/foreshore-park-rhodes/

Mapcarta. (n.d.). Rhodes Foreshore Park [Image]. Mapcarta. https://mapcarta.com/W284562170

ParraParents. (n.d.). Bennelong Bridge, Wentworth Point [Image]. ParraParents. https://www.parraparents.com.au/things-to-do/bennelong-bridge-wentworth-point/

ParraParents. (n.d.). Rhodes Foreshore Park, Rhodes [Image]. ParraParents. https://www.parraparents.com.au/parks-playgrounds/rhodes-foreshore-park-rhodes/

Ryde District Mums. (n.d.). Rhodes Foreshore Park [Image]. Ryde District Mums. https://rydedistrictmums.com.au/rhodes-foreshore-park/

Sydney Dog Parks. (n.d.). Rhodes Foreshore Park [Image]. Sydney Dog Parks. https://sydneydogparks.com.au/dog-parks/rhodes-foreshore-park/

TeamLink. (n.d.). Rhodes, NSW 2138 suburb profile [Image]. TeamLink. https://www.teamlink.com.au/suburb-profile/rhodes-nsw-2138

Three Bridges Run. (n.d.). Entries open [Image]. Three Bridges Run. https://threebridgesrun.com.au/entries-open-3/

WeekendNotes. (n.d.). Rhodes’ unique parks [Image]. WeekendNotes. https://www.weekendnotes.com/rhodes-unique-parks/

WeekendNotes. (n.d.). The Big Issue Street Soccer Program – Parramatta Park [Image]. WeekendNotes. https://www.weekendnotes.com/the-big-issue-street-soccer-program-parramatta-park/

YouTube. (2019, October 10). Rhodes Foreshore Park [Video]. YouTube. https://www.youtube.com/watch?v=gfGO1ghjxGU

### HTML and CSS code I was inspired by:
Active CSS. (n.d.). if-display: selector. Retrieved November 4, 2025, from https://activecss.org/manual/if-display.html
- This site was used to understand how a code was structured to create the effect of selecting buttons which made certain information visible. This had inspired me to create the selection buttons in both the activities section in the home page, and the transport page.


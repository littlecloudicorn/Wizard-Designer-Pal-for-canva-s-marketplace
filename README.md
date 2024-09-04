### Inspiration 

I was inspired to create Wizard Designer Pal because I wanted to build a tool that could serve as a personal design assistant for graphic designers, especially those who are just starting out or eager to learn. I saw a need for an app that could not only help with basic design principles, like color theory, but also provide advanced features like accessibility checks and color blindness simulation. From my own experience, I know that some companies place great importance on making designs accessible to people with color blindness, and I wanted to incorporate that into this app.

### What it does

Wizard Designer Pal is an app that works with generative AI to assist graphic designers in various aspects of their work. It offers a range of functionalities, but its main purpose is to serve as a personal design assistant. Users can ask questions about color theory and other best practices in graphic design. The app also performs quality checks on images, provides image descriptions, and evaluates the design’s accessibility—particularly how it would look to people with different types of color blindness. 

Additionally, it offers image background recommendations

![background_recomendation_process](https://hackthons-ep-2024.s3.us-east-2.amazonaws.com/background_recomendation_process.png)

![background_recomender_and_variation](https://hackthons-ep-2024.s3.us-east-2.amazonaws.com/background_recomender_and_variation.png)

Can create image variations based on the current image’s description. 
![Image_variation_process](https://hackthons-ep-2024.s3.us-east-2.amazonaws.com/Image_variation_process.png)

The color blindness simulation and background recommendation features are particularly valuable for ensuring that designs are inclusive and accessible.

![color_blindess_simulation](https://hackthons-ep-2024.s3.us-east-2.amazonaws.com/color_blindess_simulation.png)
### How I built it

I built Wizard Designer Pal using a combination of Canva SDK, React, Node.js, Javascript and and Python in the backend. These technologies were new to me, which made the process both challenging and rewarding. I spent a lot of time learning the ins and outs of these languages and frameworks, which allowed me to create a robust and user-friendly app. The integration of generative AI for tasks like image variation and background recommendation required careful planning and implementation, but the end result was worth the effort.

Prompt engineering was key to the success of the project in achieving the desired results

Serverless architecture with Python, using Amazon Lambda and API gateway.


- **Potential Impact:**
How big of an impact could the project have on Canva’s users or a third party product’s users? Does it fill a major gap in the product? Is this something users have been asking for?

**Anwer:**  Having a design assistant will encourage more people without design experience to use Canva’s platform even more. This app has the potential to attract more customers, as they’ll feel extra motivated to create and learn with guidance from an expert in the field. This is why it would be a valuable addition.

Incorporating features like design accessibility and color blindness simulation will be important for companies like the one I previously worked for, as they prioritize these aspects.

- **Quality of the Idea:**
How creative and unique is the project? Does the concept exist already? If so, how much does the project improve on it?

**Anwer:** I reviewed the current Canva apps and found that none were quite like mine. I noticed that Canva currently lacks a design assistant to guide users through the design process. This is particularly important for people like me who don't have a design background, new designers who are still learning, and even experienced designers who want to continue improving their skills.

Additionally, my app includes a feature that determines if a design is accessible to everyone. Unlike other apps, it specifically focuses on being inclusive for people with color blindness. My app even include a color blindness simulator. The color simulation feature enables designers to visualize how their design would look to people with different types of color blindness.

My app includes background recomendations and image variation where a new image will be generated based on the description of the current image.

Although there are AI-powered apps out there, mine stands out due to its specialized focus. Instead of just generating AI images like the more generic options, my app leverages AI alongside JavaScript capabilities and existing Canva's components to make this Designer assistant possible.

Without any doubt my app is original and unique! 


### Challenges I ran into

One of the biggest challenges I faced was learning to work with Canva SDK, React, Node.js. Since I don’t typically work with these programming languages, there was a steep learning curve. Debugging and ensuring that all the features worked smoothly together was another challenge, especially when it came to integrating the color blindness simulation feature. However, overcoming these obstacles made me more confident in my ability to work with new technologies and deliver a functional, polished product.

I was new to the Canva SDK, which required a period of learning. Working alone and not being good at making presentation videos 😅.


### Accomplishments that I'm proud of

I’m particularly proud of the color blindness simulation feature. Knowing that some companies, based on my own experience, are keen on making their designs accessible to people with color blindness, I felt it was crucial to include this in the app. Additionally, the image background recommendation feature turned out to be more sophisticated than I initially expected, providing users with valuable insights that can enhance their designs. Overall, I’m proud of how I was able to learn new technologies and successfully implement features that can genuinely help designers.


### What I learned

Throughout this project, I learned a great deal about Canva SDK, React, Node.js, and TypeScript. These technologies were challenging for me, but tackling them head-on has expanded my skill set and made me more versatile as a developer. I also gained a deeper understanding of the importance of accessibility in design, especially for users with color blindness. This project reinforced the idea that designing with inclusivity in mind not only broadens your audience but also creates better, more thoughtful work.


### What's next for Wizard Designer Pal

Looking ahead, I plan to continue improving Wizard Designer Pal by adding more features that cater to both novice and experienced designers. I want to refine the existing functionalities, especially the AI-driven recommendations and accessibility checks. Additionally, I’m considering expanding the app to support more types of design work, such as UX/UI design and possibly even 3D modeling. The goal is to make Wizard Designer Pal a comprehensive tool that can assist designers in every aspect of their creative process.

I want to improve the performance of the same.

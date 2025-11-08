# Hypermedia-Project-CV-

# Personal CV Website – Pol Cañadas Costa

This is my personal online Curriculum Vitae, built entirely using HTML and CSS. The goal of this project was to create a responsive, visually appealing, and professional résumé that reflects both my personality and technical skills in web design and front-end structuring.

# Project Analysis – User Profile

When designing this project, I firstly created a clear user persona to define my audience. The main user of this website is a potential recruiter or employer (just like the usual interviewers that test you online on a interview)  looking for a quick yet, insightful overview of my background. This kind of person values clarity, organization, and professional aesthetics. They are likely to browse from a computer or tablet, expecting smooth navigation and easy access to relevant details.

In addition, the CV also targets academic mentors, collaborators, or colleagues who may want to review my technical profile or research interests. Therefore, I designed the layout to highlight essential information such as education, experience, and skills — all presented clearly and concisely, without unnecessary distractions. 

In other words, this project tries to be professional so anyone can get an general idea of my persona, but it also tries to be visually aestethic enough so it can stand out between other CV without taking into account my skills.

# Project Analysis – Information Architecture

The information is structured to guide the reader through a logical and visually balanced flow. The layout follows a two-column design that separates personal information (left gray column) from professional achievements (right column). The header immediately establishes identity with a prominent portrait and name, serving as the visual anchor. 

I placed the "About Me" section first in the left column to give recruiters immediate context about my personality and soft skills. Following this, I positioned "My Contact" prominently to ensure accessibility, as contact information is critical for recruiters. I included a clickable GitHub logo on the right side of the contact section to provide quick access to my portfolio while maintaining visual balance (and also add some interactivity for the user).

The "Language Skills" section comes next, with visual star ratings for quick comprehension. This placement acknowledges the importance of language proficiency in today's global tech market. I mean, even more if you are trying to work from home in another country. I then positioned "Tech Abilities" at the bottom of the left column, organizing technologies into four clear categories (Frontend, Backend, Databases, Other Expertise) using a two-column sub-layout for efficient space usage, and showing what I worked with.

After all this, the right column prioritizes professional credentials. "Education" appears first because academic background is often the initial filter for technical recruiters. Each entry includes institutional logos for brand recognition and credibility (and to make it look cooler). "Notable Experiences" follows, with clear year markers in blue italic text to draw attention to recency. I used justified text for descriptions to maintain a clean, professional look. There are three of them, each with their own things and memories.

Finally, the page ends with a blue footer bar, which visually closes the CV and balances the overall composition. The information hierarchy ensures that the user naturally reads from top to bottom and left to right, focusing first on identity, then credentials, so the longest part to read, the experiences, can be left for the end.

# Project Analysis – Visual Design

For the visual design, I followed a clean and modern aesthetic with strong contrasts between sections. The first thing the user is going to see will be the blue gradient header, which contains an image of me, alongside my name and some more info of me, and the footer establish a professional yet approachable tone, while the two-column layout brings structure and readability. I chose a light gray background for the left column to visually separate personal data from academic content, enhancing contrast and legibility.

For typography, I selected a strategic combination of Google Fonts that are industry standards in professional documentation. I chose Montserrat for all headings, titles, and emphasis elements because of its geometric, modern appearance and excellent readability at various sizes. This font is widely used by many engineers on their CV (as seen on the internet), which gives it an inherent sense of credibility. For body text, I implemented Lato, which offers a warm, humanistic feel while maintaining professional clarity. This font pairing creates a clear visual hierarchy—Montserrat's bold, structured letterforms naturally draw attention to important information, while Lato's softer character makes longer text passages comfortable to read. I used varying font weights strategically: 800 for my name in the header for maximum impact, 700 for section headers and institution names, and 600 for labels and emphasis within body text. I did not really want to use many more because I felt like if I started abusing them, it could be seen badly from the user's eyes (making it less professional). 

The color palette was carefully selected to convey trustworthiness and professionalism while avoiding monotony. I used a gradient blue scheme throughout, starting with a vibrant cyan-to-navy gradient (#33c3ff to #003399) in the header that immediately establishes a tech-forward, professional tone. For section headers and emphasis text, I employed a deep navy blue (#003366) that provides strong contrast without the harshness of pure black. Body text uses a sophisticated dark slate color (#34495e and #2c3e50) that's easier on the eyes than black while maintaining excellent readability. I added an accent blue (#0077b6) for year markers and interactive elements, creating visual interest and guiding the user's attention to important dates. The left column's light gray background (#f5f5f5) creates subtle visual separation from the white right column without feeling disconnected.

I implemented multiple interactive elements to enhance user engagement too. The GitHub logo features a smooth scale-and-fade hover effect that provides immediate visual feedback. All links use color transitions on hover, changing from navy to a brighter blue. The "About Me" section has a subtle box shadow and border to make it feel like a featured element, drawing immediate attention. All icons and images were placed inside an images/ folder inside the repository for neat organization.

For layout and spacing, I used modern CSS flexbox extensively to create responsive and balanced layouts. The two-column structure divides at exactly 50%, trying to create symmetry. I applied generous padding throughout (20-40px in various sections) to prevent cramped feelings and improve readability. Line heights range from 1.6 to 1.8, which research shows is optimal for reading comprehension. Letter-spacing on headers (1.5-4px) creates a more premium, spacious feel that's common in high-end design.

The responsive design ensures the CV looks professional on all devices. I created four breakpoints (900px, 768px, 480px, and 360px) where the layout adapts. On mobile devices, the two-column layout collapses into a single column, the portrait scales down proportionally, and language skills stack vertically with subtle background boxes for better organization. I mean, I usually tend to see things on my tablet or my phone, so it would be too risky to not take the possibility of them using any or that.

Every design decision was made with recruiter psychology in mind—from the initial impact of the bold header, to the strategic use of white space that guides the eye naturally through my qualifications. The result is a CV that feels both contemporary, professional yet approachable, and most importantly, easy to scan while rewarding detailed reading. The overall goal was to combine aesthetic appeal with functionality, resulting in a CV that feels personal, professional, and consistent. 

# Link to the Figma Project

I must say that most of the ideas I just explained came while I was actually doing the code parts. However, the Figma project really helped me doing a prototype of what I wanted, how I wanted it, and where I wanted it. So, even if its not entirely updated to the final product, it really lent me a hand to do it right. Not to say it made it so much easier to think about creating sections on the code too.

https://www.figma.com/design/I29Ys6dNTZ21s6FTtBeDSV/Pol-Ca%C3%B1adas-Costa--CV-?node-id=0-1&t=IH2cZgm13RiuTOMS-1 

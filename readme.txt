--Readme document for Remiel Shirazi, remielshirazi@gmail.com--
IN4MATX 133, Assignment 1: Portfolio

1. How many assignment points do you believe you completed?

10/10 (self-assessment; no bonus claimed)
- 1/1 Readme
- 2/2 Basic HTML content
- 1/1 Basic CSS styling
- 1/1 Advanced feature
- 2/2 Responsive layout
- 1/1 Passes validation checks
- 2/2 Embraces spirit of the assignment

2. What features did you include?

(a) Basic HTML: three images with descriptive alt text, headings and paragraphs, external links, unordered lists, and semantic header/nav/main/section/article elements. There is one page.

(b) CSS: simple padding and margins, black text on white, a white top header with my name on the left and black navigation links on the right, consistent heading sizes, and thin section dividers. Text uses Arial/Helvetica/sans-serif. Images shrink to fit small screens; a basic media query reduces spacing below 600px.

(c) Advanced: section navigation and nested selectors such as nav a, section h3, and #roblox img.

The layout uses normal document flow, plain headings, lists, a basic navigation bar, and horizontal dividers. The copyright line is removed. There are no cards, live player counts, JavaScript, or libraries.

Selected Roblox work: Kabuki, Snipers VS Robbers, and Da Hood Entertainment. A separate list includes Bloom AI, LyricLens, CapsLockViewer, and roblox-upload. Accomplishments are ordinary bullet points rather than statistic blocks.

This is a new HTML/CSS page for this course. Facts and images come from my existing portfolio; its layout and code were not reused.

3. Did you ignore accessibility warnings or errors? Why?

AChecker WCAG 2.0 AA found 0 known problems, 0 likely problems, and 53 potential problems. No known/likely errors were ignored. All potential prompts were reviewed:

- Images (178, 16, 8, 14, 251, 11): the game artwork and group logo have short descriptive alternatives. They are not complex data diagrams needing long descriptions. The game/group names also appear as normal text, including the name shown in the Snipers VS Robbers artwork. Essential information and instructions do not depend on image colors.
- Direction/language (271, 270, 110): the text is English with lang="en". Proper names do not require extra language/direction markup. There are no right-to-left passages.
- Lists/relationships/sensory instructions (248, 262, 250): navigation, accomplishments, other projects, and contact links use ul/li. The nav is labelled. Instructions use destination names rather than color, shape, or position alone.
- Bypass blocks (28): the visible Skip and Back links were removed. The page retains nav/main landmarks, logical headings, and short navigation. The header name link comes before the navigation and targets the focusable main element, providing a route directly to the content.
- Title/links (54, 19): the title identifies the portfolio. Link text identifies games, projects, sections, and contact destinations. All internal targets exist.
- Site map (184): this is one page; section navigation covers its main sections.
- Headings (42, 43, 44): h1 is my name, h2 labels sections, and h3 labels the three Roblox entries. They represent content hierarchy.
- Consistency/quotations (276, 131): the reading/navigation order stays the same at every width. There are no long quotations needing blockquote.

Manual checks: all three images load, keyboard focus is visible, headings follow a logical order, and section navigation works. Black text and navigation links on white have 21:1 contrast. The earlier single-column layout had no horizontal overflow at 320, 390, 599, 600, 601, 768, 960, or 1440px, or at equivalent 200% zoom. The latest CSS retains fluid images and wrapping navigation links.

W3C HTML: no errors or warnings.
W3C CSS level 3: no errors. The all-warnings setting lists 9 warnings: one for link background inheritance and eight for intentional margin/padding overrides in the small-screen media query. Links inherit the white page background and have 21:1 contrast. The spacing overrides are intentional.

The three included JPG files are actual screenshots of the final source's checker results: valid-html-index.jpg, valid-css-index.jpg, and valid-accessibility-index.jpg. The complete CSS was checked through W3C's documented direct-input GET interface. AChecker checked the actual index.html; manual browser checks covered the local stylesheet and images.

4. How long did it take?

About 0.5 hours of AI-assisted setup, implementation, revisions, and checking across these Codex sessions. This excludes prior work on my main website and Roblox projects.

5. What resources and AI tools did you consult?

https://github.com/uci-inf-133/a1-portfolio
https://remielshirazi.com/
https://remielshirazi.com/projects
https://remielshirazi.com/projects/roblox
https://remielshirazi.com/projects/pogi-games
https://remielshirazi.com/projects/bloom-ai
https://remielshirazi.com/projects/lyriclens
https://remielshirazi.com/projects/capslock-viewer
https://remielshirazi.com/projects/roblox-upload-cli
https://remielshirazi.com/links
https://www.roblox.com/games/128541381932893/Kabuki
https://www.roblox.com/games/80414354975086/Snipers-VS-Robbers
https://www.roblox.com/communities/4698921
https://validator.w3.org/nu/
https://jigsaw.w3.org/css-validator/
https://jigsaw.w3.org/css-validator/manual.html
https://achecks.org/achecker/

The course's HTML/CSS/accessibility/responsive-design lectures were also consulted. Image URLs are in assets/sources.txt.

AI disclosure: I asked Codex to create a basic portfolio from the starter and my existing site, then simplify it to black/white, feature Kabuki/Snipers VS Robbers/Da Hood Entertainment, add other projects, replace statistic blocks with an accomplishments list, describe my broader work as an entrepreneur in the introduction, remove the copyright line, and restore the original white top header with my name on the left and navigation on the right, along with heading sizes and dividers, and remove the visible Skip/Back links. Codex researched the content, generated and revised the HTML/CSS, ran browser/validator checks, collected screenshots, and helped complete this readme. This implementation is AI-assisted.

6. What classmates or individuals did you consult?

No classmates or other individuals were consulted during this work. Codex assistance is disclosed above.

7. Anything special needed to run the code?

Unzip and open index.html in Chrome. No installation, build, framework, or server is required. The stylesheet and images use relative paths and are included locally. Internet is needed only for external links/email. Nothing has been submitted to Canvas or deployed as a website.

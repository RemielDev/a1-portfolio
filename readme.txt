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

(a) Basic HTML: three images with descriptive alt text; appropriate headings and paragraphs; external links; semantic header, nav, main, section, article, and footer elements. There is one page.

(b) CSS: padding and margins for readable spacing; a restrained green color palette; responsive layouts and an Arial/Helvetica/sans-serif fallback list. No CSS library is used.

(c) Advanced: a navigation bar linking to sections, plus nested selectors such as .project .role and .contact-links a. The grid changes from one column to two at 640px and three at 960px. About/Contact sit side by side when there is room.

The page primarily shows my Roblox work: Pogi Games, Da Hood Entertainment, and Bloom AI. It includes static achievements, my roles, and contact links. There are no live player counts, API calls, animations, or JavaScript dependencies.

This is a new HTML/CSS page for this assignment. The facts and logos come from my existing portfolio; its layout and website code were not reused.

3. Did you ignore accessibility warnings or errors? Why?

AChecker WCAG 2.0 AA: 0 known problems, 0 likely problems, 50 potential problems. No known or likely errors were ignored. I reviewed all potential prompts, grouped below by their check IDs:

- Images (178, 16, 8, 14, 251, 11): the three logos identify their projects and have short descriptive alternatives. They are not complex charts requiring long descriptions. Project names and roles also appear as normal text. The logos do not convey instructions, data, or essential information through color alone.
- Direction/language (271, 270, 110): the text is English, with lang="en". There are no passages requiring a different language or right-to-left direction. Project/person names are proper names.
- Lists/relationships/sensory instructions (248, 262, 250): navigation and contact links use ul/li; highlights use dl/dt/dd; the main navigation is labelled. Instructions identify destinations with words rather than shape, color, or position alone.
- Skip link (28): a working skip-to-main-content link is the first keyboard stop. Enter moves focus to main. It becomes visible on focus.
- Title/links (54, 19): the title identifies me and the subject. Link text describes each destination, including project names and contact services. Internal links target existing section IDs.
- Site map (184): this is a single page, with visible navigation to all main sections, so a separate site map is unnecessary.
- Headings (42, 43, 44): one h1 describes the page; h2 elements label sections; h3 elements identify projects. Headings describe content, not just formatting.
- Consistency/quotations (276, 131): the navigation and content retain their order at every width. There are no long quotations needing blockquote.

Manual checks: keyboard navigation, visible focus, heading order, image alternatives, section links, and browser accessibility-tree labels. Normal text contrast is at least 6.3:1. The page has no horizontal overflow at 320, 390, 400, 401, 639, 640, 641, 768, 959, 960, 961, and 1440px. It also remained readable without overflow at an equivalent 200% zoom.

W3C HTML: no errors or warnings.
W3C CSS level 3: no errors. At the "all warnings" setting, 17 warnings concern inherited foreground/background colors and deliberate CSS overrides (spacing and responsive grid/font rules). The inherited colors were checked for contrast; the overrides are intentional.

Screenshots:
- valid-html-index.jpg: final index.html uploaded to the Nu HTML checker.
- valid-css-index.jpg: complete style.css checked through W3C direct input. The upload/POST route stalled or returned a server exception, so the same complete CSS was sent through its documented GET interface.
- valid-accessibility-index.jpg: final index.html uploaded to AChecker.
- valid-accessibility-index-styled.jpg: an additional AChecker check with identical CSS and images embedded in a temporary checking copy, so the remote checker could see assets normally loaded through local relative paths. This checking copy is not an extra portfolio page. Both checks returned 0 known/0 likely/50 potential problems.

4. How long did it take?

About 0.3 hours of AI-assisted setup, implementation, and checking in this Codex session. This excludes previous work on my main website and Roblox projects.

5. What online resources and AI tools did you consult?

Starter and source content:
https://github.com/uci-inf-133/a1-portfolio
https://remielshirazi.com/
https://remielshirazi.com/projects
https://remielshirazi.com/projects/roblox
https://remielshirazi.com/projects/pogi-games
https://remielshirazi.com/projects/bloom-ai
https://remielshirazi.com/links
https://github.com/RemielDev
https://www.roblox.com/games/2788229376/Da-Hood
https://www.roblox.com/games/4954752502/Tower-of-Misery

Validation:
https://validator.w3.org/nu/
https://jigsaw.w3.org/css-validator/
https://jigsaw.w3.org/css-validator/manual.html
https://jigsaw.w3.org/css-validator/DOWNLOAD.html
https://achecks.org/achecker/

The course's HTML/CSS/accessibility/responsive-design lectures were also consulted. Exact image-source URLs are in assets/sources.txt.

AI disclosure: I asked Codex to use the assignment starter and information from remielshirazi.com to create a very basic portfolio focused on my Roblox success, without live CCU information or complex libraries. Codex researched the content, generated the HTML and CSS, ran browser and validation checks, assembled screenshots, and helped complete this readme. The implementation is AI-assisted; I am not claiming it was written without assistance.

6. What classmates or individuals did you consult?

No classmates or other individuals were consulted during this work. Codex assistance is disclosed above.

7. Anything special needed to run the code?

Unzip the submission and open index.html in Chrome. No installation, build command, framework, or server is required. style.css and the three images use relative paths and are included locally. An internet connection is needed only when following external links or emailing. This has not been submitted to Canvas or deployed as a website.

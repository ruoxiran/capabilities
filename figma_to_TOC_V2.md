Accessibility at the Edge Community Group
About this markdown: manual copy/paste from the figjam board

# Guide to this effort
Frontmatter for the information below
## capability content
Review the capability content. 
* What does the reader absolutely need to know?
* What type of info isn???t needed?
* Tone???what is the focus for the capabilities? Example below.
When writing, one idea per sticky
## capability organization
Review the capabilities and their sections. 
* Do they all relate to the main heading?
* Are some sections too long?
* Is the information architecture correct?


# Creating Accessible Content & Presentation
This is, in OSI language, the presentation layer. In the classic OSI 7 layer model, application (the control and interaction layer) is distinguished from the presentation (the look and feel) layer. 
Visual Perception & Interaction
User-triggered transformations, user-triggered personalizations
Controlling such presentation layer changes
## cursor & focus
Focus Visibility Enhancement
Isolating Specific Semantic or Interactive Components for Efficient Browsing and Access: 
methods and technologies used to enhance user experience by isolating specific elements within a digital interface. It enables users to navigate efficiently through content by focusing on particular types of elements, such as headings or buttons.
### Optimize cursor size
### reading guide
### Hyperlink Highlighting
## text
Managing Text Readability
text, white space and reading guide transformations
### text size
### text spacing, white spacing
### line-height
### facilitate document format translation (Export)
### personalized font selection
accessible font, dyslexia friendly font
### Margin Management
### Paragraph Indentation
### Text Wrapping Techniques
### Drop Cap Implementation
### Bulleted and Numbered Lists
### Text Box Framing
### Shadow and Outline Effects
### Text Transparency Control
### Interactive Text Elements
## images
graphics remediation
How things look
## forms
## color
### Optimize color contrast
## links
## rich media
non-html content
### audiovisual content
### animation control
### auto play videos


# Creating Accessible Functionality / Interaction
This is, in OSI language, the application layer. In the classic OSI 7 layer model, application (the control and interaction layer) is distinguished from the presentation (the look and feel) layer. 
Structural semantics: Can we rename this to something like ???Fixing structural semantics??? or ???Remediating structural semantics????
## navigation
Managing Navigation on the page
with a focus on its interactive elements
#### Heading Navigation
isolating the headings in a dedicated view, so that the reader can browse just the headings (like the table of contents in Wikipedia)
#### Button Navigation
isolating the button names in a dedicated view, so that the reader can browse just the buttons
#### Link Navigation
isolating the link or anchor texts  in a dedicated view, so that the reader can browse just the buttons
#### Landmark Navigation
isolating the landmarks in a dedicated view, so that the reader can browse directly to a landmark. (note that landmark implementation is not highly prevalent)
## dynamic content changes
carousels
## client-side interactions
selection boxes, size, color selections
## Notifications 
(notification management?)
error messages
## authN/authR (User authentication and authorization)

## TO BE SORTED -- UNDER THIS HEADING NOT YET SORTED 
### Expose structural semantics (reword?)
content is marked up structurally correct and is available to be use
we want content to have structural content
(edge can play a role in this by ???exposing??? those semantics to users in an understandable way to make edits)
-- make it easier and clearer for people to understand and use (bridge the gap between people that code and understand vs. those that want a header, as an example, to look how they want it to look in the structure.
### normalize the structural composite
consistent help/ consistent in where controls are, etc. 
edge could ???normalize??? this as it sees all the website/enforce consistency that???s derived from other websites and only learned/gained from viewing lots of websites
### semantic navigation
ability to navigate by semantics alone
there are AT shortcuts to jump semantic elements (page discovery/screen reader)
sighted users see at a glance, discover what the page offers; AT users do a similar activity using semantics
EX: Janina prefers to walk a nav tree to really understand the page-> four H1s, she wants to know what they are and if collapsed or expanded and what???s in them
#### Form labels
#### Hyperlinks
## Examples?
Should there be something we can point to for examples of good vs. bad examples? (descriptions exist in WCAG)
## reset to page defaults all personalizations 
(one button click reset option, easy to try and use and then reset, etc.) (like experimentation on settings)



# Aural Perception & Interaction
## Read content aloud
allowing capability of hosted read aloud.
(screenreader, JAWS, TTS, etc.)
think about the tools that allow highlighting of words as well
curb cut effect
voice options for the reader
User should retain control; two TTS voices should not jabber at the same time
## Voice command
Voice command: The ability to decorate a website with unique short Identifiers, e.g. put a number ???7??? on a button, then via voice recognition have the user speak ???7??? and the button is fired.

# Meeting content provider???s needs
## Automation
### Incompleteness
automated transformations, whatever benefit they may bring, will certainly neither fully meet the need, nor do the best possible job
This is a reasonable thing to try to do. We are used to automation working
A kind of incompleteness theorem
### automated detection of WCAG violations
There is broad community support for documenting and harmonizing the interpretation of W3C accessibility standards, such as WCAG and WAI-ARIA, for automated testing purposes.
### Human-in-the-loop automated remediation
Guided automation, to a system where human decision-making is integrated into the automated process. Automation handles routine, predictable tasks, but humans are involved in making decisions, providing guidance, or managing exceptions that are too complex or nuanced for the automated system.
## Manual
### Manually-written code 
is typically best; manual code injected from the Edge can be just as good as manual code at source
## content provider checks
### feature-bundling profiles
### image alt provisioning
### tooltip provisioning
### dictionary on demand
### form validation improvement
### interactive elements status clarification
### external link target notification
### ambiguous link notification
### video captioning
### missing title provisioning
### site language indication
### PDF remediation
### content moderation
### accessible pricing (strikethroughs)
### live site translations

## User feedback
### accessibility statement availability
### accessibility provider identification
### accessibility issue reporting


## Knowledge & Skills / Human Resources
### Bring skills to bear
The ability to bring to bear knowledge and skills
Given that the knowledge required to bring accessibility support to content is specific, has a steep learning curve. 
Any desire to hire internal experts is frequently found to be exceeding a company???s budget.
With this in mind, the ability to bring other experts to bear via the Edge is desired.

### Bring in experts
The ability to bring in devoted teams who are expert in this particular subject: accessible interfaces
It is difficult to train and retain software development talent that really are expert in accessibility.
The approach insisting that everyone in the organization must understand and contribute to the accessibility agenda might be asking too much.
Most devs can do accessibility once they???ve been trained, but do they want to do it day in and day out? Likely not.
### Bring in 3rd party services
"my site, their service"
It is a commonly used, widely employed, virtuous pattern of Web 2.0 to add services that are not one???s own expertise, to one???s website.
For services on one???s website, that the website owner did not personally create, website owners have no other method to improve accessibility outside of the Edge.
We would expect that content owner???s would do due diligence and validate that the service provider meets accessibility requirements.
#### Cross-site Expertise
A cross-site service is likely to have knowledge that a single site will not have
Leveraging remediations at scale, based on the reality that most sites are re-using common patterns, tooling and open-source components.
### only the edge knows for sure
Each page refresh can yield different content and a different user experience. Individual sessions often provide individual results that are unique.
Much as a thermostat should be positioned far from the heat source, to measure the temperature of the room, monitoring at the edge is the only way to determine what is happening there.
By definition, this cannot be done at source.
### Provenance 
Services should have clear provenance, labelling, in order to preserve user agency
### Edge Limitations
Can you discover enough to do a good job? Keep in mind that the end user may have legitimate privacy concerns that limit what you can discover.
### Accessibility Editing
#### accessibility editing, by site owner
Site owner may not have ability to login to their CMS, and prefer editing at the edge
#### accessibility editing, by 3rd party
See above, "bring in 3rd parties" and "cross-site expertise"

# Aspirational
## Group, match, create sets of desired personalizations / capabilities
## consistent help/ 
consistent in where controls are, etc.  
edge could ???normalize??? this as it sees all the website/enforce consistency that???s derived from other websites and only learned/gained from viewing lots of websites
## Support Legal Surrogacy
legal surrogacy services, whether fiduciary, medical, or probate.
## Support Guardians and Caretakers
rusted friend or a family member assisting a child or an elder, or person with cognitive disabilities
# Meeting User's Needs
## Principles
### Preserving User Agency, User Autonomy
### Configure once, use everywhere
### Raising awareness of accessibility 
(in isolation from implementing accessibility). 
#### raising awareness to increase access to functionality 
(need to consider wording as we define what this is)
### Implied rather than overt semantics
Design and software development consistently have IMPLIED semantics, by visual layout or page placement, rather than OVERT semantics.
### Honor user choices,
### Foster user choice. 
Don???t limit users to a single modality. 
Multiple or redundant access to features 
(e.g., color can be set in the operating system, in a browser extension, ain JS, in CSS)
### Encourage experimentation. Discover, see what works for you

# Appendices
## design principles
## acknowledgments

# end of file
EOF

# Personal Professional Website for Mental Health Therapist

## HTML / CSS / Javascript

---

- HTML
- CSS
- Javascript
- Boxicons
- EmailJS
- Psychology Today Verification Badge

- [Personal Professional Website for Mental Health Therapist](#personal-professional-website-for-mental-health-therapist)
- [Features](#features)
- [About](#about)
- [Design](#design)
- [Color Palette](#color-palette)
- [Boxicons](#boxicons)
- [Psychology Today Badge](#psychology-today-badge)
- [EmailJS Integration](#emailjs-integration)
- [Contributing](#contributing)
- [Commit Log](#commit-log)
- [Action Items](#action-items)

### Features

- Responsive Personal Resume/Info Website Using HTML CSS & JavaScript
- Smooth scrolling in each section.
- Developed first with the Mobile First methodology, then for desktop.
- Compatible with all mobile devices and with a beautiful and pleasant user interface.
- Contact Form Integration w/ EmailJs
- Equipped with Psychology Today Verification Badge

### About

This is a responsive personal resume and informative website built using HTML, CSS, and JavaScript. The website is designed with the Mobile First methodology, making it compatible with all mobile devices and having a beautiful and pleasant user interface. The website doubles as a resume presented for employers, but also serves as an informative site for potential clients interested, curious, or apprehensive about therapy.

The website includes explanations of therapy terminology and practices, as well as gives resources for those who need more invasive help such as the suicide prevention hotline, domestic abuse hotline, and other resources from state and local governments (Baltimore City). The navigation bar features scrollTo links that change to active class when matching the appropriate scrollHeight. The website also links to the provider's LinkedIn and Psychology Today pages.

## Design

### Color Palette

The color palette is pulled from the provider's headshot photograph to demonstrate a visually engaging, appealing, and welcoming vibe.

Color Palette
  --first-color: #63732f;
  --first-color-dark: #3f590b;
  --first-color-darker: #8a8c6f;
  --title-color: #966245;
  --subtitle-color: #a69163;
  --text-color: #4d5232;
  --link-color: #966245;
  --link-color-active: #dce908;
  --first-color-light: #ddbea9;
  --first-color-lighter: #fff;
  --white: #fff;

### Boxicons

The website utilizes Boxicons for its extensive collection of icons. The icons are incorporated directly into the HTML and CSS files using the Boxicon CDN.

```html
<link rel="stylesheet" href="https://boxicons.com/css/boxicons.min.css">
```

For more information on using Boxicons, including a full list of available icons, check out the Boxicons documentation: [boxicons.com](https://boxicons.com/)

### Psychology Today Badge

The website is equipped with the Psychology Today verification badge, providing additional credibility and visibility to the provider's profile. The anchor tag placed in the index.html footer as the desired location of the badge.

```html
<a href="https://www.psychologytoday.com/profile/1118513" class="sx-verified-seal"></a>

<script type="text/javascript" src="https://member.psychologytoday.com/verified-seal.js"
  data-badge="17"
     data-id="1118513"
   data-code="aHR0cHM6Ly93d3cucHN5Y2hvbG9neXRvZGF5LmNvbS9hcGkvdmVyaWZpZWQtc2VhbC9zZWFscy9bQkFER0VdL3Byb2ZpbGUvW1BST0ZJTEVfSURdP2NhbGxiYWNrPXN4Y2FsbGJhY2s="></script>
```

The data badge number corresponds to a specific combination of color and size.

```text
         Small   Med    Large
Light     10     11      12
Medium    13     14      15
Large     16     17      18
```

### EmailJS Integration

The website also includes a contact form that utilizes EmailJs to send user messages to the provider's fastmail inbox.

```html
<script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js">
</script>
```

More info on setting up EmailJs can be found @ [emailjs.com/docs/](https://www.emailjs.com/docs/)

## Contributing

As this is a personal website, there is little room for contributions. However, if you find any issues or have suggestions for improvements, please feel free to open an issue.

## Commit Log

1/6/25

feat: Update copy to LCSW-C per client request. Update footer year to 2025

5/5/24

Migration to savannaaltenor.com

7/5/23

- BRANCH master: Update `sitemap.xml`.

- BRANCH master: Refactored CSS code to remove empty rulesets.

- BRANCH w3c: CSS/Javascript Changes made for W3C validation.

   1. Removed duplicate variables and css comments
   2. Fix navigation link activation on scroll
         - Updated `main.js` to properly activate the navigation links when scrolling past their corresponding sections. The issue with `sectionLink` being null is resolved by iterating over the navigation links directly and checking the `href` attribute against the current section's `id`.

7/4/23

- BRANCH w3c: HTML Changes made for W3C validation.

   1. Fixed broken LMSW link in header
   2. Refactor HTML structure for improved accessibility
   3. Fix image dimensions in HTML markup
   4. Replaced `<section>` tags with `<div>` tags for appropriate sections.
   5. Updated filepaths to use relative paths for improved flexibility.
   6. Removed the "action" attribute from the `<form>` tag since form submission is handled by email.js.
   7. Removed the `type/text` attribute from the script tags for JavaScript resources.
   8. Set a valid value for the "cols" attribute of the `<textarea>` tag (cols="40").
   9. Removed html comments
   10. Changed the loading attribute to `lazy/eager`for select images.

5/9/23

- UPDATE: Favicon with headshot image.

- FINAL REVIEW #1: Resize ABOUT section links with colors.

5/8/23

- BRANCH: resize => ADJUST: Media queries for ABOUT, SPECIALTIES, & LINKS sections && REFORMAT `README.md`

5/4/23

- BRANCH: links => IMPROVE: LINKS links & ADD: link descriptions.

5/3/23

- INSERT: Psychology Today Badge in FOOTER && space SERVICES descriptions

- ALTER: Services, Specialties, && ADD: Insurances

5/2/23

- BRANCH: emailJs => FEAT: Integrate #contactForm w/ EmailJs && CREATE: `thanks.html` redirect

4/28/23

- ADD: section images && alter footer color scheme

4/27/23

- Color Pallete Update

4/26/23

- BRANCH: competencies => ADD: Specialties and Approach && ALTER: psychologytoday links

- BRANCH: footerExpansion => Expand FOOTER section to include contact section && Adjust media Queries for small screens

4/25/23

- BRANCH: faq => FEAT: Remove grid media querys for SERVICES section && Widen iFrame map embed.

4/24/23

- BRANCH: faq => FEAT: Integrate SERVICES section collapse toggle w/ javascript

4/17/23

- ADD: meta description tag

- ADD: Google Maps iFrame for stone soup counseling

3/23/23

- Eliminate Skills section and replace with Experience

- Reformat README.md commit log to bottom-up approach.

3/22/23

- Create and Style favicon && change download to contact scrollTo.

- Configure media query for screen > 1024px

- Configure media query for screen > 768px

- Integrate mainjs action for nav menu tray

- Update color pallete

3/21/23

- CREATE and STYLE Contact section.

- CREATE and STYLE Links section.

- INSERT icons/

- INSERT `images/howareyoureally-unsplash.jpg`

- INSERT images/988images/

- CREATE and STYLE Resources section.

- CREATE and STYLE Services section.

3/20/23

- CREATE and STYLE Education section.

- CREATE and STYLE Skills section.

- CREATE and STYLE About section.

3/19/23

- CREATE and STYLE Home section

3/16/23

- Stow Header tray to offset position

- Integrate Header + Nav Menu

- Link stylescss + main.js + boxicons CDN && Generate css  variables, media query for screen to 768px

- Set Base CSS + Reset CSS

- Init Commit

___

### Action Items

- Set alt tags for images

- Finalize Thanks page

- Adjust LINKS section grid size issues

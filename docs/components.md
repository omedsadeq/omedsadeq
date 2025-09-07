Components and Reusable Sections

Header Contact Bar

- Selector: `header.bg-primary`
- Purpose: Displays contact phone and email
- Usage: Include at top of page body

Navbar

- Selector: `nav.navbar.navbar-expand-lg.navbar-light.bg-light`
- Brand: `<img src="img/logo2.png" class="navbar-brand">`
- Links: `HOME`, `ABOUT US`, `SERVICE`, `DOCTORS`, `CONTACT US`
- Active link: add `active` to `li.nav-item`

Middle Section Container

- Selector: `.middle`
- Purpose: Wraps content blocks and images
- Notes: Has a bottom border and contains nested divs

Bottom Features Section (Home only)

- Selector: `.bottom`
- Purpose: Feature list describing lab capabilities

Appointment Form

- Location: `index.html`, `service.html`, `doctor.html`
- Fields: first name, last name, email, mobile, sex, appointment date, message
- Submit: `<button class="btn btn-primary">Submit</button>`
- Behavior: No client JS; handled by default browser submission

Doctor Profile Card

- Container: `.doctor-profile`
- Photo: `.doctor-photo` (150x150, circular)
- Info: `.doctor-info`, `.doctor-name`, `.doctor-title`

Footer

- Selector: `footer.bg-dark`
- Purpose: Site copyright

Images

- Directory: `img/`
- Referenced images: `logo2.png`, `r1.jpg`, `r2.jpg`, `r3.jpg`, `serv.jpg`, `d1.jpg`, `d2.jpg`, `d3.jpg`, `d4.jpg`, `bio.jpg`, `cov.png`, `kl.jpg`


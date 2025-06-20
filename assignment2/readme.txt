README - CSS Types and Selectors Used

1. Inline CSS:
- Used for setting background color on the profile card <div>.

2. Internal CSS (inside <style> tag in <head>):
- .bio class: used to color and style the bio text.
- #profile-pic ID: used to style the image size and shape.
- h1, h2 grouped: used to style headings.
- .profile-card class: used for box shadow and padding.
- .contact p (descendant selector): styles only p inside contact.
- a[href] (attribute selector): styles all links with href.
- a:hover (hover effect): changes link color when mouse is on it.

3. External CSS (style.css):
- Used for background of body and ul list.
- Also styled links inside .contact using descendant selector.

Selectors used:
- Element: h1, h2, ul, body
- ID: #profile-pic
- Class: .bio, .profile-card
- Group: h1, h2
- Descendant: .contact p, .contact a
- Attribute: a[href]

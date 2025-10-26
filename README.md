# mi349_blog

## Deploying this site on Netlify

Follow these steps to deploy and enable form submissions:

1. **Connect your GitHub repository to Netlify**
	- Go to [Netlify](https://app.netlify.com/) and sign up or log in.
	- Click "Add new site" > "Import an existing project".
	- Select GitHub and authorize Netlify to access your account.
	- Choose your `mi349_blog` repository and follow the prompts to deploy.

2. **Enable form detection**
	- Netlify automatically detects forms with the `data-netlify="true"` attribute in your HTML.
	- No extra configuration is needed if your form uses the correct attributes (see `contact.html`).

3. **Deploy your site and test form submission**
	- Once deployed, visit your site’s contact page.
	- Fill out and submit the form to test.
	- You should see your thank-you confirmation page after submission.

4. **Verify submissions in Netlify dashboard**
	- In Netlify, go to your site’s dashboard.
	- Click on "Forms" in the left sidebar.
	- You will see a list of form submissions, including those from your contact form.
	- You can view, filter, and export submissions as needed.

	## Responsive Design Lab

	This site includes a small responsive lab to demonstrate common responsive patterns used in the stylesheet:

	- Breakpoints used: 900px and 600px — layouts adapt at these widths (e.g., two-column -> single-column at 900px, tighter adjustments around 600px).
	- Images and media are fluid (they use `max-width: 100%`) so they scale to their container.
	- Multi-column layouts stack on narrow screens (columns collapse to a single column at the 900px breakpoint).
	- Forms are built to be touch-friendly: full-width fields, generous tap targets, and increased spacing for mobile.
	- Wide tables are horizontally scrollable so content remains readable on small screens (`overflow-x: auto` on table containers).

	Links

	- GitHub repository: https://github.com/phamphu3/mi349_blog
	- Deployed site (Netlify): https://your-site-name.netlify.app  <!-- replace with your actual Netlify URL -->

	If you'd like, I can update this file to include the real Netlify URL once you provide it or after a successful deploy.
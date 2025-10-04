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
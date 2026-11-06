# StrokeRehart website

Public website for the StrokeRehart research project and its Google Health API integration.

## Hosting

- GitHub Pages
- Custom domain: https://strokerehart.eu
- Repository: https://github.com/andreu-oliver/strokerehart-website

## Required public pages

- `/` — Project and application homepage
- `/privacy/` — Privacy policy covering Google Health data
- `/terms/` — Terms of service, if applicable
- `/contact/` — Contact details for the project/data controller
- `/data-deletion/` — Data deletion and withdrawal instructions

## Google Health compliance

The public homepage must identify the application and explain its functionality. It must link to an accessible privacy policy and disclose compliance with the applicable Google Health API policies, including Limited Use.

Health research also requires a separate Google Health research-policy submission and participant-facing disclosures/informed consent in the enrollment flow. The website does not replace those requirements.

Official policies:
- https://developers.google.com/health/policies/health-api-developer-user-data-policy
- https://developers.google.com/health/policies/health-api-user-data-and-research-policy
- https://developers.google.com/health/app-verification

## Deployment checklist

1. Enable GitHub Pages from the `main` branch.
2. Confirm `strokerehart.eu` is configured as the custom domain and HTTPS is enforced.
3. Verify ownership of the domain in Google Search Console / Google Cloud as required.
4. Publish the privacy policy and test that it is publicly accessible without login.
5. Ensure the privacy policy identifies the correct data controller, contact details, data categories, purposes, recipients/processors, retention, security, international transfers where relevant, participant rights, withdrawal and deletion procedure.
6. Ensure all public claims accurately match the deployed application and actual operational configuration.
7. Add the prominent, specific Google Health data disclosure and consent process inside the participant enrollment flow.
8. Complete the Google Health research intake and ethics documentation before using the API for human-subject research.

Do not publish placeholder contact details, retention periods, controller identities or security claims. Confirm each with the project owner and the actual deployment configuration first.

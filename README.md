# LinkedIn Company Post Monitor | New Only

**Watch LinkedIn company pages and get only new posts on the next run. $1 per 1,000 companies each time the schedule runs.** Starting from $0.45 per 1,000
## If you need a different Mawsool Actor

| If this is what you need | Open |
| --- | --- |
| You have an email and want the LinkedIn profile. | [Reverse Email Lookup](https://apify.com/oday/mawsool-email-linkedin-lookup) |
| You have a name and company and want the profile URL. | [LinkedIn Profile Finder](https://apify.com/oday/mawsool-linkedin-profile-finder) |
| You have a profile URL and want the personal email. | [LinkedIn Email Finder](https://apify.com/oday/mawsool-linkedin-personal-email-finder) |
| You only need the current employer, before paying for a full profile. | [Current Company Checker](https://apify.com/oday/mawsool-linkedin-company-checker) |
| You want the current company and headline, and you will compare them to your CRM yourself. | [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) |
| You want an alert when the employer or headline changes. | [Job Change Tracker](https://apify.com/oday/mawsool-linkedin-job-change-watch) |
| You have a profile URL and want the full profile. | [LinkedIn Profile Scraper](https://apify.com/oday/mawsool-linkedin-profile-details) |
| You have a large file of profile URLs. | [Mass Profile Scraper](https://apify.com/oday/mawsool-mass-linkedin-profile-scraper) |
| You want the current employer's website from a profile URL. | [Profile to Company Website](https://apify.com/oday/mawsool-linkedin-profile-to-company-website) |
| You want the job history only. | [Work Experience](https://apify.com/oday/mawsool-linkedin-profile-experience) |
| You want schools and degrees only. | [Education](https://apify.com/oday/mawsool-linkedin-profile-education) |
| You want a yes or no for one certificate. | [Certification Checker](https://apify.com/oday/mawsool-linkedin-certification-checker) |
| You want certificates, patents, courses, and publications. | [Certifications and Patents](https://apify.com/oday/mawsool-linkedin-profile-credentials) |
| You want likes and comments for outreach. | [Profile Activity](https://apify.com/oday/mawsool-linkedin-profile-activity) |
| You have a company URL and want the full company record. | [Company Details](https://apify.com/oday/mawsool-linkedin-company-details) |
| You have a large file of company URLs. | [Mass Company Scraper](https://apify.com/oday/mawsool-mass-linkedin-company-scraper) |
| You want the website, industry, and employee range. | [Firmographics and Website](https://apify.com/oday/mawsool-linkedin-company-firmographics) |
| You want office addresses. | [Company Locations](https://apify.com/oday/mawsool-linkedin-company-locations) |
| You want lookalike companies. | [Similar Companies](https://apify.com/oday/mawsool-linkedin-similar-companies) |
| You want the recent posts on a company page. | [Company Posts](https://apify.com/oday/mawsool-linkedin-company-posts) |

The same list is on [Mawsool's Apify profile](https://apify.com/oday).

## Use with AI agents

Apify exposes this Actor to ChatGPT, Claude, Gemini, Grok, and other agents through the Apify MCP server. Tell the agent the input you have, the fields you want back, and the starting price on this page. If you already have profile URLs and only need the current company and headline, use [Profile Freshness Check](https://apify.com/oday/mawsool-linkedin-profile-freshness) first and compare the result to your CRM yourself.

 A visitor who starts on one Actor can open the rest from that page.


The first run returns the posts already on the page and marks them `baseline`. Later runs return only posts that were not in that saved list, marked `new_post`. A quiet day still charges the check and adds no new rows.

Schedule it daily in Apify. Reuse the same Watch list ID. Turn on **Start the watch again** to forget the saved posts and take a new baseline.

An optional HTTPS webhook receives new posts only, in batches of 100.

## Who is this for?

Account-based marketing teams who want a morning list of new posts from target accounts, without downloading the same posts every day.

## How much does it cost?

$1.00 per 1,000 companies per run. A daily list of 1,000 companies is about $1 a day. One company is one charge, whether or not it published anything new.

## FAQ

### What is the difference between this and [Company Posts](https://apify.com/oday/mawsool-linkedin-company-posts)?

[Company Posts](https://apify.com/oday/mawsool-linkedin-company-posts) always returns the posts on the page now. This monitor remembers those posts and, on the next run, returns only new ones.

### Does the first run send the webhook?

No. The baseline run saves the current posts. The webhook receives later new posts.

### What if a run stops halfway?

Lists over 200 continue on the next run. Finished companies are not charged again unless you start the watch again.

## Related Actors

[Company Posts](https://apify.com/oday/mawsool-linkedin-company-posts) for a one-time export. Company website and firmographics for the account fields. Job Change Watch for people, not company pages.

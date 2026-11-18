# Local SEO Schema Templates

Copy-paste **JSON-LD structured data** templates for local businesses and freelancers. Replace the placeholder values, validate, and add them to your site.

| File | Use it for |
|---|---|
| [`local-business.json`](local-business.json) | Local service businesses with an address or service area (plumbers, cleaners, clinics, shops). Use a more specific type if one fits, e.g. `Plumber`, `Dentist`, `HomeAndConstructionBusiness`. |
| [`person.json`](person.json) | Freelancers and personal brand / portfolio sites. Helps search engines and AI assistants connect your name, website and profiles. |
| [`faq.json`](faq.json) | Pages with a visible FAQ section. |

## How to use

1. Copy a template and replace every placeholder value with real details.
2. Keep the information identical to your website and your **Google Business Profile** (name, address, phone).
3. Wrap it in a script tag:

   ```html
   <script type="application/ld+json">
   { ...your JSON... }
   </script>
   ```

4. Add it to the page:
   - **Rank Math**: Schema Generator > Import / custom schema (Pro), or
   - **Elementor**: an HTML widget on the page, or Elementor > Custom Code for site-wide schema.
5. Test with Google's [Rich Results Test](https://search.google.com/test/rich-results) and the [Schema Markup Validator](https://validator.schema.org/).

## Rules worth following

- Only mark up information that is **visible on the page**. FAQ questions and answers must match the page text.
- Don't add fake reviews or ratings. Self-serving review markup is not shown by Google.
- Use one `@id` per entity (e.g. `https://example.com/#business`) so other schema on the site can reference it.
- Remove fields you don't have instead of leaving placeholders.

## Author

**Saira Shakeel**, freelance web designer, local SEO and AI automation specialist  
[sairashakeel.com](https://sairashakeel.com/) · [LinkedIn](https://www.linkedin.com/in/sairashakeel/)

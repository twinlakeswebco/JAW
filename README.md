# JAW Creations

A static portfolio and custom-inquiry website for Jordan Williams, Jordan’s Artistic Whims.

Open `index.html` directly or serve this directory with any static web server. No build, package install, external font service, gallery API, or backend is required.

## Content and behavior

- Eight artwork examples with accessible medium filters. All work remains visible without JavaScript.
- Real client-provided images, optimized to WebP in `assets/`.
- Apparel imagery is explicitly labeled as digital mockups.
- Custom inquiries use email, telephone, and Jordan’s Facebook page. The main email action opens a prefilled draft in the visitor’s email app; it does not send or store anything.
- Self-hosted Rubik fonts; license in `assets/fonts/OFL.txt`.
- Responsive navigation, keyboard focus, reduced-motion support, social sharing metadata, and structured business data.

## Updating

Copy updates to `index.html` and `assets/` together. Gallery markup is in `#gallery`. Original supplied images are preserved in the project root; the page only loads optimized assets. `assets/*.origin.txt` records image provenance. The two original vintage-template images remain in the repository for history but are no longer referenced by the site.

The source story says “fourteen years ago,” quoting the supplied account. Confirm that relative date with Jordan when revising her biography in a later year. No prices, fulfillment policies, opening hours, or turnaround guarantees have been assumed.

## Local search and answer-friendly content

The homepage targets custom artwork and artist inquiries in Leitchfield, Kentucky, with Clarkson, Caneyville, and Grayson County as surrounding service areas. Relevant terms appear in the title, description, introductory copy, services, and a useful local FAQ rather than hidden keyword lists. Google does not use the keywords meta tag.

ProfessionalService structured data describes Jordan Williams, contact details, service areas, verified profile links, and a service catalog. FAQPage data exactly matches the five visible, expandable questions. This markup does not guarantee FAQ rich results, AI citations, rankings, or traffic. No address, hours, ratings, review counts, prices, or fixed turnaround times are fabricated.

Footer links: Facebook profile 61574271221137, Instagram @jawcreations, and the client-supplied Google Business Profile share link. Icons use inline SVG, accessible names, and 46px touch targets.

Before publishing on the final domain: confirm the preferred domain, then add its canonical URL, og:url, robots.txt and sitemap.xml; register it with Google Search Console and add the final website URL to the Google Business Profile. Do not use a temporary preview URL as the permanent canonical. The website is ready for deployment preparation; creating a Cloudflare Pages project is a separate step.

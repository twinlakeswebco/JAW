# JAW Creations review

## Repository findings addressed

The original homepage represented Blush & Brass Vintage rather than JAW Creations. Its remote gallery relied on a `data/gallery.json` file absent from this repository. The newsletter form displayed a success message without storing or sending the signup. Footer policy links were placeholders, and social/contact links belonged to the other business.

The replacement presents Jordan Williams and her supplied artwork, lists all requested creative mediums, identifies digital apparel mockups, and directs custom inquiries to Jordan’s supplied email, phone and Facebook page. Gallery content is inline and works without a gallery API. All artwork remains available without JavaScript.

## Checks completed

- HTML IDs, internal anchors, accessible section names and local asset references.
- Image alternative text and intrinsic dimensions.
- Eight gallery examples, including five explicitly identified apparel mockups.
- JavaScript syntax and structured business data parsing.
- Defined text/background pairs meet 4.5:1; checked combinations range from 5.88:1 to 9.56:1.
- Independent source review: ship at source-only scope, no material source defects identified.

## Verification limits

Rendered desktop/mobile layout and interactive browser behavior remain unverified. Headless browser launch was denied by the operating-system sandbox, and the browser preview blocked local file URLs. Source review does not establish that cropping, layout, keyboard navigation or interactions render correctly on a device. Review desktop and mobile previews before a production launch.

## Content assumptions

The “fourteen years ago” wording reflects Jordan’s supplied story, not an independently verified founding date. No prices, stock status, fulfillment policies, operating hours or turnaround guarantees were invented. The email action prepares a draft in the visitor’s mail app; it neither sends nor stores an inquiry.

## Local search and social profiles update

Added a Leitchfield-focused title, description and introductory copy; explicit Clarkson, Caneyville and Grayson County service-area content; more descriptive creative services; five native, expandable commission FAQs; and matching ProfessionalService/OfferCatalog/FAQPage structured data. No business address, opening hours, ratings or fixed prices were assumed.

Added accessible inline SVG links for Facebook, Instagram @jawcreations, and the supplied Google profile. The Google share link resolves to a JAW Creations search entity; Instagram search results show the matching brand, embroidery/illustration bio and Alice Theatre artwork.

Checks passed: all three footer destinations/accessible names, five exact visible FAQ-to-schema matches, service areas, image and internal-anchor references, unchanged eight-piece gallery, JavaScript syntax, title/description lengths, and git whitespace validation. The existing color/type advisory findings are outside this scoped content update; new UI uses the existing palette, focus rings and responsive breakpoint. Browser runtime installation failed due to a truncated download, so no new rendered desktop/mobile pass was completed locally.

Final-domain canonical, og:url and sitemap remain deployment tasks. FAQ markup is descriptive and does not promise Google FAQ rich results or AI/search placement.

## Asset organization and supplied photo placement

All 32 image files now live in `assets/` with short descriptive filenames. Original uploads use `.jpg`; matching optimized copies use `.webp`. References in HTML, sharing metadata, documentation and provenance sidecars were updated together. The 25 moved image files retain their original SHA-256 hashes. The concurrent upstream deletion of the unrelated template portrait is preserved; no supplied JAW image was removed.

Jordan’s supplied portrait now appears alongside “Hi, I’m Jordan.” The official supplied logo is visible in the header and footer. The two added storefront paintings and the doodle portrait collage extend the gallery to 11 projects, with the existing filter controls retained. New web images have optimized derivatives, intrinsic dimensions and accessible image/link labels. The fabric banner uses containment so its full lettering is visible.

Validation passed for all image paths, descriptive filenames, preserved original hashes, image dimensions, sharing/schema image URLs, gallery category counts, and JavaScript syntax. An independent review inspected the supplied photos and final source and returned ship at source-review scope with no material issues. Browser capture remains unavailable in this execution environment; rendered desktop/mobile layout and interactions are not certified by this review.

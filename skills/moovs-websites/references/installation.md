# Install booking on a website

Reviewed 2026-10-15; three-option and GoDaddy procedures rechecked 2026-10-16.
Follow task-authority.md for editing/saving and exact publication approval. Inspect the
intended site/plan/permissions first; take no action on an unrelated website.
Agree whether this is preview-only, a saved edit or a published installation.
Do not require publication, Moovs Test or a booking submission for preview-only work.

## Choose link, widget or generated iFrame

In Operator, open **Settings > Customer Portal > Installation & Share**.

- **Customer Portal Link:** use **Copy Link** for the general booking URL or
  **Open Link** to preview its standalone Moovs-hosted booking page. Use that link
  as a button's destination; check the intended company before publishing.
- **Customer Portal Widget:** choose Book Now or Get a Quote, then **Copy code**.
  This floating button opens booking without sending visitors to a separate page.
  The operator pastes the generated snippet into the builder's documented custom
  HTML/code area, saves/publishes deliberately, and uses Moovs **Test** plus the
  real public page to verify placement. A site-wide header is an option only for
  an agreed all-pages placement supported by the builder, not a single-page requirement.
- **Customer Portal iFrame:** supply the intended website URL and copy the
  Moovs-generated code. This places the form inline. The operator inserts it into
  the intended page, checks
  responsive layout, then publishes and verifies. Do not manufacture an iframe
  pointing at the ordinary portal URL.

The current [three-option guide](https://intercom.help/moovs-05c940f1970e/en/articles/6650028-how-to-add-moovs-to-your-website)
specifically distinguishes supported generated embeds from manual portal wrapping.
Prefer it over broader older examples in the
[legacy iFrame guide](https://intercom.help/moovs-05c940f1970e/en/articles/8541577-how-to-add-the-customer-portal-iframe-to-your-moovs-website).
Never copy example company URLs from documentation into a real installation.

## Builder-specific guidance

This is routing, not one completed installation across every builder. Choose the
intended platform's task below; GoDaddy uses a link, not the widget.
Fetch the relevant guide if controls differ. Do not modify a live theme, site-wide
header/footer or existing scripts just to experiment. Keep a recoverable copy of
the operator's existing configuration before they edit; do not store it publicly.

[General widget guide](https://intercom.help/moovs-05c940f1970e/en/articles/8549265-add-the-customer-portal-widget-to-your-website).

## Link a GoDaddy action button to the Customer Portal

1. Copy the intended company's **Customer Portal Link** from **Settings >
   Customer Portal > Installation & Share**; do not use widget code here.
2. In GoDaddy **Websites + Marketing > Manage > Edit Website**, open the intended
   action-button section, or operator adds a suitable section if none exists.
   Do not add a section when an existing one works. Select the button, enable **Show Action Button** if
   needed, and use clear button text. For **Link to**, choose **Website URL**.
3. Operator pastes the portal link. GoDaddy auto-saves editor changes: this is an
   edit, not a non-mutating preview. Preview the button and confirm its company.
4. Only for an approved public update, operator publishes; reopen the public
   page and check the button destination. Editor auto-save alone is not public.

If the Moovs portal link itself fails, the operator uses **? > Moovs Support**.
GoDaddy Support handles its website editor/publication problems. Distinguish a
broken destination from a button/site problem before preparing an inquiry; do
not send it or republish/change DNS merely to discover which team owns it.

[GoDaddy guide](https://intercom.help/moovs-05c940f1970e/en/articles/8590289-add-your-moovs-customer-portal-link-to-a-godaddy-website).

## Install the widget in WordPress

1. Operator opens the intended site from its WordPress dashboard, then
   **Customize > Footer HTML code** in the documented example. Themes can differ.
2. Review the intended company's Moovs-generated widget code and existing footer
   content before operator insertion and **Save changes**; preserve other code.
3. Reopen the saved footer configuration. For an authorized live installation,
   use Moovs **Test** and inspect the public site's widget/company. If the actual
   editor requires publication, operator decides it separately; do not guess.

[WordPress guide](https://intercom.help/moovs-05c940f1970e/en/articles/8590276-how-to-add-the-customer-portal-widget-to-your-wordpress-website).

## Install the widget in Webflow

1. Open the intended site's **Settings** from the dashboard three-dot menu, or
   **Site Settings** from its designer. Open **Custom Code > Footer Code**.
2. Operator inserts the intended company's generated widget code without
   replacing unrelated code, then saves. Reopen to compare the saved placement.
3. Only when publication is requested, operator selects **Publish**. Inspect the
   public site and use Moovs **Test**; a saved footer is not a published widget.

[Webflow guide](https://intercom.help/moovs-05c940f1970e/en/articles/8590287-how-to-add-the-customer-portal-widget-to-your-webflow-website).

## Install the widget in Wix

1. Open the intended website dashboard's **Settings > Custom code > Add Custom
   Code**. If the editor differs, consult the current guide rather than guessing.
2. Operator pastes the intended company's generated snippet in **Paste the code
   snippet here**, chooses **Place Code in > Body - start**, then **Apply**.
3. Treat Apply as a consequential change, not a harmless preview. Reopen the
   saved code/placement and inspect the site's widget/company; for an authorized
   live installation use Moovs **Test**. Do not invent an additional publish step.

[Wix guide](https://intercom.help/moovs-05c940f1970e/en/articles/8590291-how-to-add-the-customer-portal-widget-to-your-wix-website).

## Install the widget in Squarespace

1. The published example uses **Website > Edit > Home > Advanced** and its code
   block. Follow the current guide if the operator's editor differs.
2. Operator inserts the intended company's generated code, selects **Save** in
   the code area, then **Save** in the website editor; preserve unrelated content.
3. Reopen the saved placement. For an authorized live installation, inspect the
   public widget/company and use Moovs **Test**. Do not infer public availability
   solely from a code save or invent a universal separate publish control.

[Squarespace guide](https://intercom.help/moovs-05c940f1970e/en/articles/8590292-how-to-add-the-customer-portal-widget-to-your-squarespace-website).

## Install the widget in Shopify

1. Open **Online Store > Themes > Customize** for the intended theme. Use its
   supported **Add Section/Add Content > Custom HTML/Custom Content** option.
2. Operator pastes the intended company's generated widget code and saves.
   Reopen the saved section and preview layout/company without submitting a trip.
3. Only when a public update is requested, operator publishes. Inspect the public
   widget/company and use Moovs **Test**; preview is not evidence of publication.

[Shopify guide](https://intercom.help/moovs-05c940f1970e/en/articles/8590294-how-to-add-the-customer-portal-widget-to-your-shopify-website).

## Booking widget colors

[Pricing](https://www.moovsapp.com/pricing) names custom booking widget colors.
The reviewed installation articles establish generated embeds, not the exact
color editor, save behavior or whether an already-installed snippet updates.
Portal logo/banner branding is not proof of widget-color propagation.
Confirm whether the intended change is the floating button or booking form,
approved colors, account access and affected site pages. Read current public Help
or obtain supported instructions before operator editing; do not inject CSS,
rewrite generated code or republish a theme to guess. After a supported change,
compare saved configuration and the intended public desktop/mobile appearance.
Keep editor save, site publication and visible visitor result separate.

## Readback

For preview-only work, verify only the intended preview and report it as such.
After an approved public update, verify the public page, intended company,
correct booking entry point and mobile layout. If a template has several booking
buttons, review every affected button.
An editor preview, successful code paste or Moovs test alone is not proof the live
visitor journey works. No real booking submission is authorized by installation.

---
title: Guide
nav: Guide
gallery: true
---

<br>

{% include feature/nav-menu.html sections="Getting Started;Run the Accessibility Check;Remediation Workflow;Auto Tag;Reading Order;Set the Document Language;Set the Document Title;Decorative Text vs. Alt Text;Add Alt Text;Check Lists;Check Tables;Check Hyperlinks;Verify Header Order is Sequential;Final Verification and Saving;Run the Accessibility Check Again;Save the File" %}

<br>

## Getting Started

*   Open your PDF in Adobe Acrobat Pro (the free Reader version does not have these capabilities).
*   Go to the menu bar on the side of the screen and select `Prepare for Accessibility`

{% include gallery-figure.html img="remed_pdf_19.jpg" alt="A screenshot from a digital document displaying an article titled `RangeDocs: searchable science for rangeland management` by multiple authors. The left sidebar shows a list of document tools such as `Prepare for accessibility,` `Export a PDF,` and `Edit a PDF.` An article menu is open with details about the web application `RangeDocs,` including a URL. The article discusses rangeland management and features a list of points under `On the Ground.` On the right side, there is a panel labeled `Accessibility tags` listing various tags such as <H3>, <Figure>, and <P>." caption="Prepare for Accessibility on the left panel" width="100%" %}

<br>

### Run the Accessibility Check

This is your starting point. The checker will scan the document and generate a report of errors, warnings, and tips.

*   In the `Prepare for Accessibility` panel on the left, select `Check for Accessibility`
*   It gives you the option to save reports, but they are relatively quick to generate and you will be running it more than once, so I would uncheck this box

{% include gallery-figure.html img="remed_pdf_03.jpg" alt="A digital document is open in a PDF viewer. The article is titled `Research and Partnership Highlights` with a focus on `Rangeland` by Amber Dalke and Sean Di Stefano. An `Accessibility Checker Options` dialog is open, showing various checked boxes related to document accessibility, such as `Document is tagged PDF` and `Document title is showing in title bar.` The right panel lists `Accessibility tags.` There are menu options along the top and bookmarks visible on the left." caption="Check for accessibility and uncheck report function" width="100%" %}

*   Select `Start Checking` and results will generate on the right panel

<br>

## Remediation Workflow

If your check generated some failures (represented by a red x mark in the accessibility panel), the most frequent culprits will be the lack of a tagging structure and lack of alt text for images within the document. 

{% include gallery-figure.html img="remed_pdf_04.jpg" alt="A computer screen displaying a document titled `RangeDocs: searchable science for rangeland management` by several authors. It includes text about rangeland management tools and systems. To the right, an accessibility checker panel lists various accessibility checks, indicating both passed and failed elements, such as `Tagged annotations - Failed` and `Figures alternate text - Failed.` The panel offers options for preparing the document for accessibility." caption="Accessibility checker output and failures" width="100%" %}


The **tagging structure** informs your PDF reader application how a document is meant to be read and in what order. **Alt text** is a short, simple description of the contents of an image. While a caption below an image describes what is not visible, such as the names of the people, the location and date of the image, alt text describes only what is visible. 

> Here is an example of alt text for this image: 
{% include gallery-figure.html img="remed_pdf_15.jpg" alt="Text on a page with the title `Choosing Pear Rootstocks for the Pacific Northwest` and a subtitle indicating reprinting in January 1995. An image shows a snow-capped mountain across a grassy valley, partially obscured by a conifer tree limb. Text below the image describes the Hood River Valley as a major pear-producing region, emphasizing climate and soil type considerations. An open dialog box shows object properties, including image description and details." caption="Alt text example" width="100%" %}
>
> "A large, snow capped mountain seen from across a grassy valley and immediately behind a conifer tree limb."

<br>

### Auto Tag

<br>

{% include gallery-figure.html img="remed_pdf_01.jpg" alt="A document titled `RangeDocs: searchable science for rangeland management` by several authors including Amber Dalke and Jason W. Karl. It features an introduction about RangeDocs, a web application aimed at helping professionals search and manage rangeland resources efficiently. A section labeled `On the Ground` lists features like a glossary, technical resource annotations, and web application capabilities. Keywords include SRM glossary, terminology, and National Range and Pasture Handbook. An accessibility tools menu is visible on the left side." caption="Automatically Tag PDF location in the accessibility panel" width="100%" %}

<br>

*   In the `Prepare for Accessibility` tools panel, click `Automatically Tag PDF`. After this runs (takes about 1-5 minutes), it will display Accessibility tags, displaying the order of items as they display on the page.

{% include gallery-figure.html img="remed_pdf_05.jpg" alt="A document titled `RangeDocs: Searchable Science for Rangeland Management` by multiple authors is displayed. It is an article in press with the Society for Range Management logo. A section labeled `On the Ground` describes the RangeDocs application and its features, including a glossary and technical resources. Keywords listed include `SRM glossary` and `information exchange.` On the side, there is a panel showing accessibility tags for various document elements." caption="Tag panel" width="100%" %}

{% include feature/alert.html text="**Note**: the easiest way to navigate and expand the tag field is using your arrow keys. Up and down goes directionally through the tags and left and right expands or collapses content." color="light" align="left" %}

*   **It would be great** if you could search through the tags and filter according to type so you could look at say, just your figures, tables or lists that are frequently the culprits of accessibility issues, but selecting the ellipses on the Accessibility Tags panel and selecting Find looks instead for an obscure set of terms…

<br>

> The next three steps should have been completed by the Auto Tag process, but just in case…

<br>

### Reading Order

{% include gallery-figure.html img="remed_pdf_06.jpg" alt="A document titled `RangeDocs: searchable science for rangeland management` by Amber Dalke and others is displayed. The article is part of the `Research and Partnership Highlights` series. Text outlines the benefits of RangeDocs, including a rangeland-specific glossary and tools for accessing relevant information. The document also includes navigation and table of contents features on the side." caption="Reading order panel" width="100%" %}

*   If anything needs correcting, select the `Fix Reading Order` tool on the left panel. This will open a window. Select `Show Reading Order`, which will open on the right pane with all of the sections. **Drag the section’s box icon up or down to reorder as needed.**

{% include gallery-figure.html img="remed_pdf_20.jpg" alt="A document titled `Cultivating relationships for Indigenous futures: developing a model for university, Tribe, and Land partnerships in educator professional development` is displayed. It lists several authors from the Cultivating Relationships Collaborative. The abstract outlines efforts to integrate Indigenous knowledge and science in education. Keywords include decolonial praxis and Indigenous knowledge integration. The document has various annotations, including an accessibility checker on the right showing completed and skipped checks." caption="Window for the Fix Reading Order function" width="100%" %}

*   If _everything_ needs correcting, select `Clear Page Structure`. Then draw boxes around each page element in the order they need to be read, selecting what text type they are (Header 1, Header 2, Body Text, etc.) as you order elements.

<br>

### Set the Document Language

Without a language set, a screen reader cannot pronounce words correctly.

{% include gallery-figure.html img="remed_pdf_08.jpg" alt="A document window with a dialog box in front showing `Document Properties.` The dialog box contains various settings such as `PDF Settings,` `Accessibility,` and `Reading Options.` The `Binding` option is set to `Left Edge,` and the `Language` is set to `English.` There is an arrow pointing to the `Language` option. In the background, a document titled `Research and Partnership Highlights` with authors listed as Amber Dady, Sean Di Stefano, and others is partially visible. The right side has an `Order` panel with a list of document sections and keywords." caption="Setting document language metadata" width="100%" %}

*   Go to `File` > `Document Properties`
*   Select the `Advanced` tab
*   Under the `Reading Options` section, select the correct language from the Language dropdown menu (e.g., "English (US)")
*   Click `OK` to save

<br>

### Set the Document Title

Screen readers should announce a document's title, not its filename.

{% include gallery-figure.html img="remed_pdf_07.jpg" alt="An application window displaying document properties. The properties include details such as the file name, title, authors, subject, keywords, creation and modification dates, and application used. The title is `RangeDocs: searchable science for rangeland management.` Authors listed are Amber Dalke, Jason W. Karl, and others. The subject is `Rangelands, Corrected proof.` Keywords include `SRM glossary` and `National Range and Pasture Handbook.` The application is `Elsevier.` The background shows a PDF document with text about research and rangeland management." caption="Setting document title metadata" width="100%" %}

*   Go to `File` > `Properties`.
*   Select the `Description` tab.
*   Enter a descriptive title in the Title field if this is missing.
*   Click `OK`

<br>

## Decorative Text vs. Alt Text

Images must have alternative text that describes their content for screen reader users. “Figures” in a document can also be identified as decorative text. 

{% include gallery-figure.html img="remed_pdf_21.jpg" alt="A document about chickpeas with one decorative icon in the top left corner." caption="Example of a decorative text within a PDF document" width="100%" %}

> Ask these questions to determine if a figure is decorative text:

*   Is the image purely for visual styling? (e.g., a border, a background texture, a corner flourish)
*   Does it not contain any text or critical information?
*   If you removed the image, would the user lose any understanding of the content on the page?
*   Is it not a link or a button? (If it's clickable, it's functional, not decorative)

<br>

## Add Alt Text

*   First, select `Add Alternate Text` from the `Prepare for Accessibility` pane on the left. This will open a window that will allow you to add alt text to only the areas that have been identified by the Auto Tag process.

{% include gallery-figure.html img="remed_pdf_09.jpg" alt="A digital screen showing a document editing interface with a sidebar menu for accessibility options. The main text is titled `RangeDocs: searchable science for rangeland management` and authored by several individuals. A pop-up window labeled `Set Alternate Text` includes a description “SRM logo with an icon of a person on a horse.” There are sections numbered with text beneath each. A file structure is visible on the right, listing various headers like `ARTICLE IN PRESS` and `On the Ground.` An arrow points to the feature `Add alternate text` in the sidebar." caption="Adding alt text within the Add Alternate Text function" width="100%" %}

*   If the image has been identified correctly, describe it simply in one or two sentences, being sure to add any words that may be incorporated in the image.
*   If the element is a decorative image, mark this box instead of adding alt text. This designation will add code so the element is skipped over by the screen reader
*   If an element has been identified as a feature incorrectly, open the accessibility tags section on the right pane, find that section, right click and select `Properties` from the bottom of the window. Select the dropdown next to the Type section and find the appropriate type and close the panel to save.

{% include gallery-figure.html img="remed_pdf_22.jpg" alt="A document titled `Cultivating relationships for Indigenous futures: developing a model for university, Tribe, and Land partnerships in educator professional development` is displayed. It lists several authors from the Cultivating Relationships Collaborative. The abstract outlines efforts to integrate Indigenous knowledge and science in education. Keywords include decolonial praxis and Indigenous knowledge integration. The document has various annotations, including an accessibility checker on the right showing completed and skipped checks." caption="Changing an element type manually through the tag panel. This is also a way you can add alt text" width="100%" %}

*   Alternately, the Auto Tag function might identify a little bit of noise or distortion on the page as a figure. If this is the case, go to the Tag panel, select this item from the list, right click and select `Delete Tag`.

{% include gallery-figure.html img="remed_pdf_16.jpg" alt="A document titled `Choosing Pear Rootstocks for the Pacific Northwest` by R. Stebbins, reprinted January 1995, with the code PNW 341. The text begins with a discussion on the importance of choosing the right rootstock for a new pear orchard. An image shows a landscape with a mountain in the background. There is a list of key questions to consider when choosing pear rootstocks." caption="Example of the Auto Tag function misidentifying noise on the page as a figure." width="100%" %}

<br>

> Next, let's check lists, tables and hyperlinks:

<br>

### Check Lists:

*   Find the list content in the Tags panel. It should be tagged as `<L>` (List), with `<LI>` (List Item) tags inside.
*   If it's not tagged correctly, select the list content on the page with the Selection tool.
*   Right-click the tag where you want the list to go in the Tags panel and select Create Tag from Selection. Choose `<L>` as the tag type.

<br>

### Check Tables:

*   Find the table in the Tags panel. It should be tagged as `<Table>`, with `<TR>` (Table Row), `<TH>` (Header Cell), and `<TD>` (Data Cell) tags inside.
*   The most critical part is identifying header cells. Right-click a cell tag (`<TD>`) and select Properties. Go to the Table Header tab and choose if it is a row or column header. This changes the tag to `<TH>`.
*   If a table is not tagged at all, use the `Fix Reading Order` tool to draw a box around the table and select "Table" from the dialog. Then, go into the Tags panel to define the headers as described above.

<br>

## Check Hyperlinks

Links need to be descriptive. **A link that reads "Click Here" is not accessible.**

{% include gallery-figure.html img="remed_pdf_23.jpg" alt="A document titled `RangeDocs: searchable science for rangeland management` by Amber Dalke and others is displayed. The article is part of the `Research and Partnership Highlights` series. Text outlines the benefits of RangeDocs, including a rangeland-specific glossary and tools for accessing relevant information. The document also includes navigation and table of contents features on the side." caption="Example of how a link is nested in the tag structure. In this case, the link is descriptive because it is plainly showing the URL the hyperlink will lead to." width="100%" %}

*   In the Tags panel, find a `<Link>` tag.
*   The text inside the `<Link>` tag should be descriptive (e.g., "DOJ Final Rule on ADA Accessibility").

{% include feature/alert.html text="**Note**: There is a little discrepancy here on what is recommended remediation and best practice. Recommended remediation is that, if the linked text is not descriptive, you actually use the Edit Text and Images function to visibly change the text in the document. I don't think we want to be taking this liberty with faculty PDF files. Just changing the descriptions within the link tags seems sufficient." color="light" align="left" %}

<br>

## Verify Header Order is Sequential

*   Return to the Accessibility Tags pane on the right and look over header material. Make sure Headers are stepping down sequentially (<H1>, <H2>, <H3>, etc.) and not skipping a number. 

{% include gallery-figure.html img="remed_pdf_11.jpg" alt="A document is open on a computer screen showing a table titled `Table 1` and contains a list with `Publisher Type` and the number of documents added to `RangeDocs.` The right side features a panel labeled `Accessibility tags` with a list of tags such as `<document>` and `<H1>,` each with a small icon and some arrows pointing to specific tags. Text in the document discusses glossary development related to RangeDocs. Menu options on the left include `Prepare for accessibility,` `Change reading options,` and various tools." caption="Checking for sequential headers within the tag panel" width="100%" %}

> **When in doubt**, just designate an element as a paragraph rather than using elaborate header structures.

<br>

## Final Verification and Saving

Once you believe you have fixed all the issues, you must verify your work and save the file correctly.

<br>

### Run the Accessibility Check Again

*   Go back to the `Check for Accessibility` function and run the tool
*   If anything still comes up, expand the issue and it will make all of the culprits visible
*   Depending on the issue, you may see the option to fix the item if it is a metadata correction that can be done automatically
*   If not, right click and select see in accessibility tags to resolve the individual issue

{% include gallery-figure.html img="remed_pdf_10.jpg" alt="A document titled `Glossary development` with text discussing RangeDocs and glossary terms for rangeland management. On the left, there is a section labeled `Table 1` with a list of publisher types and the number of documents added to RangeDocs. On the right, there is an `Accessibility Checker` sidebar showing various items, such as `Logical Reading Order` and `Color contrast,` marked with arrows indicating they need manual checks." caption="Example of 'issues', rather than 'failures', in the Accessibility Checker, as well as 'manual checks'." width="100%" %}

*   **Note: Some of the final elements that are flagged are “issues” not failures**. This is an odd feature of Acrobat where some items that are nonessential need to be skipped rather than these items not being flagged in the first place. Additionally, there are items that will be flagged as “needing a manual check” that are also nonessential.
*   Repeat as needed!

<br>

### Save the File

How you save is important to preserve your accessibility work.

{% include gallery-figure.html img="remed_pdf_17.jpg" alt="Adobe Acrobat window titled `PDF Optimizer.` It includes settings for images, fonts, transparency, discard objects, discard user data, and clean up. Image settings have options for color, grayscale, and monochrome images with different resolutions and compression types. On the right, there is an `Accessibility Checker` panel with various checked items. A red arrow points to a dropdown menu labeled `Settings: Standard.` Text from a document is visible in the background." caption="PDF Optimizer set to Standard." width="100%" %}

*   Go to `File` > `Save As Other` > `Optimized PDF`, making sure the settings are on standard (should be default)
*   Click OK

<br>

<div style="width:100%; text-align:center;">

  <div role="img" aria-label="ASCII art of a lil’ PDF feller — a smiling, anthropomorphic sheet of paper with arms and legs, looking proud of being accessible." style="background-color:white; padding:20px; border-radius:12px; display:inline-block; text-align:center; box-shadow:0 2px 6px rgba(0,0,0,0.1);">

  <pre style="font-family: monospace; line-height: 1.1em; font-size: 14px; background-color:white; margin: 0 auto; display:inline-block; text-align:left;">
       ________
     /         \
    |    PDF    |  
    |   -----   |  
    |  ( •‿• )  |  
    |    | |    |  
     \_________/   
        /   \       
       /_____\      
        |   |       
       (b) (b)     
  </pre>

  <p><b>That's it! Enjoy your accessible PDF file!</b></p>

  </div>

</div>

<br>

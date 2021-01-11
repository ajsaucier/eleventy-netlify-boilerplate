---
title: PDFs with Fillable Forms
permalink: "/training/creating-accessible-content/pdfs-fillable-forms/index.html"
tags: training
eleventyNavigation:
  key: PDFs with Fillable Forms
  parent: Creating Accessible Content
  order: 3

---
While digital publishing programs like Adobe InDesign can export a reasonably accessible PDF document, that PDF is usually not actually usable by people with disabilities. PDF documents need tagged content to be perceivable to assistive technologies, but relying on tags and reading order to be created in an automated process will not offer a fully usable solution. It’s necessary for a human to test the document and make sure it works with assistive technology. This guide is assuming that the PDF has already been created and exported to a PDF, and that the design of the document itself is already accessible – for example, there is sufficient color contrast between the text and the background of the document. The design and color palette of a document needs to be edited in the original program and not in Adobe Acrobat.

Fillable forms are just one type of PDF document that needs to be fully accessible. Users can interact with the form using a mouse, keyboard, voice recognition software, assistive technologies like screen readers and Braille displays, and many other types of input. Getting the basics right and making sure a form is properly tagged and the reading order is correct can go a long way to making it as accessible as possible.

It’s usually a good idea to use the Accessibility Tool’s Autotag Document option as the first step to making a PDF more accessible. Unless you’re confident that it was exported from InDesign with all tags intact and accurate, the Autotag Document tool might make for a better starting point. However, running the Autotag Document tool sometimes causes the PDF’s layers to overlap one another, making some text difficult or impossible to read. If that happens, you’ll need to revert to the previous version of the file by going to the File option at the top of the program, followed by the Revert option. When that happens, you’ll need to manually change the tags that were exported from the original program.

**Note:** Instead of making a fillable form as a PDF, consider using [Microsoft Forms](/training/creating-accessible-content/microsoft-forms/) instead. It's a more accessible option in many ways, including not requiring the user to download a file, allowing the user to easily complete the form on a mobile device, and using HTML instead of the inherently less accessible PDF format.

## Add Accessibility Tool to Acrobat

Adding the Accessibility Tool is helpful and makes it easier to access the tools that you might need. To do this, first go the Tools tab at the top of the Acrobat window. Then, under the Protect & Standardize heading on the Tools page, click on the Add button below the Accessibility icon. Finally, click the Add Shortcut option in the select box.

![](/static/img/add-tools.png)

## Adding Missing Tags

It’s common for the fillable fields to not have any tags when exported from InDesign.

Newly created tags will show underneath your previously selected tag in the left Tags panel. It’s a good idea to select an existing tag in that panel – for example, a <P>, <Art> or <Sect> tag – so you know where to find these newly added tags later in the process, when you need to drag them to the appropriate area.

To add tags to all these missing elements, first click the Tags icon in the left toolbar (its icon is a tag). Then, click on the Options icon and, finally, the “Find...” option in the popup window.

Whenever you are using the Tags panel, make sure to have the “Highlight Content” option turned on (a checkmark icon should show to the left of the option). This will make clear which tag you selected by highlighting the associated content in the document itself.

![Screenshot showing the Tags icon in the left toolbar of Adobe Acrobat DC, with the relevent menu options surrounded with a red border - the Tags icon, the associated Options icon and the Find... option.](/static/img/find-tag-from-selection.png)

In the next popup window, choose “Unmarked Annotations” in the select menu and click the “Find” button. If any untagged form fields are present in the current page (or the whole document, depending on what option you chose), Acrobat will highlight the element and move the window’s focus to that element. Click the “Tag Element” button when it becomes enabled. Repeat this process until an alert appears that says “Find Completed”.

![Screenshot showing the Find Element popup window, with the option Unmarked Annotations selected](/static/img/find-unmarked-annotations.png)

## Manually Adding Tags

It is sometimes necessary to add tags manually - if, for example, multiple separate sections of text were exported from InDesign as a single tag.

To manually tag elements in the PDF, first add the tag in the appropriate place in the Tags panel on the left side of Acrobat. The best way to do this is to find the existing tag that you would like the new tag to appear underneath. Right-click on the existing tag and choose the “New Tag...” option. A popup window will appear, where you can choose the type of tag you’d like to add. You can leave the Title field empty.

![Screenshot showing the New Tag popup window with a select menu for the Type of tag to be added and the Title. Cancel and OK buttons are below the fields.](/static/img/new-paragraph-tag.png)
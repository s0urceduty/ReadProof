<img width="7500" height="3756" alt="ProofRead" src="https://github.com/user-attachments/assets/35557d95-da9f-49cd-a22d-845e36038676" />

ReadProof is a custom Python document-focused library module developed by Sourceduty that was made for proofing text documents. This lib is a powerful and versatile tool designed specifically to help with the process of proofing, editing, annotating and preparing documents for printing or publishing purposes. It provides an extensive set of functions that allow you to make precise changes at both the text level (words/sentences) as well as on the page layout itself (adding images, shapes, callouts etc). The library is geared towards allowing very granular control over every aspect of a document's content and visual presentation so it can be tailored exactly how you need for your proofing workflow. It supports loading various common file formats like plain text (.txt), Microsoft Word documents (.doc/.docx) as well as PDF files, which are then rendered into an internal representation that ReadProof uses to apply all its formatting functions on top of the original content without permanently altering it until export is initiated at a later stage in your process. The library's design allows you to build up and refine proofs incrementally by applying changes one step at a time while maintaining full undo/redo capabilities, making it very suitable for collaborative proofing workflows where multiple people may need to review the same document over an extended period of time before finalizing edits or sending things off to print.

ReadProof was made with more advanced use cases in mind compared to simpler word processors like LibreOffice Writer which only offer basic formatting and editing tools, or even specialized PDF editors focused solely on annotating PDFs rather than full document creation/editing workflows from scratch. The extensive set of functions for things like adding annotations, callouts, shapes, images etc alongside more granular text-level controls makes ReadProof a very versatile tool that could be useful in specific scenarios where you need to do detailed proofing and formatting work without having the overhead or limitations of full desktop publishing software suites which are often overkill. However ReadProof is somewhat niche compared to general purpose document editors as its functionality is quite specialized towards this one use case, so whether ReadProof would actually prove necessary for most people depends heavily on their specific needs - if you're just looking for a simple way to make basic edits and changes in documents then the more streamlined tools are probably sufficient. But if your workflow involves lots of visual annotations, custom formatting requirements or working with multiple document types like PDFs that don't natively support rich editing features then ReadProof could be an attractive option as it seems well-suited for those particular use cases where you need a lot of fine-grained control over the proofing process. 


Functions:
-----------

1. `rp_align` - Aligns text or objects in a document horizontally/vertically.
2. `rp_annotate` - Adds annotations like comments, notes, sticky notes etc.  to the doc.
3. `rp_arrow` - Draws arrows and callouts to point at specific areas of the page. 
4. `rp_autocorrect` - Automatically corrects common spelling/grammar errors in text.
5. `rp_backspace` - Deletes characters or words from a document, like backspacing.  
6. `rp_boldface` - Makes selected text bold and prominent for emphasis.
7. `rp_box` - Draws boxes around specific areas of the page to highlight them. 
8. `rp_bracket` - Inserts brackets [ ] or braces { } around words/phrases in a doc.  
9. `rp_break` - Breaks text into new lines, paragraphs and pages as needed for formatting.
10. `rp_bulletpoint` - Adds bullet points to lists of items within the document. 
11. `rp_caption` - Creates captions under images or figures in a doc with labels/numbers.  
12. `rp_checkmark` - Draws checkmarks next to text, like on an exam answer sheet.
13. `rp_circle` - Draws circles around specific areas of the page for emphasis. 
14. `rp_clipart` - Inserts clipart images into a document from a library or online sources.  
15. `rp_comment` - Adds comments and notes to documents, like sticky note annotations.
16. `rp_comparison` - Compares two versions of the same doc side-by-side for changes. 
17. `rp_contrast` - Adjusts contrast levels in images within a document as needed.  
18. `rp_crop` - Crops and resizes images to fit better into the layout of a page.
19. `rp_delete` - Deletes text, objects or entire pages from a document completely. 
20. `rp_diagram` - Creates diagrams with shapes like arrows, boxes, lines etc for visual aids.  
21. `rp_document` - Loads and opens various types of documents (txt, doc, docx, pdf) to edit them in ReadProof format.
22. `rp_editbox` - Adds editable text fields that can be typed into within a document layout. 
23. `rp_emoticon` - Inserts emoticons like smiley faces and other icons as visual cues/reactions.  
24. `rp_equation` - Types out mathematical equations in the proper LaTeX format for printing.
25. `rp_expand` - Expands collapsed sections of a document to reveal hidden content within it. 
26. `rp_export` - Exports documents from ReadProof into various formats like PDF, DOCX etc.  
27. `rp_format` - Formats the entire document for proofing as described in your example above.
28. `rp_freehand` - Allows free-form drawing and doodling on a page with mouse/pen input. 
29. `rp_font` - Changes font styles, sizes, colors of text within the document layout.  
30. `rp_footer` - Adds footers to pages that contain information like date, author etc at bottom of each page.
31. `rp_header` - Creates headers for documents with title/chapter names and other info repeated on top of every page. 
32. `rp_highlight` - Highlights selected text in a document using color or visual cues to draw attention to it.  
33. `rp_image` - Inserts images into the layout, allowing resizing, cropping etc for proper placement within pages.
34. `rp_indent` - Indents blocks of text by adding spaces at beginning like bullet points and lists do. 
35. `rp_insert` - Insertions various elements (text, objects) anywhere in a document's layout as needed.  
36. `rp_italicize` - Makes selected text italicized for emphasis or to indicate foreign words etc.
37. `rp_justify` - Justifies the alignment of blocks of text so that left and right edges are even on each line. 
38. `rp_layout` - Adjusts overall layout, margins, spacing between elements in a document as needed for formatting.  
39. `rp_link` - Creates hyperlinks to other documents or web pages within the current doc's text content.
40. `rp_list` - Generates numbered lists and bulleted lists of items from plain text input by user. 
41. `rp_mark` - Marks up selected portions of a document with visual cues like checkmarks, underlines etc as you described in your example above.  
42. `rp_merge` - Merges two or more documents into one single unified file containing all their content together. 
43. `rp_move` - Moves text blocks and objects around within the layout of a document to new locations on pages.  
44. `rp_newline` - Inserts newline characters in plain text so that it breaks up into paragraphs as needed for formatting. 
45. `rp_numbering` - Adds numbering or letters like A, B, C etc before each item in lists and outlines within a document's content.  
46. `rp_overlay` - Draws overlays on top of images to add annotations, arrows pointing at things etc as you described above for marking up documents visually. 
47. `rp_pagebreak` - Inserts page breaks into the layout so that certain blocks of text or objects start on a new page when printed out.  
48. `rp_paragraph` - Creates paragraphs by adding spaces between lines and indenting first line as needed for formatting plain text input to look like proper paragraph structure in documents. 
49. `rp_pen` - Allows drawing with pen-like tools on pages, similar to freehand but may have more control over stroke thickness etc.
50. `rp_placeholder` - Inserts placeholder boxes that can be typed into or edited later as needed for creating templates and forms within documents. 
51. `rp_print` - Prints out the document in ReadProof format, including all formatting elements like checkmarks, underlines etc when printed on paper.  
52. `rp_proofread` - Proofreads text to catch common errors and suggest corrections as you type or edit a document within ReadProof.
53. `rp_rectangle` - Draws rectangles around specific areas of the page for emphasis similar to boxes but with straight sides instead of rounded corners like in box function.  
54. `rp_remove` - Removes selected text, objects and formatting elements from documents as needed during editing process. 
55. `rp_replace` - Replaces certain words or phrases within a document's content based on user input to edit the overall wording of what is written in doc.  
56. `rp_resize` - Resizes images, text blocks and other objects proportionally while maintaining aspect ratio as needed for proper formatting. 
57. `rp_rotate` - Rotates selected elements like boxes or arrows by a certain angle around their center point within the document layout.  
58. `rp_save` - Saves changes made to documents in ReadProof format, including all added annotations and edits so that they can be loaded back later. 
59. `rp_scale` - Scales up or down selected elements like images by a certain percentage while maintaining aspect ratio as needed for proper formatting.  
60. `rp_select` - Selects text blocks, objects and other elements within the document layout to allow editing of those specific parts without affecting surrounding content. 
61. `rp_shadow` - Adds shadows around selected elements like boxes or arrows in a doc by drawing them slightly offset from their actual position with reduced opacity.  
62. `rp_signature` - Allows users to draw digital signatures on documents using mouse/pen input and save those as part of the document's content. 
63. `rp_sidebar` - Creates sidebars within pages that contain additional information, notes or annotations related to main text but separated from it visually.  
64. `rp_smiley` - Inserts emoticons like smiley faces into documents for visual cues and reactions similar to emoticon function above but with more variety of expressions. 
65. `rp_split` - Splits a document at certain points, either by page or content based on user input so that it can be divided up into multiple separate files.  
66. `rp_strikethrough` - Strikes through selected text in documents to indicate words/phrases should not be included as part of final version. 
67. `rp_subscript` - Makes certain characters like numbers and letters appear smaller than surrounding text by placing them below the baseline for mathematical formulas or other specialized content.  
68. `rp_superscript` - Makes certain characters like exponents in math equations appear above the normal line of text to indicate they are raised up from main body. 
69. `rp_swap` - Swaps positions of two selected elements within a document's layout, such as moving an image over top another element or swapping order of boxes side by side.  
70. `rp_template` - Allows users to create reusable templates for documents that contain pre-formatted layouts and default content so they can be used repeatedly without having to start from scratch each time. 

Prototype Lib
-----------



-----------

[sourceduty.com](https://sourceduty.com/)

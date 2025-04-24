# Templates Supernote
 
This is a collection of templates that I use in my note-taking app Obsidian (https://obsidian.md).
For [my Supernote templates](https://github.com/malleVF/Supernote-Templates) I have published another repo on github. 

I could use Obsidian on a Supernote device, but I have decided against it. Instead, I use a plugin in Obsidian to copy my Supernote notes to my Obsidian vault when it makes sense for me. On the other hand, I can import an Obsidian note as a PDF file to read it in Supernote or use it as a template. 

All the icons in my templates are from https://lucide.dev/icons/. 

## Obsidian Templates

To keep certain types of notes organized, I use templates. I mostly use the [Templater](https://github.com/SilentVoid13/Templater) and [Dataview](https://github.com/blacksmithgu/obsidian-dataview) plugins to code and link the notes in the vault.

The **Templater** plugin is required and the **Dataview** plugin is strongly recommended, otherwise the templates cannot be executed or, in the case of Dataview, the notes created cannot interact with each other.

It is not necessary to use all templates, but they can benefit from each other. For example, Meeting, Jour Fixe and Trip Planner can use the notes from the contact template as well. On the other hand, the contact notes provide you with a list of other notes to which the contact name is linked.

### Contact

I simply use this template for all my contacts and it works like an address book. Only a few pieces of information are requested during execution, e.g.
- Name (first and last name)
- Telephone number
- Company
- Job title
- Email address
- Relationship (to other contacts, e.g. reporting line, etc.)
After creation, the file is moved to the **Contacts** folder. If I also want to add the postal address, I can do this directly in the created note. 
Don't be surprised that two colons are used in the postal address. It is not a typing error, but is interpreted by the Dataview plugin as so-called [Inline Fields](https://blacksmithgu.github.io/obsidian-dataview/annotation/add-metadata/).

### Cover Pager - Cover Page TLP

The cover page template is rather optional if a cover page with company logo is required for the export of a note to make it look more official.

This template is designed with information security in mind, where I can select a file classification to mark it.

The default **Cover Page** template sets one of the following file classifications on the cover page:  
- Public 
- Internal 
- Confidential 
- Strictly confidential 

Optional, the Traffic Light Protocol ([TLP](https://www.first.org/tlp/)) classification template **Cover page TLP** sets one of the TLP labels on the cover page and the corresponding disclosure agreement text for:
- TLP:CLEAR
- TLP:GREEN
- TLP:AMBER
- TLP:AMER+STRICT
- TLP:RED

### Jour Fixe

### Meeting

### Trip Planner

### Workshop



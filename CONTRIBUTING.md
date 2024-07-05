# Libre Library Contributing Guidelines

## Adding Books

To add one or more books, you must fork the repository, make modifications to the local fork, and then make a Pull Request to the original repository.

Only Pull Requests that follow the guidelines established in this document will be accepted.

## Naming

* The file name must exactly match the title of the book.
* The name of each file must be created in lower case.
* Special characters cannot be added to the book name.
* Each word in the file name must be separated by a hyphen.
* The default format must be PDF, if you do not have the book in PDF, there are various tools to do the conversion.
* A section name must follow the same rules as the naming of book files.

## Structure

* Books should be organized by sections.
* A section is a directory, which must contain the books and a README.md file (GitHub Markdown file) with the section index.
* A book should not physically be in more than one section; If the book applies to multiple sections, it should be added to the most relevant one and linked from the other sections.
* If a section does not exist, the directory and the README.md file that will serve as the section's index must be created.  The main README.md file in the repository must be updated by adding the new section and each of the new files.
* Subsections can be created for greater specificity, but no more than 1 level deep.
* The Indexes must be ordered alphabetically in ascending order.
* Books, sections and subsections must be correctly linked and navigable from any location where they are listed.

## Examples

### Book
```
Book Title: The Self-Taught Computer Scientist
File Name: the-self-taught-computer-scientist.pdf
```

### Section
```
Section Name: Computer Science
Section Directory Name: computer-science
```
### Subsection

```
Subsection Name: React
Subsection Directory Name: react
Subsection Directory Path: javascript/react
```

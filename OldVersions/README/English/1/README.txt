
***

<details open><summary><p><b>Click/tap here to expand/collapse the project logo</b></p></summary>

<img src="/HyperSlice_1024pxIcon_V1_HighCompression.png" alt="HyperSlice logo" width="256" height="256">

</details> <!-- Logo:End !-->

<details open><summary><p><b>Click/tap here to expand/collapse this article</b></p></summary>

# [HyperSlice](#HyperSlice)

<details open><summary><p><b>Click/tap here to expand/collapse the title/lead section</b></p></summary>

`✂️⚡️🔪️💾️ HyperSlice is an AI powered tool for rapidly cutting elements out of digital media, and saving them to various output files.`

</details> <!-- Title/lead:End !-->

***

## [Targets](#Targets)

<details open><summary><p><b>Click/tap here to expand/collapse the targets section</b></p></summary>

The logo of HyperSlice gives a basic example of functionality. HyperSlice can snip out different parts of the image and place them in separate files. The first challenge is to fix the HyperSlice logo using only HyperSlice.

A better example is webpages. HyperSlice can read document source code, and can snip out only content placed in specific tags (such as `<div>` `<header>` `<article>` `<li>` and more) it can do this either by reading the source code, or selecting content it sees as being in its own section. It can also do this multiple times at once throughout the page, and saving them to output files.

This functionality also applies to images and videos, but not audio. Videos can be sliced through recorded playback of up to 24 hours, although processing time and needed RAM multiplies with every second, which is something to keep in mind.

</details> <!-- Targets:End !-->

***

## [Technical](#Technical)

<details open><summary><p><b>Click/tap here to expand/collapse the technical section</b></p></summary>

This project is written in Julia, and relies on the [:octocat: `AI2001 framework`](https://github.com/seanpm2001/AI2001/) although it is not directly a part of the AI2001 project.

</details> <!-- Technical:End !-->

***

## [.hypslyce](#-hypslyce)

<details open><summary><p><b>Click/tap here to expand/collapse the .hypslyce section</b></p></summary>

A hypslyce file is a project file containing instructions for snipping/slicing and output. It is an XML file.

Here is an example of a simple `.hypslyce` file that grabs all `<div>` HTML elements and exports it into an SVG image:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<hyperslice>
	<hypersnip>
		<systemType="UNIX-like"></systemType>
		<file="///bob/home/Desktop/HyperSlice-Demo/Input/Test.htm">
			<target="<div>" && "</div>"></target>
			<action="Snip"></action>
			<mode="image/svg"></mode>
			<range="l1" && "l999"></range> <!-- The first 999 lines of the file !-->
			<exportTo="///bob/home/Desktop/HyperSlice-Demo/Output/DIV.svg">
			<overWrite="False"></overWrite>
		</file>
	</hypersnip>
</hyperslice>
```

When `overWrite` is set to `False`, any additional images that are generated are placed in a separate file in the target folder with the same name, with a number appended to it.

In this example, Bob is the username, and the system is UNIX-like. An HTML file is the input, where its first 999 lines are read, and all `<div>` elements are sent to a file called `DIV.svg` if more than 1 `<div>` element is selected, additional output files will go like `DIV-1.svg` `DIV-2.svg` and so on.

</details> <!-- .hypslyce:End !-->

***

## [Alternative name](#Alternative-name)

<details open><summary><p><b>Click/tap here to expand/collapse the alternative name section</b></p></summary>

The secondary name for this project is HyperSnip, which is intended to be used for small snippets.

<!-- I don't enforce pronunciation, but I do enforce terminology !-->

</details> <!-- Alternative name:End !-->

***

## [Additional-documentation](#Additional-documentation)

<details open><summary><p><b>Click/tap here to expand/collapse the additional documentation section</b></p></summary>

Additional documentation is located [:octocat: `in a separate repository`](https://github.com/seanpm2001/HyperSlice_Docs/)

</details> <!-- Additional documentation:End !-->

***

## [Original draft](#Original-draft)

<details open><summary><p><b>Click/tap here to expand/collapse the original draft section</b></p></summary>

```plain-text
HyperSlice

AI powered tool to cut various elements out of an image, and save them to various files (such as: each <div> detected in a screenshot) give it other targets via a .hypslyce file with instructions.
```

</details> <!-- Original draft:End !-->

</details> <!-- Article:End !-->

***

# [File info](#File-info)

<details open><summary><p><b>Click/tap here to expand/collapse the file info section</b></p></summary>

**File type:** `Markdown (*.md *.mkd *.mdown *.markdown)`

**File version:** `2 (2023, Wednesday, July 5th at 01:26 pm PST)`

**Line count (including blank lines and compiler line):** `213`

**Word count:** `1,161`

**Character count (including spaces):** `7,666`

**Character count (excluding spaces):** `6,542`

**Size (in bytes):** `7,684`

**Current article language:** `English (EN_USA)` / `Markdown (CommonMark)` / `HTML5 (HyperText Markup Language 5.3)`

**Encoding:** `UTF-8 (Emoji 12.0 or higher recommended)`

**All times are UTC-7 (PDT/Pacific Time)** `(Please also account for DST (Daylight Savings Time) for older/newer entries up until it is abolished/no longer followed)`

> **Note** _On 2022, Sunday, March 13th at 2:00 am PST, the time jumped ahead 1 hour to 3:00 am._

> **Note** **You may need special rendering support for the `<details>` HTML tag being used in this document**

</details> <!-- File info:End !-->

***

# [File history](#File-history)

<details open><summary><p><b>Click/tap here to expand/collapse the file history section</b></p></summary>

## Version 1 (2023, Monday, July 3rd at 11:20 pm PST)

<details open><summary><p><b>Click/tap here to expand/collapse the file history entry for version 1 section</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> Changes

- [x] Started the file
- [x] Added the title section
- [x] Referenced the project logo
- [x] Added the `Targets` section
- [x] Added the `Technical` section
- [x] Added the `.hypslyce` section
- [x] Added the `Alternative name` section
- [x] Added the `Additonal documentation` section
- [x] Added the `Original draft` section
- [x] Added the `File info` section
- [x] Added the `Footer` section
- [ ] No other changes in version 1

</details> <!-- File history:V1:End !-->

## Version 2 (2023, Wednesday, July 5th at 01:26 pm PST)

<details open><summary><p><b>Click/tap here to expand/collapse the file history entry for version 2 section</b></p></summary>

- This release was made by: [:octocat: `@seanpm2001`](https://github.com/seanpm2001/)

> **Note** _This release was delayed by 1 day due to time issues._

> Changes

- [x] Converted all sections into dropdown sections
- [x] Updated the `.hypslyce` section to include an example
- [x] Updated the `Additional documentation section` to fix a typo
- [x] Updated the `Technical` section to clarify that this is not part of the AI2001 project
- [x] Updated the `File info` section
- [x] Added the `File history` section
- - [x] Added an entry for version 1
- - [x] Added an entry for version 2
- [ ] No other changes in version 2

</details> <!-- File history:V2:End !-->

</details> <!-- File history:End !-->

***

# [Footer](#Footer)

<details open><summary><p><b>Click/tap here to expand/collapse the footer</b></p></summary>

You have reached the end of this page.

</details> <!-- Footer:End !-->

###### [EOF](#EOF)

***

# Project Name: LaTeX Template (Yet Another LaTeX Document Template)

## Description

This LaTeX project provides a template for generating documents with a
front page. It is designed to create a report structure, including a
title page, content, and additional sections. The document is built
using the `report` class and can be compiled with LuaLaTeX for better
font support.

## Document Structure

-   `main.tex`: The main LaTeX document where the content is compiled.
-   `sources/preamble.tex`: Contains the LaTeX preamble, including
    packages, fonts, and custom commands.
-   `sources/variables.tex`: Stores document variables such as title,
    author, and other customizable information.
-   `README.md`: This file, which provides documentation about the
    project structure and compilation instructions.

## Quick Start

1.  **Copy the template to some folder**

2.  **Change variables / settings**

-   **`main.tex`**

-   Set the document class, see lines 7-9.

-   **`sources/preamble.tex`**

-   Uncomment line 8 for Letter Paper.

-   Set your default language last at line 16; just reorder as needed.

-   **`sources/variables.tex`**

-   Set the following variables:

-   `doctitle`

-   `docsubtitle`

-   `docstate`

-   `documentabstract`

-   `author`

3.  **Edit the files `sections/intro.tex`, `sections/chapters.tex`, and
    `sections/appendices.tex`**\
    These files are located in the `sections` folder.

## Compiling Instructions

1.  Make sure you have LaTeX installed (preferably LuaLaTeX for enhanced
    font support).
2.  To compile the document, press the 'Build & View' button in
    TeXstudio.

------------------------------------------------------------------------

## Licenses

**Copyright (c) 2025 Bouke Jasper Henstra <bouke@ict-diensten.com>**

This template is licensed under the **BSD License**. You are free to
use, modify, and distribute this template for any purpose, with or
without modification, provided that the following conditions are met:

1.  The above copyright notice and this permission notice must appear in
    all copies or substantial portions of the software.
2.  This software is provided "as is", without warranty of any kind. The
    author disclaims all warranties, express or implied, including but
    not limited to the implied warranties of merchantability and fitness
    for a particular purpose. In no event shall the author be liable for
    any claim, damages, or other liability, whether in an action of
    contract, tort, or otherwise, arising from, out of, or in connection
    with the software or the use or other dealings in the software.

------------------------------------------------------------------------

## Third-Party Products Used

1.  **IBM Plex® Typeface**

-   **Source**: [GitHub - IBM Plex](https://github.com/IBM/plex)
-   **License**: [SIL Open Font License, Version
    1.1](https://github.com/IBM/plex/blob/master/LICENSE.txt)

This font software is licensed under the SIL Open Font License, Version
1.1. You can freely use, study, copy, modify, and redistribute the font,
provided the following conditions are met:

-   The font software or any modified version must not be sold by
    itself.
-   The font software must remain under this license and must not be
    distributed under any other license.
-   No modified version of the font may use the reserved font name
    unless explicit permission is granted by the copyright holder.

For more details, please refer to the full SIL Open Font License
available at:\
[SIL Open Font License - FAQ](http://scripts.sil.org/OFL)

------------------------------------------------------------------------

## Important Notes

-   The **BSD License** applies to the LaTeX template itself.
-   The **SIL Open Font License** applies to the IBM Plex® font, and
    other third-party libraries or tools used in this project may have
    different licenses. Please consult the individual licenses of any
    third-party products included in this template to ensure compliance.

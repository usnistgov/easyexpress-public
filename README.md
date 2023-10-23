# easyEXPRESS

This Visual Studio Code extension provides support for the [EXPRESS (ISO 10303-11)](https://www.iso.org/standard/38047.html) information modeling language.

## Development status

easyEXPRESS is currently in early stages and under active development. Expect bugs and missing features that we encourage you to document and report:

- For any problem or bug, please [create an issue](https://github.com/usnistgov/easyexpress-public/issues).
- If a similar issue has already been filed, please leave a :thumbsup:/:thumbsdown: to help us prioritze them.
- For any other kind of feedback, please [start a new discussion](https://github.com/usnistgov/easyexpress-public/discussions).

Note to STEP developers: long form and concatenated files are not supported at the moment.

## What is easyEXPRESS?

easyEXPRESS is a [Visual Studio Code](https://code.visualstudio.com/) extension that aims at providing advanced editing capabilities to [EXPRESS](https://www.iso.org/standard/38047.html) developers and help them efficiently write valid EXPRESS information models.

Advanced editing capabilities in development include:

- Syntax highlighting and validation
- [Intellisense](https://code.visualstudio.com/docs/editor/intellisense): write code faster with auto-completion
- [Code navigation](https://code.visualstudio.com/docs/editor/editingevolved): navigate your code with features such as [Go to Definition](https://code.visualstudio.com/Docs/editor/editingevolved#_go-to-definition)
- [Code refactoring](https://code.visualstudio.com/docs/editor/refactoring): refactore your code with featurs such as [Rename Symbol](https://code.visualstudio.com/docs/editor/refactoring#_rename-symbol)
- [Code snippets](https://code.visualstudio.com/docs/editor/userdefinedsnippets): write code faster with shortcuts to commonly used code patterns

## Current status


<table>
    <thead>
        <tr>
            <th>Feature</th>
            <th>Context</th>
            <th>Status</th>
            <th>Note</th>
        </tr>
    </thead>
<tbody>
 <tr>
            <td style="font-weight:bold;">Group qualifier</td>
            <td></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td></td>
            <td>Supertype tree</td>
            <td>✔ Done</td>
            <td>-</td>
        </tr>
         <tr>
            <td></td>
            <td>Subtype tree</td>
            <td>🚧 In progress</td>
            <td>-</td>
        </tr>
        <tr>
            <td></td>
            <td>SELECT type</td>
            <td>✔ Done</td>
            <td>Under validation</td>
        </tr>
        <tr>
            <td></td>
            <td>Index qualifier</td>
            <td>🚧 In progress</td>
            <td>Only 1D</td>
        </tr>
        <tr>
            <td style="font-weight:bold;">Attribute qualifier</td>
            <td></td>
            <td></td>
            <td>-</td>
        </tr>
                                <tr>
            <td></td>
            <td>Direct attribute</td>
            <td>🚧 In progress</td>
            <td>Only explicit attributes are fully validated</td>
        </tr>
        <tr>
            <td></td>
            <td>From supertype</td>
            <td>🚧 In progress</td>
            <td>-</td>
        </tr>
                                <tr>
            <td></td>
            <td>From subtype</td>
            <td>📅 To do</td>
            <td>-</td>
        </tr>
                                        <tr>
            <td></td>
            <td>Index qualifier</td>
            <td>🚧 In progress</td>
            <td>Only 1D</td>
        </tr>
                                <tr>
            <td style="font-weight:bold;">Enums</td>
            <td></td>
            <td>📅 To do</td>
            <td>-</td>
        </tr>
                <tr>
        <td colspan="4" style="text-align:center">More information coming soon ...</td>
        </tr>
</tbody>
</table>


## How to contribute?

The best way to contribute for now is to properly document and report bugs and feature requests using the [issues](https://github.com/usnistgov/easyexpress-public/issues) and [discussions](https://github.com/usnistgov/easyexpress-public/discussions).

## Contact information

For comments or questions, you can reach out directly to:

- Sylvere Krima - sylvere.krima@nist.gov
- Allison Barnard Feeney - allison.barnardfeeney@nist.gov
- Rosemary Astheimer - rosemary.astheimer@nist.gov

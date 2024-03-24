<h1 align="center"><b>iVer</b></h1>
<p align="center">iVer is a standardisation system for project versioning and abbreviations.<br><br></p>

<br>

## Versioning Format<br>
<b>Format:</b> v0.0.0.0 mk*n*<br>
<b>First Number:</b> Features and/or security updates that do not change the core structure.<br>
<b>Second Number:</b> Stability updates and improvements to the existing code base.<br>
<b>Third Number:</b> Design changes.<br>
<b>Forth Number:</b> Minor adjustments that don't have to be visible to the end user.<br>

*Note: The number that's ahead resets the number that follows it. If you have, for example, version 1.2.3 and you make a <b>stability update</b>, the new version should be 1.3.0 and not 1.3.3.*

## Abbreviations Dex<br>
<b>iVer</b> = Info Version<br>
<b>mk</b> = Mark<br>
<b>v</b> = Version<br>
<b>*n*</b> = (placeholder for) Number<br>

## Use Cases<br>
<b>mk</b>*n*:
- Shall be used when an existing project is redesigned and built from scratch but relies on the concept and developments previously achieved.
- When a new <b>mk</b> is launched, the versioning shall start from 1.0.0.<br>

<br>

<b>build:</b>
- Developer side only.
- Any changes that are meant to better organise or structure the app, with 0 impact on the user end, shall be recorded with a <b>build</b> number.
- Changes that are <b>build</b> exclusive should not be included into a new release.
- Use cases include changing the name of a ```<div>``` or formatting the code differently.

## Usage<br>
Every change made to the iVer document is creating a unique concept. One mk could be entirely different from the other ones and so, on a project, it can be mentioned that it is following the "<b>iVer versioning format mk*n*</b>" to be specific or "<b>iVer versioning format</b>" to always refer to the latest version.

<br>

<b>Examples:</b>

Code:
```
**This repository follows the [iVer](https://github.com/frontfacer/iVer) versioning format.*
```
Output:<br>

**This repository follows the [iVer](https://github.com/frontfacer/iVer) versioning format.*

<br><br>

Code:
```
**This repository follows the [iVer](https://github.com/frontfacer/iVer) versioning format mkn.*
```
Output:<br>

**This repository follows the [iVer](https://github.com/frontfacer/iVer) versioning format mkn.*

<br>

#
<p align="center">© 2022 - 2024 | FRONTFACER<br/>www.frontfacer.com<br>

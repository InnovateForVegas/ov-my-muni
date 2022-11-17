<!--
 Copyright (C) 2022 Innovate for Vegas Foundation
 
 This file is part of ov-my-vegas.
 
 ov-my-vegas is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.
 
 ov-my-vegas is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.
 
 You should have received a copy of the GNU General Public License
 along with ov-my-vegas.  If not, see <http://www.gnu.org/licenses/>.
-->

# My Vegas Overview

This Overview repository is a specification and documentation component of the My Vegas Project. Please do not add code or other resources to this repository.

The goal of the My Vegas Project is to enable a Human Interface for our Smarter Smart City.

## Project Policies

Unless otherwise and specifically indicated with replacement files in this repository, this project will adhere to the default Innovate for Vegas Foundation policies for Code of Conduct and Contributing, found at

* [Code of Conduct - Innovate for Vegas Foundation](https://github.com/InnovateForVegas/.github/blob/main/CODE_OF_CONDUCT.md)
* [Contributing to this Project - Innovate for Vegas Foundation](https://github.com/InnovateForVegas/.github/blob/main/CONTRIBUTING.md)

## General Focus Areas

A completely reasonable starting point would combine examining which mobile applications and deployed websites are available at any given time from our City and/or its agencies and relations, example the way other localities address similar interfaces to city services and other information with regard to their populations, and apply a layer of thoughtfulness and interactive engagement with our populace to develop and evolving user experience that is, and will be, a better Human Interface than has been available to date.

This is the *Familiar Surprise* approach, with some caveats.

With the Smart Social project, it is easier to adapt existing platforms and applications and so on, to new paradigms, which can still leverage existing protocols and tools for most of the initial functionality (that is the design approach, at least). If we assume that My Vegas can begin with Smart Social services, we can take the Familiar Surprise approach. However, there will ideally be some new things done in new ways, so while the overall My Vegas platform should be viewed as a MAYA design, there should be components of it that are unusual and new and perhaps unexpected.

### Native Applications vs Progressive Web Applications vs Plain Old HTML

There is no compelling reason to require a particular approach across the board. There will be cases where a native application, requiring installation from a vendor application store somewhere, makes sense.

For the most part, though, a no-install-required approach may make adoption easier, and will make bug fixes and feature changes more easily deployed to users who may or may not be willing to track a rapid or diverse development cycle. To insure the broadest compatibility and least-obtrusive user experience, a web-first (plain HTML to progressive web application) is probably preferable. There is no hard rule here, though.

### Accessibility

Wherever possible, proactive use of WAI-ARIA and other applicable accessibility tools and methods, is encouraged during development and will be required for deployment.

A component of the My Vegas platform must be the ability to accept accessibility feedback in an accessible way from our users. Recall that our users will be our friends and neighbors.

### Inclusivity and Diversity

Building web-first components will mitigate the need for higher-end mobile devices, latest-versions of software on the client side and build SDKs on the developer side.

As well, content and the platform should be built with cultural and language awareness. While 2020 Census data indicates that English and Spanish are the two languages of note spoken in the greater Las Vegas area, the ability to include users speaking other languages (visiting or living in our Smart City), textual content, edit, layout, etc must keep these in mind. Accessibility is certainly a component here, in that someone visiting the My Vegas platform may not use English as their first or second language, and may also not see the content presented.

Diversity will almost certainly figure into general platform presentation. Some of the user audience will be visiting our Smart City from other places, and it is possible that the My Vegas platform will make a splash with other places. Presumptions about our users should be kept to a minimum.

## References

[Raymon Loewy - MAYA - Familiar Surprise](https://uxdesign.cc/most-advanced-yet-acceptable-theory-meets-digital-product-innovation-f14897147dd5)

    “To sell something surprising, make it familiar; to sell something familiar, make it surprising.”

    — Raymond Loewy

<!--
 Copyright (C) 2022 Innovate for Vegas Foundation
 
 This file is part of ov-my-muni.
 
 ov-my-muni is free software: you can redistribute it and/or modify
 it under the terms of the GNU General Public License as published by
 the Free Software Foundation, either version 3 of the License, or
 (at your option) any later version.
 
 ov-my-muni is distributed in the hope that it will be useful,
 but WITHOUT ANY WARRANTY; without even the implied warranty of
 MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
 GNU General Public License for more details.
 
 You should have received a copy of the GNU General Public License
 along with ov-my-muni.  If not, see <http://www.gnu.org/licenses/>.
-->

# Welcome to My Muni

This is project aimed at building the parts that make up the Human Interface to our Smart City (this project began as *My Vegas* and so may refer to Las Vegas sometimes, all aspects should apply to any municipality, hence the rename!). There are, as of 2022, several applications available on the various mobile app stores that deal with particular elements of the City of Las Vegas and surrounding areas, each in various statues of usefulness and modernity, and each a native application which requires installation. This is something to look at in particular as we move through this project timeline.

Remember, *My Muni* (formerly *My Vegas*) is a project name, not a product name (especially since there is a magazine, a website, and a variety of other uses of the *My Vegas* name already), and the components that make up the My Muni project may be separately-useable, separately-installable (in the case of a stand-alone native application or similar), and separately-enabling. Or, everything might fit together in one monolithic mobile-first or progressive web application.

We will make this determination along the way, ideally with real user feedback!

## Native Applications vs Progressive Web Applications vs Plain Old HTML

There is no compelling reason to require a particular approach across the board. There will be cases where a native application, requiring installation from a vendor application store somewhere, makes sense.

For the most part, though, a no-install-required approach may make adoption easier, and will make bug fixes and feature changes more easily deployed to users who may or may not be willing to track a rapid or diverse development cycle. To insure the broadest compatibility and least-obtrusive user experience, a web-first (plain HTML to progressive web application) is probably preferable. There is no hard rule here, though.

### Accessibility

Wherever possible, proactive use of WAI-ARIA and other applicable accessibility tools and methods, is encouraged during development and will be required for deployment.

A component of the My Muni platform must have the ability to accept accessibility feedback in an accessible way from our users. Recall that our users will be our friends and neighbors, we need to receive and act on their feedback!

### Inclusivity and Diversity

Building web-first components will mitigate the need for higher-end mobile devices, latest-versions of software on the client side and build SDKs on the developer side.

As well, content and the platform should be built with cultural and language awareness. While 2020 Census data indicates that English and Spanish are the two languages of note spoken in the greater Las Vegas area (for example), the ability to include users speaking other languages (visiting or living in our Smart City), to account for textual content, the ability to edit, layout (eg think right-to-left as an option), etc must keep these in mind. Accessibility is certainly a component here, in that someone visiting the My Muni platform may not use English as their first or second language, and may also not see the content presented.

Diversity will almost certainly figure into general platform presentation. Some of the user audience will be visiting our Smart City from other places, and it is possible that the My Muni platform will make a splash with other places. Presumptions about our users should be kept to a minimum. Aiming our efforts toward visitors will really be the focus of the Welcome project (not to be confused with the name of this file you are reading now).

## References

[Raymond Loewy - MAYA - Familiar Surprise](https://uxdesign.cc/most-advanced-yet-acceptable-theory-meets-digital-product-innovation-f14897147dd5)

    “To sell something surprising, make it familiar; to sell something familiar, make it surprising.”

    — Raymond Loewy

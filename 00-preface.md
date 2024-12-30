---
title:
- type: main
  text: Warez
- type: subtitle
  text: The Infrastructure and Aesthetics of Piracy
creator:
- role: author
  text: Martin Paul Eve
publisher: punctum books
date: 2021
rights: © 2021 Martin Paul Eve, CC BY-NC-SA 4.0 International
lang: en
identifier:
- scheme: DOI
  text: doi:10.53288/0339.1.00
- scheme: LCCN
  text: 2021951510
cover-image: images/cover.png

---
# Support {epub:type=foreword}

Before you start to read this book, take this moment to think about making a donation to [punctum books](https://punctumbooks.com/support/), an independent non-profit press:

https://punctumbooks.com/support/

If you’re reading the e-book, you can click on the image below to go directly to our donations site. Any amount, no matter the size, is appreciated and will help us to keep our ship of fools afloat. Contributions from dedicated readers will also help us to keep our commons open and to cultivate new work that can’t find a welcoming port elsewhere. Our adventure is not possible without your support.

Vive la Open Access.

<figure>

![](./images/fig.0-hieronymous-bosch-ship-of-fools.jpg)

<figcaption>Fig. 0: Hieronymus Bosch, Ship of Fools (1490–1500)</figcaption>
</figure>

\newpage{}

# Copyright notice {epub:type=copyright-page}

_Warez: The Infrastructure and Aesthetics of Piracy_. Copyright © 2021 by Martin Paul Eve. This work carries a Creative Commons BY-NC-SA 4.0 International license, which means that you are free to copy and redistribute the material in any medium or format, and you may also remix, transform and build upon the material, as long as you clearly attribute the work to the authors (but not in a way that suggests the authors or punctum books endorses you and your work), you do not use this work for commercial gain in any form whatsoever, and that for any remixing and transformation, you distribute your rebuild under the same license. http://creativecommons.org/licenses/by-nc-sa/4.0/

First published in 2021 by dead letter office, BABEL Working Group, an imprint of punctum books, Earth, Milky Way.

https://punctumbooks.com

The BABEL Working Group is a collective and desiring-assemblage of scholar– gypsies with no leaders or followers, no top and no bottom, and only a middle. BABEL roams and stalks the ruins of the post-historical university as a multiplicity, a pack, looking for other roaming packs with which to cohabit and build temporary shelters for intellectual vagabonds. We also take in strays.

ISBN-13: 978-1-68571-036-1 (print) \
ISBN-13: 978-1-68571-037-8 (ePDF) \

DOI: 10.53288/0339.1.00

LCCN: 2021951510 \
Library of Congress Cataloging Data is available from the Library of Congress

Work on this book was made possible through the award of a Philip Leverhulme Prize from the Leverhulme Trust.

Book design: Vincent W.J. van Gerven Oei

Cover image: Ahmed Adly via Unsplash

\newpage{}

# Acknowledgements {epub:type=acknowledgements}

Many individuals have helped me in the writing of this book. My thanks at punctum to Eileen Joy, Vincent W.J. van Gerven Oei, and Lily Brewer. For her brilliantly helpful suggestions on the manuscript, my thanks to Virginia Crisp. Notably, thanks also to Jamie Harries, Ronald Snijder, Paul Tavner, Jake Bickford, James Baker, and John Fink for responding to my queries on degenerative DRM. I owe a debt to Ben Garrett for assembling the DeFacto2 archive that underpins this work. My thanks go also to Iñigo Quilez for permission to include images of his DemoScene productions. With thanks to my friends, in no particular order: Joe Brooker, John and Caroline Matthews, Caroline Edwards, Iain Robert Smith, James and Holly Crow, Helen and Duncan Stringer, Alyson Jakes, Duncan Gray, Richard Hall, Hazel and Michael Vanderhoeven, Siân Adiseshiah, Ernesto Priego, Ben Johnson, Lianne de Mello, Julian Cottee, Doireann Lalor, Mark Blacklock, Peter Christian, Roland Clare, Kay Mendlson, Warren Young, Andy Byers, Mauro Sanchez, Rose Harris-Birtill, Paula Clemente Vega, Tom Grady, Jon Fugler, Bryan Cheyette, Stephen Curry, Don Waters, Ross Mounce, Tobias Steiner, and Sam Moore. Everyone at A Love From Outer Space. Friendship has sustained me through the writing of this book under difficult global circumstances. I hope to see you all on the other side of the coronavirus pandemic. My final thanks, as ever, go to my family — Gill Hinks, Rich Gray, Alyce Magritte, Nova Gray, Mina Gray, Susan Eve, Juliet Eve, Lisa Holloway, Carin Eve, Anthony Eve, Julia Eve, Sam Jones, and Toby Eve — but especially, with all my love, to my wife, Helen.

\newpage{}

# Dedication {epub:type=dedication}

_For Nova and Mina, who will not know, for some time, what this book is about_

_and for James, who already does._

\newpage{}

# Terminological Notes {epub:type=foreword}

Throughout this book, the terms “Warez Scene” and “the Scene” are capitalized in order to denote the underground movement. Other terms, such as NukeNets have some capitalisation where there are CamelCase formulations, while some roles do not. User nicknames are specified in the case used by the holder.

\newpage{}

# Glossary {epub:type=foreword}

<dl epub:type="glossary">
  <dt><b>0day.</b></dt><dd>Refers to the most bleeding-edge access to pirate releases. Its derivation is that access comes “0 days” since its release.</dd>
  <dt><b>Addline.</b></dt><dd>The command that will add a user to a topsite. This command contains the user’s Internet Protocol (IP) details, ident mask, and other security features.</dd>
  <dt><b>Affiliate.</b></dt><dd>An arrangement whereby a release group is associated with a topsite and “pres” its releases on that site. It can also refer to the affiliation of courier groups with a site.</dd>
  <dt><b>ASCII art.</b></dt><dd>An artistic mode in which graphics are constructed from textual characters using the American Standard Code for Information Interchange.</dd>
  <dt><b>Autotrader.</b></dt><dd>A courier who uses software to transfer releases between topsites automatically without any human intervention. It is also used to refer to such software itself. It is generally frowned upon but is also a seemingly widespread practice.</dd>
  <dt><b>Bittorrent.</b></dt><dd>A protocol for the distribution of content between peers. It is often but not exclusively used in the lower echelons of the piracy hierarchy.</dd>
  <dt><b>Bouncer (BNC).</b></dt><dd>A proxy to which users connect. These mechanisms hide or cloak a topsite’s actual IP address. Bouncers can handle either just the File Transfer Protocol (FTP) command channel or can also take the form of “traffic bouncer” that also masks the data stream. There are also IRC bouncers that keep users connected to an Internet Relay Chat server, which means that they do not have to reconnect to the server every time and that their connecting IP address remains hidden.</dd>
  <dt><b>Bulletin Board System (BBS).</b></dt><dd>A precursor to the internet that offered dial-in access to a single machine. The Scene originated in BBS cultures and moved to the internet in the 1990s.</dd>
  <dt><b>Courier.</b></dt><dd>An individual who moves releases between sites to build ratio credit for download and to participate in courier charts. The act of transferring a release, in competition with other couriers, is called “racing.” Previously, in earlier BBSs, a courier was also referred to as a “broker.”</dd>
  <dt><b>Courier Charts.</b></dt><dd>Competitive scoring systems that rank couriers. Based on weektop scorecards.</dd>
  <dt><b>Crack.</b></dt><dd>A modification to a piece of software that removes its copyright protection routines. Often bundled with releases. </dd>
  <dt><b>Daemon.</b></dt><dd>A piece of server software that runs as a background process, rather than interactively. Examples include web servers and FTP servers that serve remote users. Topsites use FTP daemons.</dd>
  <dt><b>DRM.</b></dt><dd>Digital Rights Management. Programming routines that aim to make it impossible, illegally, to copy an artefact. Cracks aim to circumvent DRM/TPM.</dd>
  <dt><b>Dupecheck.</b></dt><dd>A database of previous scene releases, allowing a release group to ascertain whether a release is a duplicate of a previous work.</dd>
  <dt><b>Eggdrop.</b></dt><dd>A piece of software for running IRC bots. It is frequently used to run topsite bots.</dd>
  <dt><b>Exif.</b></dt><dd>Exchangeable image file format. An image file format that may contain metadata exposing the original source.</dd>
  <dt><b>File eXchange Protocol (FXP).</b></dt><dd>The use of FTP to transfer files between two remote servers rather than the more common client-server architecture.</dd>
  <dt><b>File Transfer Protocol (FTP).</b></dt><dd>A protocol for storing and retrieving files from a remote server.</dd>
  <dt><b>FLAC.</b></dt><dd>The Free Lossless Audio Codec. A lossless music compression format.</dd>
  <dt><b>FXP board.</b></dt><dd>A bulletin board or forum site where pirated releases are disseminated through hacked servers. It is a lower level of the Warez Scene that is strictly frowned upon by the topsite scene.</dd>
  <dt><b>Ident.</b></dt><dd>A protocol specified in the specification document “RFC 1413” (Request for Comment) that identifies the user of a particular TCP (Transmission Control Protocol) connection. It is used in the Scene to determine whether a user connecting to the topsite is authorized.</dd>
  <dt><b>Internal.</b></dt><dd>A release designed only for dissemination among members of the release group itself. Such releases are not beholden to the same standards (e.g., dupecheck) as public releases.</dd>
  <dt><b>Internet Relay Chat (IRC).</b></dt><dd>A distributed online chat system used by Sceners to communicate with one another. Site bots also post updates to the IRC channels of topsites.</dd>
  <dt><b>Keygen.</b></dt><dd>A “key generator.” A piece of software that will produce a valid, but counterfeit, serial key or license for software that requires it. Often distributed with a release.</dd>
  <dt><b>Leet-speak.</b></dt><dd>A contraction of “elite speak”—a form of slang communication that uses text and numbers. Often, the numbers “1337” or “31337” are used to mean “leet” of “eleet” for the digits’ resemblance to “e,” “l,” and “t.”</dd>
  <dt><b>MP3.</b></dt><dd>The MPEG-2 Audio Layer III codec. A music compression format.</dd>
  <dt><b>NFO Files.</b></dt><dd>Short for iNFOrmation file. A text file that contains information about a release. Usually also populated with ASCII art.</dd>
  <dt><b>Nuke.</b></dt><dd>Both a noun and a verb. In its noun form, this refers to a “bad” release that has been marked as a rule violation at either the topsite-level (a violation of individual site rules) or Scene-level (a violation of release rule standards). Nuke as a verb refers to the act of marking a release as bad using the “site nuke” command.</dd>
  <dt><b>NukeNet.</b></dt><dd>An inter-site system for nuking releases.</dd>
  <dt><b>Nuker.</b></dt><dd>A person with the role of nuking releases.</dd>
  <dt><b>Pre.</b></dt><dd>A noun and a verb. It is the moment at which a release is made available.</dd>
  <dt><b>Pre-spam.</b></dt><dd>The act of posting pre announcements in order to convey a message rather than to advertise the true availability of a release. They are also used to catch autotraders.</dd>
  <dt><b>Race.</b></dt><dd>The competitive transfer of releases between topsites by couriers. The goal is to earn credits and to score highly enough to retain one’s account on the site. Statistics from this contribute to the weektop scorecard.</dd>
  <dt><b>RAID.</b></dt><dd>A Redundant Array of Independent Disks. This is a storage schema that makes additional copies of data locally, spread across many different hard-disk drives (“striping”), in order to protect against the risk of catastrophic drive failure and data loss. Topsites use RAID to protect their archives.</dd>
  <dt><b>Release.</b></dt><dd>A pirate artefact, be it music, movies, software, games, etc.</dd>
  <dt><b>Release Group.</b></dt><dd>A set of individuals working together to create releases.</dd>
  <dt><b>SceneBan.</b></dt><dd>A lifetime ban instated on an individual for a serious infraction, such as being a law enforcement officer.</dd>
  <dt><b>Site.</b></dt><dd>Short for topsite.</dd>
  <dt><b>Siteop.</b></dt><dd>A site operator. The administrator who runs a topsite. These users may not be the site owner (i.e., the physical owner of the server).</dd>
  <dt><b>Topsite.</b></dt><dd>An FTP server with a high-speed internet connection and vast amounts of storage space. It has affiliates, couriers, siteops, nukers, and other user categories. It is ranked according to various criteria for participation in courier charts.</dd>
  <dt><b>TPM.</b></dt><dd>Technical Protection Measures (TPM). See DRM. Weektop Scorecard. Also referred to as wkup or wktop. The weekly positional ranking of couriers and release groups by the volume uploaded to a particular topsite. Used to create a competitive ambiance and Scene-wide scoring systems such as courier charts.</dd>
  <dt><b>Zipscript.</b></dt><dd>A software routine that executes on a topsite while a release is being uploaded. This provides integrity checking, release tagging, and other “race” features.</dd>
</dl>

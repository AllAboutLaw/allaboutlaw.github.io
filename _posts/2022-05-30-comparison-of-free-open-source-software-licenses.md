---
layout: post
title: Comparison of Free and Open-Source Software Licenses
categories: 
 - IT Law
tags:
 - open-souce license
 - public domain
 - copyright
 - software
 - copyleft
 - lesser general public license
 - permissive license
excerpt: This post is aimed to make the subject more understandable for software developers and users by comparing free and open-source software licenses.
comments: false 
---
In another article, we explained what software licenses are and how they are used (<a href= "https://allaboutlaw.github.io/it%20law/2022/05/22/what-is-a-software-license.html">Here</a>). It can be complicated because of some similarities. I believe, if we do a comparison between them, you can understand easily which one benefits you.

<table>
<tr>
    <th>License</th>
    <th>Linking</th>
    <th>Distribution</th>
    <th>Modification</th>
    <th>Patent Grant</th>
    <th>Private Use</th>
    <th>Sublicensing</th>
    <th>Trademark Grant</th>
  </tr>
  <tr>
    <td>Apache License</td>
    <td>Permissive</td>
    <td>Permissive</td>
    <td>Permissive</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Permissive</td>
    <td>No</td>
  </tr>
  <tr>
    <td>BSD License</td>
    <td>Permissive</td>
    <td>Permissive</td>
    <td>Permissive</td>
    <td>Manually</td>
    <td>Yes</td>
    <td>Permissive</td>
    <td>Manually</td>
  </tr>
  <tr>
    <td>European Union Public License</td>
    <td>Permissive,<em>(Recitals 10 & 15 Directive 2009/24/EC)</em></td>
    <td>Copylefted, with an explicit compatibility list</td>
    <td>Copylefted, with an explicit compatibility list</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Copylefted, with an explicit compatibility list</td>
    <td>No</td>
  </tr>
  <tr>
    <td>GNU General Public License</td>
    <td>GPLv3 compatible only</td>
    <td>Copylefted</td>
    <td>Copylefted</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Copylefted</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>GNU Lesser General Public License</td>
    <td>With restrictions</td>
    <td>Copylefted</td>
    <td>Copylefted</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Copylefted</td>
    <td>Yes</td>
  </tr>
  <tr>
    <td>Microsoft Public License</td>
    <td>Copylefted</td>
    <td>Copylefted</td>
    <td>Copylefted</td>
    <td>No</td>
    <td>Permissive</td>
    <td>No</td>
    <td>No</td>
  </tr>
   <tr>
    <td>MIT License</td>
    <td>Permissive</td>
    <td>Permissive</td>
    <td>Permissive</td>
    <td>Manually</td>
    <td>Yes</td>
    <td>Permissive</td>
    <td>Manually</td>
  </tr>
   <tr>
    <td>Mozilla Public License</td>
    <td>Permissive</td>
    <td>Copylefted</td>
    <td>Copylefted</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>Copylefted</td>
    <td>No</td>
  </tr>
  <tr>
    <td>WTFPL</td>
    <td>Permissive/Public domain</td>
    <td>Permissive/Public domain</td>
    <td>Permissive/Public domain</td>
    <td>No</td>
    <td>Yes</td>
    <td>Yes</td>
    <td>No</td>
  </tr>
</table>
<p style="font-size:9.5px;"><em>Source:https://choosealicense.com/licenses/</em></p>
<p class=message
  style="font-size:85%;">
<b>Linking:</b> licensed under a different license 
<br>
<b>Distribution:</b> Distribution of the code to third parties
<br>
<b>Modification:</b> Modification of the code by a licensee
<br>
<b>Patent Grant:</b> Protection of licensees/contributors from patent claims made by licensees and code contributors regarding their contribution.
<br>
<b>Private Use:</b> Whether modification to the code must be shared with the community or may be used privately
<br>
<b>Sublicensing:</b> Whether modified code may be licensed under a different license or must retain the same license under which it was provided
<br>
<b>Trademark Grant:</b> Use of trademarks associated with the licensed code or its contributors by a licensee
<br>
</p>

In addition to the above table, it would be helpful to look at the differences between copyleft and permissive license for a better understanding of the subject.
<table>
<tr>
    <th>Permissive License</th>
    <th>Copyleft License</th>
     </tr>
  <tr>
    <td>Requires users to include the original copyright notice and a copy of the license text.</td>
    <td>Has the same condition. However, it also, require users to offer the source code of any modifications to all recipients and  place those modifications under the same license.</td>
    </tr>
    <tr>
    <td>It is the right choice for making as easy and appealing as possible for others to use your code.</td>
    <td>It is a good fit to share improvements with the OSS community and  to commercialize your project.</td>
    </tr>
   <tr>
    <td>You don't have to worry about license compatibility.</td>
    <td>It is suitable, if you don't want your code made proprietary by someone else and to create a project within a community that tends to use a specific copyleft license.</td>
    </tr>
     <tr>
    <td>Examples:  <em>MIT License, Boost Software License (BSL),  Apache License 2.0,  Berkeley Source Distribution (BSD)  License</em> </td>
    <td> Examples: <em>GPL v2 and GPL v3, Affero GPL License (AGPL), Mozilla Public License 2.0,  CDDL (Common Development and Distribution License), Creative Commons (CC) license.</em> </td>
    </tr>
![archicad-github-banner](https://user-images.githubusercontent.com/79079633/148689482-3e3474ad-0770-4317-b001-00098a17ea2d.png)

![GitHub last commit](https://img.shields.io/github/last-commit/cryinkfly/Archicad-for-Linux?style=for-the-badge)
![GitHub issues](https://img.shields.io/github/issues-raw/cryinkfly/Archicad-for-Linux?style=for-the-badge)
![GitHub Repo stars](https://img.shields.io/github/stars/cryinkfly/Archicad-for-Linux?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/cryinkfly/Archicad-for-Linux?style=for-the-badge)
![GitHub](https://img.shields.io/github/license/cryinkfly/Archicad-for-Linux?style=for-the-badge)

Archicad is a model-based CAD program for architects that works according to the building data modeling method and saves project information such as floor plans, sections, views, evaluations and room books in a file. In this way, when changes are made to the model, all relevant data such as the number of components and the calculated costs are automatically adjusted.

But the problem is that this program only works on computers that have Windows or macOS system installed!

So that people like me can still use this program under Linux, I decided to create this project here on my GitHub-Channel.

With this it will also be possible in the future to use this software also on various Linux distributions such as openSUSE Leap, Ubuntu or Fedora.

Is that a great idea for the future?

Personally, I think this idea is good and for this reason I will do my best to give you the opportunity to use it on Linux as well!

---

You will get more information about this program, then you can visit the original website of Archicad with this link: https://graphisoft.com/de/archicad

---

- 📂 Downloads: Still in Progress!
  - 📔 Documentation: Still in Progress!
  - 💬 Would You like to get in touch with me? Or if You have any questions, suggestions or problems?
  - 📫 Then You can create an [issue](https://github.com/cryinkfly/Archicad-for-Linux/issues) here on GitHub or You visit my <a href="https://cryinkfly.com">website</a> and get in touch with me!
  - 📜 Code of Conduct: Contributor Covenant (Still in Progress!)
  - 📖 Information for contributors: All contribution information, Compilation instructions, Roadmap (Still in Progress!)
  - ❤️ I'd like to thank everyone who has [helped](https://github.com/cryinkfly/Archicad-for-Linux/blob/main/COMMUNITY.md) me to get Archicad up and running on Linux!
  - 🍷 Super Application Maintainer (WineHQ): Still in Progress!

---

## Screenshots
<div>
<img src="https://github.com/cryinkfly/Archicad-for-Linux/blob/main/files/images/BIMx%20Desktop%20Viewer/bimx-demo-project-2d-view-5.png?raw=true" width="300px" height="200px">
<img src="https://github.com/cryinkfly/Archicad-for-Linux/blob/main/files/images/BIMx%20Desktop%20Viewer/bimx-demo-project-overview.png?raw=true" width="300px" height="200px">
</div>
<div>
<img src="https://github.com/cryinkfly/Archicad-for-Linux/blob/main/files/images/BIMx%20Desktop%20Viewer/bimx-demo-project-3d-view-2.png?raw=true" width="300px" height="200px">
<img src="https://github.com/cryinkfly/Archicad-for-Linux/blob/main/files/images/BIMx%20Desktop%20Viewer/bimx-demo-project-2d-view-0.png?raw=true" width="300px" height="200px">
</div>

---

## Downloads

Still in Progress!

---

## Hardware and Software Requirements

- Internet connection (Cable/DSL speeds recommended)!
- Latest Ubuntu LTS, Fedora, Debian, Manjaro, openSUSE Leap, fully updated!
- Latest graphics driver!
- Some packages (p7zip, p7zip-full, p7zip-rar, curl, wget, winbind, cabextract, wine, wine-mono, wine_gecko & winetricks)
- Winetricks packages msxml4 msxml6 vcrun2019!

---

## Getting Started

Install Archicad for Linux client:

1.) Check my GitHub-Documentation (Still in Progress)!

2.) Open your web browser and log into the [Archicad website](https://graphisoftid.graphisoft.com/Account/ServiceLogin?Application=GRAPHISOFT&ReturnUrl=https://graphisoft.com/de/archicad).

3.) Download the installation file.

4.) Open a terminal and run this command:

    mkdir -p /$HOME/.wineprefixes/archiad && cd ~/Downloads && wget -N https://raw.githubusercontent.com/Winetricks/winetricks/master/src/winetricks && chmod +x winetricks && WINEPREFIX=$HOME/.wineprefixes/archicad sh winetricks -q msxml4 msxml6 vcrun2019

5.) Install Archicad with this command:

    WINEPREFIX=$HOME/.wineprefixes/archicad winecomsole ARCHICAD*.exe

3.) Now, You can use BIMx Desktop Viewer on your Linux system, but not Archicad at the moment!

---

## Which work areas and functions have I tested:

<table>
<thead>
<tr>
<th></th>
<th>Windows</th>
<th>Linux</th>
</tr>
</thead>
<tbody>
<tr>
<td>Installation worked!</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
  </tr>
<tr>
<td>BIMx Desktop Viewer worked!</td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td style="text-align: center;"><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
  </tr>
<tr>
<td>Archicad</td>
<td><g-emoji class="g-emoji" alias="heavy_check_mark" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png"><img class="emoji" alt="heavy_check_mark" src="https://github.githubassets.com/images/icons/emoji/unicode/2714.png" width="20" height="20"></g-emoji></td>
<td><g-emoji class="g-emoji" alias="heavy_multiplication_x" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/2716.png"><img class="emoji" alt="heavy_multiplication_x" src="https://github.githubassets.com/images/icons/emoji/unicode/2716.png" width="20" height="20"></g-emoji></td>
</tr>
</tbody>
</table>

---

## Important Notice

With the help of my script, You get a way to install Archicad on your Linux system. 

Certain packages and programs that are required will be set up for You, but it's important to know, that my script only helps You to get the program to run and nothing more! 

And so, You must to purchase the licenses directly from the manufacturer of the program Archicad!

---

## License

All my scripts are released under the MIT license, see <a href="https://github.com/cryinkfly/Archicad-for-Linux/blob/main/LICENSE.md">LICENSE.md</a> for full text.

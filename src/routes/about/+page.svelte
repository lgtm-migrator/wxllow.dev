<script>
    let socials = [
            {
                "name": "Discord", 
                "href": "https://discord.com/users/229710046706139139",
                "text": "willow#6969 (229710046706139139)",
            },
            {
                "name": "GitHub", 
                "href": "https://github.com/wxllow",
                "text": "wxllow"
            },
            {
                "name": "YouTube",
                "href": "https://www.youtube.com/channel/UCzTTeq0NBEUnDTULDWWwvwA",
                "text": "wxllow",
            },
            {
                "name": "Steam", 
                "href": "https://steamcommunity.com/id/wxllow/",
                "text": "wxllow",
            },
            {
                "name": "Xbox", 
                "href": "https://account.xbox.com/en-us/profile?gamertag=wxllowxy",
                "text": "wxllowxy",
            },
        ];
</script>

<h1 class="text-5xl font-bold sidelines">About</h1>
<ul class="list-outside list-disc text-left">
    <li>👋 Name: Willow</li>
    <li>♀ Pronouns: she/they </li>
    <li>🌐 Location: United States</li>
    <li><span class="text-yellow-400">✦ </span>Ethnicity: Latina</li>
    <li>🎂 Birthday: November 17</li>
</ul>

<h2 class="text-4xl font-bold">Social Media</h2>
<ul class="">
    {#each socials as {name, href, text}}
    <li>
        <h3 class="text-2xl">{name}</h3>
        <a {href} target="_blank" class="text-sky-400">{text}</a>
    </li>
    {/each}
</ul>

<h2 class="text-4xl font-bold">Favorite Artists (Not in order)</h2>
<ul>
    <li>Brent Faiyaz</li>
    <li>Clairo</li>
    <li>Cuco</li>
    <li>Deftones</li>
    <li>Earl Sweatshirt</li>
    <li>Frank Ocean</li>
    <li>Gorillaz</li>
    <li>Kali Uchis</li>
    <li>Kanye West</li>
    <li>MF DOOM</li>
    <li>Mac Demarco</li>
    <li>Mac Miller</li>
    <li>Mitski</li>
    <li>Nirvana</li>
    <li>The Beatles</li>
    <li>The Weeknd</li>
    <li>Tyler, The Creator</li>
</ul>

<h2 class="text-4xl font-bold">Software Recommendations (Cross-platform)</h2>
<ul>
    <li>mpv - Lightweight media player</li>
    <li>GIMP - Image Editor (like Photoshop)</li>
    <li>Krita - Image Editor, more oriented for art</li>
    <li>Inkscape - Vector Editor (like Adobe Illustrator)</li>
    <li>Kdenlive - Video Editor <span class="italic">(Lacking and source only for some platforms)</span></li>
    <li>Davinci Resolve - Video Editor <span class="italic">(NOT OPEN SOURCE; Free and paid tiers; Good video editor for Linux though)</span></li>
</ul>

<h2 class="text-4xl font-bold">Software Recommendations (Linux)</h2>
<ul>
    <li>AwesomeWM - Window Manager</li>
    <li>KDE Plasma - Desktop Environment (If you're not comfortable using WM)</li>
    <li>Polybar - Status bar</li>
    <li>Kitty - Fast, GPU-accelerated terminal</li>
    <li>Alacritty - Another fast, GPU-accelerated terminal except more faster (and suckless)</li>
    <li>Rofi - Window Switcher + Application Launcher</li>
    <li>Feh - Lightweight Image Viewer</li>
    <li>Dolphin - GUI File Manager</li>
    <li>Ark - GUI Archive Manager</li>
    <li>Bottles - WINE/Proton Bottles Manager</li>
    <li>Virt Manager (with QEMU/KVM) - Virtual Machines</li>
    <li>Virtual Box - Virtual Machines: More beginner friendly than using QEMU/KVM, but more lacking and less performant</li>
</ul>

<h2 class="text-4xl font-bold">Linux Distro Recommendations</h2>
<ul>
    <li>Arch Linux - For experienced Linux users: Lightweight, make the OS yours, bleeding-edge, the AUR is amazing, up to date repos, nice wiki, somewhat complex installation</li>
    <li>Artix Linux - For experienced Linux users: Arch sans systemd; also has some nice installers with DE included</li>
    <li>EndeavourOS - Arch for "beginners"; still will require basic terminal knowledge</li>
    <li>Linux Mint - Amazing beginners distro; easy to use, based on Ubuntu, includes important applications</li>
    <li>AmogOS</li>
    <li>Hannah Montana Linux</li>
</ul>

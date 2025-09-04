<h1>Vintage Story Launcher (Dev)</h1>
<p>&nbsp;</p>
<div style="display: flex; gap: 6px; flex-wrap: wrap; align-items: center; margin: 8px 0 0;"><img src="https://img.shields.io/github/v/release/NoahBRostant/VintageStoryLauncher?include_prereleases&amp;sort=semver&amp;display_name=tag&amp;style=for-the-badge" alt="GitHub Release" /> <img src="https://img.shields.io/github/downloads/NoahBRostant/VintageStoryLauncher/total?style=for-the-badge" alt="GitHub Downloads (all assets, all releases)" /></div>
<div style="border-left: 4px solid #d35400; background: #fff6e8; padding: 12px 14px; margin: 16px 0;" data-darkreader-inline-border-left="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage=""><strong>Development status:</strong> This launcher is actively developed. New features and polish are arriving regularly. There may be breaking changes between versions.</div>
<div style="border-left: 4px solid #c0392b; background: #fff3f3; padding: 12px 14px; margin: 16px 0;" data-darkreader-inline-border-left="" data-darkreader-inline-bgcolor="" data-darkreader-inline-bgimage=""><strong>Important:</strong> Please <strong>back up your saves</strong> before using the launcher. See <a href="#backup-090">Backup Instructions (v0.9.0+)</a> and <a href="#backup-legacy">Legacy Backup</a> below.</div>
<h2>Platform Status</h2>
<ul>
<li><strong>Linux:</strong> Supported and tested on Ubuntu 20.04+, Debian 11+, Fedora 38+.</li>
<li><strong>Windows:</strong> Builds currently unavailable. Windows support is planned for a future release.</li>
</ul>
<h2>Overview</h2>
<p>The Vintage Story Launcher is an <em>unofficial</em>, feature‑rich companion app that helps you manage game versions, isolated play instances, and mods with ease. The interface is built in <strong>Godot</strong> for a thematic, game‑like feel, while core operations are implemented in <strong>Rust</strong> (via GDExtension) for speed, safety, and reliability.</p>
<h2>Key Features</h2>
<ul>
<li><strong>Multi‑Instance Management:</strong> Create fully separate installations for different worlds, servers, or mod sets&mdash;ideal for testing or keeping survival and creative gameplay isolated.</li>
<li><strong>Per‑Instance Version Control:</strong> Download and switch game versions per instance. Quickly match server versions or run older mods without disrupting your main setup.</li>
<li><strong>Integrated Mod Manager:</strong> Enable/disable mods per instance. The launcher handles file organisation so you can focus on play, not folders.</li>
<li><strong>News Feed:</strong> See official Vintage Story updates directly on the home screen.</li>
<li><strong>*Thematic UI:</strong> A handcrafted interface designed to feel like a natural extension of the game.</li>
</ul>
<h2>Install Instructions</h2>
<ol>
<li><strong>Install Git</strong> (required to run the installer script).</li>
<li><strong>Download</strong> the release archive and extract it.</li>
<li><strong>Linux:</strong>
<ul>
<li>Open a terminal in the folder containing <code>install.sh</code> and run:<br /><code>chmod +x ./install.sh</code> then <code>./install.sh</code></li>
<li>Alternatively, set the file as executable from your file manager and double‑click it.</li>
</ul>
</li>
<li><strong>Windows:</strong> When Windows builds are available, run <code>install.sh</code> using Git Bash.</li>
<li>Follow the on‑screen prompts. Once installed, launch from your application menu.</li>
</ol>
<h2>Support Development</h2>
<p><a href="https://ko-fi.com/P5P5696XP" target="_blank" rel="noopener"> <img style="border: 0; height: 36px;" src="https://storage.ko-fi.com/cdn/kofi6.png?v=6" alt="Support on Ko-fi" height="36" data-darkreader-inline-border-top="" data-darkreader-inline-border-right="" data-darkreader-inline-border-bottom="" data-darkreader-inline-border-left="" /> </a></p>
<h2 id="backup-090">Backup Instructions (v0.9.0+)</h2>
<p><strong>Recommendation:</strong> Always back up your data before testing new launchers or major updates.</p>
<p>For v0.9.0 and above, back up your <code>instances</code> directory.</p>
<h3>Linux</h3>
<ul>
<li><strong>Terminal:</strong><br /><code>cp -r ~/.local/share/VintageStoryLauncher/instances/ ~/Desktop/</code><br />Replace <code>~/Desktop/</code> with your preferred backup destination.</li>
<li><strong>File Manager:</strong> Navigate to <code>~/.local/share/VintageStoryLauncher/</code>, copy the <code>instances</code> folder, and paste it into your backup location.</li>
</ul>
<h3>Windows</h3>
<ul>
<li>Windows builds are not yet available; no backup is required at this time. This section will be updated when a Windows release is published.</li>
</ul>
<h2 id="backup-legacy">Legacy Backup (pre‑v0.9.0)</h2>
<p>If you are using a version older than v0.9.0, back up your <code>VintageStoryData</code> directory.</p>
<h3>Linux</h3>
<ul>
<li><strong>Terminal:</strong><br /><code>cp -r ~/.config/VintageStoryData/ ~/Desktop/</code></li>
<li><strong>File Manager: </strong>Go to <code>~/.config/</code>, copy <code>VintageStoryData</code>, and paste it into your backup location.</li>
</ul>
<h3>Windows</h3>
<ul>
<li>Windows builds are not yet available; this section will be updated for Windows when releases are ready.</li>
</ul>
<h2>Report Issues</h2>
<p>Found a problem? Please use the GitHub Issue Tracker (link above) so I can address the issue efficiently. Include as much detail as possible:</p>
<ul>
<li><strong>App Version</strong></li>
<li><strong>OS</strong> (and <strong>Distro/DE</strong> on Linux)</li>
<li><strong>Issue Description</strong></li>
<li><strong>Steps to Reproduce</strong></li>
<li><strong>Log File</strong> (paste text or attach the file)</li>
</ul>

<h1>
  Ryujinx-HDR
</h1>
<h3>
  DISCLAIMER
</h3>
<p>
  This is an <b>unofficial</b> version of Ryujinx with experimental features! <b>DO NOT</b> go to Ryujinx devs or Discord server for support with this build. Direct any questions or concerns to Remshi#6348 on Discord or the #help-questions channel on the HewDraw Remix Discord server.
</p>
<h3>
  What is this??
</h3>
<p>
  This is a fork of <a href="https://github.com/Ryujinx/Ryujinx#readme">Ryujinx</a> that pulls in some pending PR changes to enable and optimize compatibility with the Smash Ultimate mod <a href="https://github.com/HDR-Development/HewDraw-Remix">HewDraw Remix</a>, or HDR. In theory, these changes are also compatible with / desired for any other Skyline/ARCropolis mods.
</p>
<p>
  Previously, HDR players needed to use a very outdated PR build of Ryujinx in order to play, so this fork seeks to provide an updated build that is not only compatible, but also pulls in additional (experimental) improvements that may further enhance the experience.
</p>
<p>
  For more information on HDR and installation instructions, visit their <a href="https://discord.gg/hdr">Discord</a>!
<h3>
  Usage notes
</h3>
<ul>
  <li>
    Ryujinx will automatically force-disable PPTC when necessary, so you can leave PPTC on in settings if you prefer <strike>PPTC should be <b>disabled</b> when playing HDR</strike>
  </li>
  <li>
    <b>Leave VSync on</b> while playing HDR or else your game will be sped up
  </li>
  <li>
    Graphics Backend Multithreading <i>should not</i> cause issues and should generally be left <b>on</b> <strike>Graphics Backend Multithreading can cause issues, especially with Nvidia GPUs. Consider disabling in Ryujinx and enabling driver-level multithreading instead</strike>
  </li>
  <li>
    Vulkan rendering is available in this build, but OpenGL is the default for safety/compatibility reasons
  </li>
  <li>
    You should probably keep this separate from your vanilla Ryujinx installation lol
  </li>
</ul>
<h3>
  List of merged PRs for nerds
</h3>
<ul>
  <li>
    https://github.com/Ryujinx/Ryujinx/pull/2966 (mod compatibility)
  </li>
  <li>
    https://github.com/Ryujinx/Ryujinx/pull/2518 (Vulkan support)
  </li>
</ul>

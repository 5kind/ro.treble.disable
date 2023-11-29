<h1 align="center">Disable ro.treble.enabled</h1>

<div align="center">
  <!-- Version -->
    <img src="https://img.shields.io/badge/Version-v1.0-blue.svg?longCache=true&style=popout-square"
      alt="Version" />
  <!-- Min Magisk -->
    <img src="https://img.shields.io/badge/MinMagisk-20.4-red.svg?longCache=true&style=flat-square"
      alt="_time_stamp_" />
  <!-- Min KSU -->
    <img src="https://img.shields.io/badge/MinKernelSU-0.6.6-red.svg?longCache=true&style=flat-square"
      alt="_time_stamp_" /></div>

<div align="center">
  <strong>resetprop ro.treble.enabled to false, and restore back true after later-start.
</div>

<div align="center">
  <h3>
    <a href="https://github.com/5kind/ro.treble.disable">
      Source Code
    </a>
  </h3>
</div>

### Usage
- Install install.zip by Magisk/KernelSU.

### Notice
- If you use a soft reboot, error report will come back since we [resetprop ro.treble.enabled](./service.sh) true when later-start, you can just delete serivce.sh.

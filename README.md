
<br />
<div align="center">
  <h3 align="center">Data Verify Forwarder</h3>

  <p align="center">
    A trusted third-party responsible for RP verification and data forward through the browser's front channel in ARPSSO. 
    <br />
    <a href="https://arpsso.hejunlin.cn"><strong>View ARPSSO Demo »</strong></a>
  </p>
</div>

This repository contains the source code of the Data Verify Forwarder (DVF). It contains three files:
- `index.html`: The home page for the DVF. It's responsible for in-browser communication with IdP and RP and calls the RP validation functions in `dvf.xxxxx.js`.
- `dvf.xxxxx.js`: The RP verification script. This script is packaged by `webpack` to ensure optimal transmission over the web. The source code is available [here](https://github.com/ARPSSO/DVF-js).
- `README.md`: This file.


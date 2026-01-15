---
pagetitle: Release Notes for ISM6HG256X Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for ISM6HG256X Component Driver
Copyright &copy; 2025 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the ISM6HG256X component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 17-Sep-2025</label>
<div>

## Main changes

### First release

- First official release [ref. DS v1.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V2.0.0 / 07-Oct-2025</label>
<div>

## Main changes

- Add routine to reset SFLP game rotation logic

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V3.0.0 / 05-Nov-2025</label>
<div>

## Main changes

- Upgrade reset APIs

##

</div>

<input type="checkbox" id="collapse-section4" checked aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V4.0.0 / 15-Jan-2026</label>
<div>

## Main changes

- Convert I2C address representation from 7-bit to 8-bit in sensor-hub
- Add haodr_set, xl_setup and gy_setup to comply with the AN
- Fix docs: typo in filt_xl_setup, hg_xl_data_rate_set
- Split pin_int for clearer configuration
- Fix pad_strength values
- Add missing variant (1.875Hz) for sh_data_rate enum
- Fix bit masking in ois_gy_full_scale_set API
- Fix reboot by restoring previous data rates after reboot
- Fix filt_wkup_act_feed enum values
- Add check on idx for sensor-hub target
- Add constraints while changing eis odr
- Add filt_xl_setup API to handle filter lpf2 settings
- Add power-off gyro when changing the full-scale (ui and eis)
- Fix type for x/y/z_ofs_usr. Change type from uint8_t to int8_t
- Add read for ctrl9 in xl_offset_mg_set and improved doc

##

</div>
:::



:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on ISM6HG256X,
visit:
[ISM6HG256X](https://www.st.com/content/st_com/en/products/mems-and-sensors/inemo-inertial-modules/ism6hg256x.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 1.0">Info</abbr>
:::
:::
</footer>

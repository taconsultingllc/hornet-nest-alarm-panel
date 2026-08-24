
<div align="right">
  <details>
    <summary >🌐 Language</summary>
    <div>
      <div align="center">
        <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=en">English</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=zh-CN">简体中文</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=zh-TW">繁體中文</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=ja">日本語</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=ko">한국어</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=hi">हिन्दी</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=th">ไทย</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=fr">Français</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=de">Deutsch</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=es">Español</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=it">Italiano</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=ru">Русский</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=pt">Português</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=nl">Nederlands</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=pl">Polski</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=ar">العربية</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=fa">فارسی</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=tr">Türkçe</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=vi">Tiếng Việt</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=id">Bahasa Indonesia</a>
        | <a href="https://openaitx.github.io/view.html?user=taconsultingllc&project=hornet-nest-alarm-panel&lang=as">অসমীয়া</
      </div>
    </div>
  </details>
</div>

# Hornet Nest Alarm Panel for ESPHome

This repository houses the officially supported **ESPHome** firmware configuration files for the **Hornet Nest Alarm Panel**, developed by **Technology Automation Consulting LLC**. The Hornet Nest Alarm Panel is a scalable and customizable IoT solution designed to integrate traditional wired alarm systems into your smart home using **Home Assistant**. With 42 optoisolated zones, 3 relay outputs, and flexible PoE or 12V power options, it’s built for flexibility and reliability.

[![Where to Buy](https://img.shields.io/badge/Where%20to%20Buy-Direct%20Store%20(Discounted)-blue?style=for-the-badge)](https://byproduct.taconsulting.llc)

## Where to Buy

The **Hornet Nest Alarm Panel** is available for direct purchase from our official store at a reduced price:

* **Official Store:** [byproduct.taconsulting.llc](https://byproduct.taconsulting.llc) *(Direct pricing near original crowdfunding rates — save ~$50 compared to third-party distributors)*
* **Distributors:** [Crowd Supply](https://www.crowdsupply.com) | [Mouser Electronics](https://www.mouser.com)
  
<div style="display: flex; justify-content: space-between;">
  <img src="images/3D_AlarmPanel_2024-10-06.png" alt="3D Model" width="400"/>
  <img src="images/hornet-nest-operational.jpg" alt="Installed" width="400"/>
</div>

## Quick Start

Get started quickly by adopting and flashing your Hornet Nest Alarm Panel with the latest ESPHome firmware:

1. Plug a PoE powered ethernet cable into the Hornet Nest Alarm Panel.
2. Open the **ESPHome Dashboard** and locate the device "hornet-nest-XXXXXX" (where XXXXXX is a unique hexadecimal identifier).
3. Click on the **Adopt** option on the device.
4. The **Adopt Device** dialog will open.  You can rename your device if desired and then click the **Adopt** option again.
5. The **Configuration Created** dialog will open and indicate that a new configuration needs to be installed on the device, click the **Install** button.
6. ESPHome will begin to compile the new firmware. When the line **"INFO Sucessfully uploaded program."** is diplayed, click **STOP** to close the window.
4. Discover the Hornet Nest Alarm Panel in **Home Assistant** > **Settings** > **Devices & Services**.
5. Click **Configure** on the new device to add it into Home Assistant.

## Changes and Release Notes

See **Releases** for release notes and downloadable pre-built firmware images.

## Made for ESPHome

The **Hornet Nest Alarm Panel** uses the **wESP32 PoE** microcontroller and is fully compatible with **ESPHome** firmware. It is an open-source product, designed for easy user customization, making it ideal for Home Assistant users who need a scalable and flexible alarm solution. The included **ESPHome YAML configuration files** are fully documented, allowing advanced users to easily customize, build, and update their device with a few simple modifications.

## Works with Home Assistant

These **ESPHome** firmware configurations allow for a simple, plug-and-play setup within **Home Assistant**. The integration is local, fast, and fully customizable, giving users complete control over their home security system.
<img src="images/esphome-integrated.png" alt="ESPHome Device" width="600">

## In This Repository

This repository contains **complete firmware configuration YAML templates** for the **Hornet Nest Alarm Panel** at the top level. These templates are ready to be imported using **ESPHome Dashboard**, where they can be customized and deployed.

## User Manual

For detailed instructions, please refer to the official user manual [here.](hnap-user-manual.pdf)

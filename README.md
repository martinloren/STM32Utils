# STM32Utils
Official STM32Utils app repository.

This repository contain the firmware showing in the <a href="https://play.google.com/store/apps/details?id=com.martinloren.stm32utils">STM32Utils app</a> under the vendor < Generic >.


## Adding your project
You can add your STM32 project and firmware. What you need is:

1) Create a New Pull Request on this repo\
2) Include your .bin firmware in the fw/ folder\
3) Add a new entry in the file firmware_list.json

### JSON Format
~~~
{
  "title": "Title of your project",
  "subtitle": "STM32F103C8T6 (MCU used) | category (eg. Utility, Device, Module,...)",
  "description": "Project description",
  "article": "Link to your project page",
  "versions": [
    {
      "date": "2019-01-25T12:54:44Z",
      "prerelease": false,
      "name": "v1",
      "url": "https://github.com/martinloren/STM32Utils/raw/master/fw/(your_firmware_filename).bin"
    }
  ]
}
~~~

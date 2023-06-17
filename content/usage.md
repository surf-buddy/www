+++
layout = 'staticpage'
title = 'Usage'
background = 'wave-1920x1080.jpg'

[content]
  [[content.pages]]
    headline = 'Spot name'
    id = 'spotname'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: text
    example: Pipeline

The *Spot name* setting sets the spot name to get surfing information for. After changing the spot name and saving the settings you may need to wait a couple of minutes until new data can be pulled from the SurfBuddy API servers.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Latitude/ Longitude Hint'
    id = 'latlonhint'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: real numbers
    example: 19.5

The *Latitude Hint* and *Longitude Hint* settings allow to decide for a single spot if the [Spot name](#spotname) results in two or more identically named spots.

The spot with the smallest distance to the hinted latitude and longitude will be chosen.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Info Type'
    id = 'infotype'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: [Sun, Tide]
    example-value: Sun
The *Info Type* allows to switch between displaying the sunrise and sunset time and the time and height of the next two tide extremes.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'

  [[content.pages]]
    headline = 'Plot Type'
    id = 'plottype'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: [Tides, Wave, Wind]
    example-value: Tides
The *Plot Type* allows to switch between displaying the daily tide chart, a wave forecast chart for the next 7 days and a wind forecast chart.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Display seconds'
    id = 'displayseconds'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: boolean 
    example-value: <disabled>
*Display seconds* allows to add a second indicator on the watch. Enabling this feature makes a portion of the screen being rendered at a higher frequency. Thus it will drain the battery faster.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Plot Style'
    id = 'plotstyle'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: [Bar, Segments]
    example-value: Bar

*Plot Style* switches how the data is being displayed in the chart. `Bar` is for single bars at each value, `Segments` displays a filled curve with colored segments.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Unit for Wave Elevation'
    id = 'unitforwaveelevation'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: [System Default, Meters, Feet]
    example-value: System Default

*Unit for Wave Elevation* switches between the different units for tide height and wave elevation. `System Default` means to choose the unit that is the default for your watch.

> In the future release there might be an extra option to set the *Unit for Tide Elevation*.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Unit for Wind Speed'
    id = 'unitforwindspeed'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: [Kph, Knots, Mph]
    example-value: Kph

*Unit for Wind Speed* switches between the different units for displaying wind speed. 
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Military Format for 24 Hour Time'
    id = 'militaryformat'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: boolean 
    example-value: <disabled>

*Military Format for 24 Hour Time* can enable military time format, e.g. displaying **0900** instead of **9:00**.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Forecast Time'
    id = 'forecasttime'
    image = 'watchface.png'
    image-right = true
    page_content = """
    data-type: [Spot, Local]
    example-value: Spot

When in a different time zone than the currently set surf spot, *Forecast Time* can switch between displaying your local time or the spots time in the forecast information.

*Note: it will not change the watch time, that remains your local time*. 
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'Color Settings'
    id = 'colorsettings'
    image = 'watchface.png'
    image-right = true
    page_content = """
There are eight different color settings that each change the appearance of the watchface.
"""
    [[content.pages.buttons]]
      label = 'Download SurfBuddy'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'

+++


+++
title = 'Home'
background = 'wave-1920x1080.jpg'

[content]
  [[content.pages]]
    headline = 'SurfBuddy'
    id = 'surfbuddy'
    image = 'watchface.png'
    image-right = true
    link_info = 'Support me an learn more about the watchface and how to use it.'
    [[content.pages.paragraphs]]
      content = 'The SurfBuddy watchface is a newly desgined watchface for surfing information.'
    [[content.pages.buttons]]
      label = 'Download'
      href = 'https://apps.garmin.com/en-US/apps/ad6f857d-2f85-4551-885c-d5efa1fb0e3c'
    [[content.pages.buttons]]
      label = 'Support me'
      href = 'https://www.buymeacoffee.com/JanSurft'
  [[content.pages]]
    headline = 'How does it work?'
    id = 'how-does-it-work'
    image = 'surfbuddy-arch.png'
    link_info = 'If you want to learn more about the functionality of the service'
    [[content.pages.paragraphs]]
      content = 'The watchface gets the forecast information from the SurfBuddy API that caches and transforms forecast responses from external services. At the moment this is mostly Surfline in combination with a GeoCity location service.'
    [[content.pages.paragraphs]]
      content = 'The SurfBuddy API is crucial, because responses from forecasting services do not adhere to the limited size requirements of the Garmin watchfaces.'
    [[content.pages.buttons]]
      label = 'Learn more'
      href = '#'
  [[content.pages]]
    headline = 'Install SurfBuddy'
    id = 'install-surfbuddy'
    image = 'surfbuddy-install.gif'
    image_class = 'phone'
    image_bg = 'phone-background-solid.png'
    image-right = true
    link_info = 'Learn more about the usage of the watchface'
    [[content.pages.buttons]]
      label = 'More about usage'
      href = '/usage/'
    [[content.pages.paragraphs]]
      content = 'You can install SurfBuddy via you mobile with the following sequence of actions:'
    [[content.pages.items]]
      content = 'open connect IQ app'
    [[content.pages.items]]
      content = 'select "Search"'
    [[content.pages.items]]
      content = 'In the search field enter "surfbuddy"'
    [[content.pages.items]]
      content = 'Select the watchface from the list of results'
    [[content.pages.items]]
      content = 'Select "Install"'
    [[content.pages.items]]
      content = 'Click on "Allow" for the app requirements'
  [[content.pages]]
    headline = 'Set Surf Spot'
    id = 'set-surf-spot'
    image = 'surfbuddy-set-spot.gif'
    image_class = 'phone'
    image_bg = 'phone-background-solid.png'
    image-right = true
    link_info = '...'
    [[content.pages.items]]
      content = 'open connect IQ app'
    [[content.pages.items]]
      content = 'select "My Device"'
    [[content.pages.items]]
      content = 'select "My Watch Faces"'
    [[content.pages.items]]
      content = 'select "SurfBuddy"'
    [[content.pages.items]]
      content = 'select "Settings"'
    [[content.pages.items]]
      content = 'change the "Spot name" attribute'
    [[content.pages.items]]
      content = 'select "Save"'
  [[content.pages]]
    headline = 'FAQ'
    type = 'faq-static.html'
    id = 'faq'
    image = ''
    [[content.pages.questions]]
      question = 'Which spotnames can be used?'
      answer = 'Currently the watchface is using surfline for forecast information, so any spotname that is listed there works for SurfBuddy.'
    [[content.pages.questions]]
      question = 'What are the latitude and longitude names about?'
      answer = 'There are multiple surfspots sharing the same name, e.g. there is a "La Pared" in Spain and a "La Pared" in Puerte Rico. By setting the location hint the spot that is nearest to the hinted location will be chosen.'
    [[content.pages.questions]]
      question = 'There is no information displayed when I change the spotname, what can I do?'
      answer = 'There is a technical limitation for watchfaces: Background requests to the internet can only be executed every 5 minutes. So wait at least five minutes for the background request to be completed.'

+++

---
title: "Gallery"
date: 2021-08-26T15:49:44+02:00
draft: false
---

# Navigation
  [params.navigation]
    brand = ""
    img = "SiyaNoku.png"
    home = "Home"
    work = "Gallery"
    testimonials = "Testimonials"
    services = "Companies"
    about = "About"
    contact = "Contact"

    # You can add custom links before or after the default links
    # Assign a weight to define the order
    
    # prepended links
    [[menu.prepend]]
     url = "/work/"
     name = "Gallery"
     weight = 1

    # postpended links
    #[[menu.postpend]]
     #url = "http://gohugo.io"
      #weight = 5


    
    
 
  # Intro section
  # Available icons: http://simplelineicons.com/
  [params.intro]

  

  [[params.intro.item]]
    title = "Vision"
    description = "To be a supplier of choice in the built and maintenance programme in the continent  that contribute in reducing unemployment, providing platform for empowerment and exposure to the women, youth and people with disabilities."
    url = "#"
    #button = "View"
    #icon = "icon-wrench"
    icon = "icon-building-o"
    img = "green-card.jpg"

  [[params.intro.item]]
    title = "Mission"
    description = "The business mission is to exploit the localisation programmes to build a formidable supplier company that participate meaningfully within the built industry to create job opportunities, especially for women, youth and people with disability, maximise its profit margins."
    url = "#"
    #button = "view"
    icon = "icon-bulb"
    img = "green-card.jpg"

  [[params.intro.item]]
    title = "Value"
    description = "Siyanoku Trading Enterprise is guided by the following ideals or values:	integrity, honesty, professionalism, mutualism, life learning and timeous in quality delivery and interventions                          "
    url = "#"
    #button = "View"
    #icon = "icon-wrench"
    icon = "icon-grid"
    img = "green-card.jpg"

  

 
  # Testimonials section
  [params.testimonials]
    enable = false
    title = "Testimonials"
    description = "Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts."

    [[params.testimonials.item]]
      quote = "&ldquo;Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean.&rdquo;"
      person = 'Jean Doe, CEO <a href="http://freehtml5.co/" target="_blank">FREEHTML5.co</a> <span class="subtext">Creative Director</span>'
      img = "person1.jpg"
      alt = "Person1"

    [[params.testimonials.item]]
      quote = "&ldquo;Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. Separated they live in Bookmarksgrove right at the coast of the Semantics, a large language ocean. Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts.&rdquo;"
      person = 'John Doe, Senior UI <a href="http://freehtml5.co/" target="_blank">FREEHTML5.co</a> <span class="subtext">Creative Director</span>'
      img = "person2.jpg"
      alt = "Person2"

    [[params.testimonials.item]]
      quote = "&ldquo;Far far away, behind the word mountains, far from the countries Vokalia and Consonantia, there live the blind texts. &rdquo;"
      person = 'Chris Nash, Director <a href="http://freehtml5.co/" target="_blank">FREEHTML5.co</a> <span class="subtext">Creative Director</span>'
      img = "person3.jpg"
      alt = "Person3"
    
  # Services section
  [params.services]
    enable = true
    title = "Our Companies"
    description = "We also offer other services within our other companies."

    [[params.services.item]]
      title = "Siyanoku Plant Hire"
      description = "Heavy Machinery"
       icon = "icon-gear"
    [[params.services.item]]
      title = "Siyanoku Energy"
      description = "Diesel/Diesel tank cleaning, Renewable energy"
       icon = "icon-energy"
    [[params.services.item]]
      title = "Hazy Dazy"
      description = "Furniture, Stationery and General Supply"
      icon = "icon-notebook"
      [[params.services.item]]
      title = "BNS"
      description = "Construction and Civil Work"      
      icon = "icon-user"

      [[params.services.item]]
      title = "Rozolo"
      description = "Steel Supplier"      
      icon = "icon-tag"

      [[params.services.item]]
      title = "Monasana Readymix & Aggremates"
      description = "Concrete and Stone Crusher"
     icon = "icon-road"

       # Work section
  [params.work]
    enable = true
    title = "Gallery"
    description = "View of our past projects from all our companies "
    

    [[params.work.row]]
      img = "work_1.jpg"
      alt = "Image2"
      title = "Transnet"
      subtitle = ""

    [[params.work.row]]
      img = "work_1.jpg"
      alt = "Image2"
      title = "Mount Gray"
      subtitle = ""

    [[params.work.row]]
      img = "work_1.jpg"
      alt = "Image3"
      title = "George"
      subtitle = ""

    [[params.work.row]]
      img = "work_1.jpg"
      alt = "Image4"
      title = "East Wing Solar"
      subtitle = ""

    [[params.work.row]]
      img = "work_1.jpg"
      alt = "Image5"
      title = "Uptown"
      subtitle = ""

  # About section
  [params.about]
    enable = true
    title = "About"
    description = " We are a business registered as a close corporation and totally dedicated to affirmative action and 100% commitment to our work. Care is taken to ensure that all personnel employed comply with the necessary requirements and high standard that the Siyanoku Trading Enterprise clients requires."

   [[params.about.item]]
      name = "Ms Bridget Ndlovu"
      position = "Director"
      description = "Founder of Siyanoku Trading Enterprise"
      # img = "person4.jpg"
      # alt = "Person2"
      # social = [ ]
      

        

  # Counters section
  [params.counters]
    enable = false
    title = "Stats"
    background = "full_image_1.jpg"

    [[params.counters.item]]
      description = "Finished projects"
      icon = "icon-briefcase"
      from = 0
      to = 89
      interval = 50
      speed = 5000

    [[params.counters.item]]
      description = "Lines of code"
      icon = "icon-code"
      from = 0
      to = 2343409
      interval = 50
      speed = 5000

    [[params.counters.item]]
      description = "Cups of coffee"
      icon = "icon-cup"
      from = 0
      to = 1302
      interval = 50
      speed = 5000

    [[params.counters.item]]
      description = "Happy clients"
      icon = "icon-people"
      from = 0
      to = 52
      interval = 50
      speed = 5000

  # Contact section
  [params.contact]
    enable = true
    map = false
    form = true
    title = "Get in touch"
    description = "with us "
    
    # Available icons: http://simplelineicons.com/
    details = [
        ["icon-building-o", "Rocky Drift White River, 1240"],
        ["icon-phone", "(013) 591-2783"],
        ["icon-envelope", "Siyanoku@gmail.com"],
        
      ]

    name = "Name*"
    email = "Email*"
    company = "Contact Company e.g Plant Hire"
    message = "Message*"
    button = "Send message"

  # Footer section
  [params.footer]
    enable = false
    copyright = '&copy; Elate Free HTML5. All Rights Reserved. <br>Created by <a href="http://freehtml5.co/" target="_blank">FREEHTML5.co</a> Images: <a href="http://pexels.com/" target="_blank">Pexels</a>, <a href="http://plmd.me/" target="_blank">plmd.me</a> <br>Hugo port by: <a href="https://github.com/saey55" target="_blank">saey55</a>'
    links = [
        ["icon-twitter", "#twitter"],
        ["icon-facebook", "#facebook"],
        ["icon-youtube", "#youtube"]
      ]
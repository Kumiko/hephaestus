# hephaestus
A web-based transportplatform with map, touch and offline-cache capabilities

Thoughts
Yahoo maps api
  REST for online -> offline -> online capability
HTML5
  Application Cache for offline use
Security/gui
  the first version will only support a oneuser setup with open id or something like it for easy setup.
  early it will be possible to adapt the driver gui to specific job types.
  there will be a possibillity to create a "company" with administrators/dispatchers and driver wievs.
  Sometime there will even be a function for creating printertemplates and print them ofc.
Jobs
  For reccuring freights it will be possible to adapt the driver gui.
  This will make it possible to filter out specific freightinformation for specific job types.
  
  Freight: (Each freight will have the following attributes)
    Reciever
      Name/Copmany
      Referee
      Phone
      Adress
      Country
    Sender
      Name/Company
      Referee
      Phone
      Adress
      Country
    Goods(there can be many goods in one freight)
      Amount
      Amount not loaded
      Weight
      Size(lenght/mass)
      Handling(climate requirements or dangerous goods)
      Value(mostly for customs)
      Pickup
        Date
        Time(specific/span)
        Instructions
      Delivery
        Date
        Time(specific/span)
        Instructions
      Status
        Registerd(by admin)
        Accepted(by driver)
        Rejected(by driver)
        Retrieved
        Stationary
        Deliverd
        Refused delivery
        Not reachable
        Damaged goods

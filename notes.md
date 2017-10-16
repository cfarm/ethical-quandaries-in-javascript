## Sources

- [Geolocation API spec from w3.org](https://www.w3.org/TR/geolocation-API/#privacy_for_recipients)
  > Recipients must only request location information when necessary. Recipients must only use the location information for the task for which it was provided to them. Recipients must dispose of location information once that task is completed, unless expressly permitted to retain it by the user. Recipients must also take measures to protect this information against unauthorized access. If location information is stored, users should be allowed to update and delete this information.

- [Building Web Apps that Respect A User's Privacy and Security](https://github.com/ascott1/ethical-web-dev/tree/master/web-apps-privacy-security)

## Questions to answer

### [How do browsers know our location?](https://en.wikipedia.org/wiki/W3C_Geolocation_API): 

  > The most common sources of location information are IP address, Wi-Fi and Bluetooth MAC address, radio-frequency identification (RFID), Wi-Fi connection location, or device Global Positioning System (GPS) and GSM/CDMA cell IDs. The location is returned with a given accuracy depending on the best location information source available.

...

> GPS (Global Positioning System): This happens for any device which has GPS capabilities. A smartphone with GPS capabilities and set to high accuracy mode will be likely to obtain the location data from this. GPS calculate location information from the satellite signal. It has the highest accuracy; in most Android smartphones, the accuracy can be up to 10 metres.
  
  > Mobile Network Location: Mobile phone tracking is used if a cellphone or wireless modem is used without a GPS chip built in.
  
  > WiFi Positioning System: If WiFi is used indoors, a Wi-Fi positioning system is the likeliest source. Some WiFi spots have location services capabilities.
  
  > IP Address Location: Location is detected based on nearest Public IP Address on a device (which can be a computer, the router it is connected to, or the ISP the router uses). The location depends on the IP information available, but in many cases where the IP is hidden behind Internet Service Provider NAT, the accuracy is only to the level of a city, region or even country.

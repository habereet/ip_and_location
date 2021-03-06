# ip_and_location

* Installing the requirements: python -m pip install -r requirements.txt
* Run by using python get_and_store_loc.py

Runs only on Android devices 
* Requires [Termux](https://play.google.com/store/apps/details?id=com.termux) and [Termux API](https://play.google.com/store/apps/details?id=com.termux.api)
* After installing both, open Termux and run the following command: ```apt install termux-api```

You will need an [API Key for Google Maps' API](https://developers.google.com/maps/documentation/geocoding/get-api-key).

Ensure that the key has access to the [Geocoding API](https://developers.google.com/maps/documentation/geocoding/overview)

## To-Do
- [X] Convert Lat-Long to Address
- [X] Store if on Wi-Fi or Mobile Signal
- [X] Comment code!
- [X] Add caching implementation for addresses
- [ ] Store results -> Google Sheet
- [ ] See how easy it is to add speedtest results to above
- [ ] Implement with Tasker

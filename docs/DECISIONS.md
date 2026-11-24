
TfL Unified API: https://api.tfl.gov.uk/ (you already have your key from https://api-portal.tfl.gov.uk/)

Google Places API (New): https://developers.google.com/maps/documentation/places/web-service/overview (you'll get a key from https://console.cloud.google.com/)

DESNZ GHG conversion factors 2026: https://www.gov.uk/government/publications/greenhouse-gas-reporting-conversion-factors-2026 (download the condensed spreadsheet and use the "Business travel – land" tab)


# kg CO2e per [passenger.km](http://passenger.km), DESNZ GHG conversion factors 2026 (v1.2), Business travel- land/sea

EMISSION_FACTORS = {

    "tube":            0.01549,  # Rail → London Underground

    "dlr":             0.02121,  # Rail → Light rail and tram

    "tram":            0.02121,  # Rail → Light rail and tram

    "overground":      0.03092,  # Rail → National rail

    "elizabeth-line":  0.03092,  # Rail → National rail (no separate factor)

    "national-rail":   0.03092,  # Rail → National rail

    "bus":             0.06360,  # Bus → Local London bus

    "replacement-bus": 0.06360,  # Bus → Local London bus

    "coach":           0.03948,  # Bus → Coach

    "river-bus":       0.01871,  # Ferry → Foot passenger (closest match)

    "walking":         0.0,

    "cycle":           0.0,

}
# Country-Code



```

public enum CountryCode {
    // Other country codes omitted for brevity
    US("+1", "United States of America");

    private final String code;
    private final String name;

    CountryCode(String code, String name) {
        this.code = code;
        this.name = name;
    }

    public String getCode() {
        return code;
    }

    public String getName() {
        return name;
    }
}


```

### In this example, the +1 country code is associated with the name "United States of America". You can access the country code and name for the US like this:


```

String countryCode = CountryCode.US.getCode();   // Returns "+1"
String countryName = CountryCode.US.getName();   // Returns "United States of America"

```

### Country code List:

```

public enum CountryCode {
    AF("Afghanistan"),
    AX("Åland Islands"),
    AL("Albania"),
    DZ("Algeria"),
    AS("American Samoa"),
    AD("Andorra"),
    AO("Angola"),
    AI("Anguilla"),
    AQ("Antarctica"),
    AG("Antigua and Barbuda"),
    AR("Argentina"),
    AM("Armenia"),
    AW("Aruba"),
    AU("Australia"),
    AT("Austria"),
    AZ("Azerbaijan"),
    BS("Bahamas"),
    BH("Bahrain"),
    BD("Bangladesh"),
    BB("Barbados"),
    BY("Belarus"),
    BE("Belgium"),
    BZ("Belize"),
    BJ("Benin"),
    BM("Bermuda"),
    BT("Bhutan"),
    BO("Bolivia (Plurinational State of)"),
    BQ("Bonaire, Sint Eustatius and Saba"),
    BA("Bosnia and Herzegovina"),
    BW("Botswana"),
    BV("Bouvet Island"),
    BR("Brazil"),
    IO("British Indian Ocean Territory"),
    BN("Brunei Darussalam"),
    BG("Bulgaria"),
    BF("Burkina Faso"),
    BI("Burundi"),
    KH("Cambodia"),
    CM("Cameroon"),
    CA("Canada"),
    CV("Cabo Verde"),
    KY("Cayman Islands"),
    CF("Central African Republic"),
    TD("Chad"),
    CL("Chile"),
    CN("China"),
    CX("Christmas Island"),
    CC("Cocos (Keeling) Islands"),
    CO("Colombia"),
    KM("Comoros"),
    CG("Congo"),
    CD("Congo (Democratic Republic of the)"),
    CK("Cook Islands"),
    CR("Costa Rica"),
    CI("Côte d'Ivoire"),
    HR("Croatia"),
    CU("Cuba"),
    CW("Curaçao"),
    CY("Cyprus"),
    CZ("Czechia"),
    DK("Denmark"),
    DJ("Djibouti"),
    DM("Dominica"),
    DO("Dominican Republic"),
    EC("Ecuador"),
    EG("Egypt"),
    SV("El Salvador"),
    GQ("Equatorial Guinea"),
    ER("Eritrea"),
    EE("Estonia"),
    ET("Ethiopia"),
    FK("Falkland Islands (Malvinas)"),
    FO("Faroe Islands"),
    FJ("Fiji"),
    FI("Finland"),
    FR("France"),
    GF("French Guiana"),
    PF("French Polynesia"),
    TF("French Southern Territories"),
    GA("Gabon"),
    GM("Gambia"),
    GE("Georgia"),
    DE("Germany"),
    GH("Ghana"),
    GI("Gibraltar"),
    GR("Greece"),
    GL("Greenland"),
    GD("Grenada"),
    GP("Guadeloupe"),
    GU("Guam"),
    GT("Guatemala"),
    GG("Guernsey"),
    GN("Guinea"),
    GW("Guinea-Bissau"),
    GY("Guyana"),
    HT("Haiti"),
    HM("Heard Island and McDonald Islands"),
    VA("Holy See"),
    HN("Honduras"),
    HK("Hong Kong"),
    HU("Hungary"),
    IS("Iceland"),
    IN("India"),
    ID("Indonesia

```



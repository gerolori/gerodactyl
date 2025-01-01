# gerodactyl
gerolori's dactyl manuform generated with Cosmos flashed with qmk on cheap rp2040's from aliexpress

## Design:

### [v1.1](https://ryanis.cool/cosmos/beta#cm:CpIBCg0SBRCQQSATEgASADgxCg0SBRCQTSATEgASADgdChoSBRCQWSATEgASAxCwLxICEDA4CUCA6IqYAgoYEgUQkGUgExIAEgMQsDsSAhAwOApAgOAdChMSBRCQcSATEgASADgeQICah4ADChgSBBAQIBMSBBCggAoSAhAwODJAgIaKwAcYAEDohaCu8FVI3PCioAEKlAEKFxITEMCAAkCAgJgCSMKZoJWQvAFQQzgIChgSFBDAgAJAgIDMAkjCmaCVkLwBUIYBUDoKFRIQEEBAgIAgSNCVgN2Q9QNQC1CeAgoUEhAQQECAgPgBSOaZ/KeQC1BXUH8KFRIQEEBAgICkA0jwmcS10DBQdFCVARgCIgoIyAEQyAEYACAAQMuL/J/QMUitkdyNwZMGCo0BCg0SBRCQNSATEgASADgyCg0SBRCQKSATEgASADgeChcSBRCQHSATEgASABICEDA4CkCA8Ir4AQoWEgUQkBEgExIAEgASAhAwOAlAgJCGOAoTEgUQkAUgExIAEgA4HUCAtoeQAwoYEgQQECATEgQQoIAKEgIQMDgxQICGisAHGAFA54WgrvBVSNzuopgBEAI4AoIBBASCAQBQB1hHaAByB5ABuQIQuQJ4yIO07bDcAQ==)
Fixed the microcontroller that was too far back and couldn't connect the usb and trrs.

### [v1.0](https://ryanis.cool/cosmos/beta#cm:CpYBCg8SBRCQQSATEgASADgxQAAKDxIFEJBNIBMSABIAOB1AAAoaEgUQkFkgExIAEgMQsC8SAhAwOAlAgOiKmAIKGBIFEJBlIBMSABIDELA7EgIQMDgKQIDgHQoTEgUQkHEgExIAEgA4HkCAmoeAAwoYEgQQECATEgQQoIAKEgIQMDgyQICGisAHGABA6IWgrvBVSNzwoqABCo8BCisSExDAgAJAgICYAkjCmaCVkLwBUEMSEkCAgMwCSMKZoJWQvAFQhgFYOjgIChUSEBBAQICAIEjQlYDdkPUDUAtQngIKJxIQEEBAgID4AUjmmfynkAtQVxIRQICApANI8JnEtdAwUHRYlQFQfwoDUIICGAIiCgjIARDIARgAIABAy4v8n9AxSK2R3I3BkwYKkQEKDxIFEJA1IBMSABIAODJAAAoPEgUQkCkgExIAEgA4HkAAChcSBRCQHSATEgASABICEDA4CkCA8Ir4AQoWEgUQkBEgExIAEgASAhAwOAlAgJCGOAoTEgUQkAUgExIAEgA4HUCAtoeQAwoYEgQQECATEgQQoIAKEgIQMDgxQICGisAHGAFA54WgrvBVSNzuopgBEAIYgaAEOAKCAQIEAlAHWEdoAHjIg7TtsNwB)



## Firmware
It will be the latest qmk, based on one of the existing handwired/dactyl presets that are on the repo.
[This](https://config.qmk.fm/#/handwired/dactyl_manuform/4x6_5/LAYOUT) looks like it's 90% there, I just need to adjust all the other layers

## Key Layout
I'll aim for something like [this](https://github.com/precondition/dactyl-manuform-keymap). The keymap should be optimized for the home row use, that's why I went without a number row.
I've added an external raw so i can use esc-tab-shift like I'm used to in my normal keyboard, I don't want them to be on secondary layers. I'm not sure what I'll put on the right side but probably some function keys or something else.
The right three keys could also be tab caps and shift, using caps as a hold to use his function but when tapping it goes in some kind of layer, maybe a more obscure one

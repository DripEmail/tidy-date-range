# Tidy Date Range

A simple jQuery date range plugin.

## Usage

```
    var $myDatePicker = $('#date-picker').tidydaterange({
        from: '8/8/2018, 
        to: '10/10/2018',
        maxDays: 31,
        minDate: '5/5/2018',
        presetsHTML: "<div class='tdr-range-presets'/>",
        presetsCode: function () {
            console.log('In PresetsCode');
        }
    })
```

## Options

* `from`: String Initial from date in a form that can be converted to a Date
* `to`: String Initial to date in a form that can be converted to a Date
* `maxDays`: Int Maximum number of days for a selection (optional)
* `minDate`: Disables days before this date (optional)
* `presetsHTML`: String HTML code to be inserted before input boxes (optional)
* `presetsCode`: Function Code to be run on Control setup (optional)

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

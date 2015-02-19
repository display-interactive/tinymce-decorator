pikaday-decorator
=================

Pikaday with Polymer


##Basic use:

```HTML
<pikaday-decorator>
    <input type="text" name="date1" />
</pikaday-decorator>
```

The polymer element will search and input to instanciate pikaday

##use with trigger button
```HTML
<pikaday-decorator>
    <input type="text" name="date2" />
    <button type="button" pikaday-decorator-trigger>pick</button>
</pikaday-decorator>
```

it will use [pikaday-decorator-trigger] to set the 'trigger' param of pikaday 

##options (option are not tested)
 
For options see https://github.com/dbushell/Pikaday#user-content-configuration

```CODE
 locale: 'en', //see 'i18n'. default language if you set 'fr' it will load the french translation
 format: 'YYYY-MM-DD',
 position: 'bottom left', 
 reposition: true,
 container: undefined,
 'default-date': undefined, //see 'defaultDate' 
 'set-default-date': false, //see to 'setDefaultDate'
 'first-day': 0, //see 'firstDay'
 'min-date': false, //see 'minDate'
 'max-date': false, //see 'maxDate'
 'year-range': false, //see 'yearRange'
 'show-week-number': false, //see 'showWeekNumber'
 rtl: false, //see 'isRTL'
 'year-suffix': '', //see 'yearSuffix'
 'show-month-after-year': false, //see 'showMonthAfterYear'
 'number-of-months': 1, //see 'numberOfMonths'
 'main-calendar': 'left', //see 'mainCalendar'
 'on-select': null, //see 'onSelect'
 'on-open': null, //see 'onOpen'
 'on-close': null, //see 'onClose'
 'on-draw': null,//see 'onDraw'
 ``
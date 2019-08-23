# datepicker-enabling-between-min-and-max-dates
url:https://mdbootstrap.com/docs/jquery/forms/date-picker/(for reference)

<div class="md-form">
  <input placeholder="Selected date" type="text" id="date-picker-example" class="form-control datepicker">
  <label for="date-picker-example">Try me...</label>
</div>


$('.datepicker').pickadate({
selectYears: 5,
selectMonths: true,
  firstDay: 1,
  min: new Date(2019,08,5),
 max: new Date(2019,08,14),
disable: [
[2015,3,3],
[2015,3,12],
[2015,3,20]
]
})

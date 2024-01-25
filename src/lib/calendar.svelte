<script>
	import Calendar from '@event-calendar/core';
	import TimeGrid from '@event-calendar/time-grid';

	let plugins = [TimeGrid];
	let options = {
		height: '100%',
		view: 'timeGridWeek',
		allDayContent: 'Goals',
		events: [
			// your list of events
		]
	};
</script>

<Calendar {plugins} {options} />

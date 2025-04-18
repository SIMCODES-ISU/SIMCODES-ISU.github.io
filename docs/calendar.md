---
layout: default
title: Calendar
permalink: /calendar/
---

<h1>Program Calendar</h1>

<div id="calendar"></div>

<!-- FullCalendar Stylesheet and Script -->
<link href='https://cdn.jsdelivr.net/npm/fullcalendar@6.1.8/index.global.min.css' rel='stylesheet' />
<script src='https://cdn.jsdelivr.net/npm/fullcalendar@6.1.8/index.global.min.js'></script>

<script>
  document.addEventListener('DOMContentLoaded', function () {
    var calendarEl = document.getElementById('calendar');
    var calendar = new FullCalendar.Calendar(calendarEl, {
      initialView: 'dayGridMonth',
      height: 'auto',
      events: [
        {
          title: 'SIMCODES Starts',
          start: '2025-05-26'
        },
        {
          title: 'Mid-Term Presentations',
          start: '2025-07-10'
        },
        {
          title: 'Final Symposium',
          start: '2025-08-01'
        }
      ]
    });
    calendar.render();
  });
</script>

<style>
  #calendar {
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem;
    background: white;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
  }
</style>

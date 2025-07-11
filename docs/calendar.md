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
          start: '2025-07-11'
        },
        {
          title: 'Final Symposium',
          start: '2025-07-31'
        },
        {
        title: 'Songwriter Showcase: Wolfskill and The Wild',
        start: '2025-07-15T18:00:00',
        end: '2025-07-15T20:00:00',
        description: 'Catalpa Courtyard, Reiman Gardens\n$15-$20\n\nWolfskill and The Wild take the stage for the third of five performances in the Goldfinch Room Songwriter Showcase series at Reiman Gardens. A local food truck will be on site and beverages will be available for purchase. Outside food and nonalcoholic beverages are allowed. Audience members are encouraged to bring lawn chairs or blankets for seating on the lawn. Inclement weather could move the performance to the Garden Room.'
       },
       {
        title: 'Welcome Picnic at Brookside Park',
        start: '2025-06-14T12:30:00',
        end: '2025-06-14T16:00:00',
        description: 'Sandwiches and sides will be provided from Jimmy John, Opportunity for students across all the REUs and summer programs to socialize'
       },
        {
        title: 'Songwriter Showcase: David G. Smith and Carol Montag',
        start: '2025-06-24T18:00:00',
        end: '2025-06-24T20:00:00',
        description: 'Catalpa Courtyard, Reiman Gardens\n$15-$20\n\nDavid G. Smith and Carol Montag take the stage for the second of five performances in the Goldfinch Room Songwriter Showcase series at Reiman Gardens. A local food truck will be on site and beverages will be available for purchase. Outside food and nonalcoholic beverages are allowed. Audience members are encouraged to bring lawn chairs or blankets for seating on the lawn. Inclement weather could move the performance to the Garden Room.'
      },
      {
        title: 'Songwriter Showcase: The Bird Hunters',
        start: '2025-05-27T18:00:00',
        end: '2025-05-27T20:00:00',
        description: 'Catalpa Courtyard, Reiman Gardens\n$15-$20\n\nThe Bird Hunters open as the first of five performances in the Goldfinch Room Songwriter Showcase series at Reiman Gardens. A local food truck will be on site and beverages will be available for purchase. Outside food and nonalcoholic beverages are allowed. Audience members are encouraged to bring lawn chairs or blankets for seating on the lawn. Inclement weather could move the performance to the Garden Room.'
      },
      {
        title: 'Frankie Valli and The Four Seasons – The Last Encores Tour',
        start: '2025-06-29T19:30:00',
        description: 'Stephens Auditorium\n$45 and up\n\n"The Last Encores Tour," featuring 2025 Lifetime Achievement Grammy Winner Frankie Valli and the Four Seasons. This tour promises to be a fantastic celebration of Valli\'s legendary career, showcasing his timeless music and incredible showmanship.'
      },
        {
        title: 'Weekly Professional Development Sessions',
        start: '2025-06-11T12:00:00',
        end: '2025-06-11T13:00:00',
        description: '0114 SICTR, led by Erin Todey: CV and resume workshop'
      }, {
        title: 'Weekly Professional Development Sessions',
        start: '2025-06-18T12:00:00',
        end: '2025-06-18T13:00:00',
        description: '3204 SICTR, led by Erin Todey: Personal statements and statements of purpose workshop'
      },{
        title: 'Weekly Professional Development Sessions',
        start: '2025-06-25T12:00:00',
        end: '2025-06-25T13:00:00',
        description: '2221 SICTR, led by Kelli Fitzpatrick: Communicating research to the public'
      },{
        title: 'Weekly Professional Development Sessions',
        start: '2025-07-02T12:00:00',
        end: '2025-07-02T13:00:00',
        description: ' 0114 SICTR, led by Erin Todey: Research poster workshop part 1'
      },{
        title: 'Weekly Professional Development Sessions',
        start: '2025-07-09T12:00:00',
        end: '2025-07-09T13:00:00',
        description: ' 0114 SICTR, led by Erin Todey: Abstracts workshop'
      },
      {
        title: 'Weekly Professional Development Sessions',
        start: '2025-07-16T12:00:00',
        end: '2025-07-16T13:00:00',
        description: ' 2221 SICTR, led by Kelli Fitzpatrick: Public speaking skills for conference presentations'
      }, {
        title: 'Weekly Professional Development Sessions',
        start: '2025-07-23T12:00:00',
        end: '2025-07-23T13:00:00',
        description: ' 2221 SICTR, led by Erin Todey: Research poster workshop part 2'
      },
      {
        title: 'Poster Session',
        start: '2025-07-31T14:00:00',
        end: '2025-07-31T16:00:00',
        description: 'Student Innovation Center atrium'
      }
      ],
      eventClick: function(info) {
        if (info.event.extendedProps.description) {
          alert(info.event.title + '\n\n' + info.event.extendedProps.description);
        }
      }
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

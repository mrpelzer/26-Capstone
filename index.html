window.location.hash = "homepage";

const fullTitle = "The Gazette !!";
        let index = 0;
        function typeTitle() {
            if (index <= fullTitle.length) {
                document.title = fullTitle.substring(0, index);
                index++;
            } else {
                index = 0;
            }
        }
        setInterval(typeTitle, 200);

function showPage(page){

let sections = document.querySelectorAll(".section");

sections.forEach(section=>{
section.classList.remove("active");
});

document.getElementById(page).classList.add("active");

}


const highlight = document.querySelector(".nav-highlight");
const navLinks = document.querySelectorAll(".nav-left a");
const nav = document.querySelector(".navbar");

let activeLink = document.querySelector(".nav-left a.active");

/* move highlight */

function moveHighlight(link){

const rect = link.getBoundingClientRect();
const navRect = nav.getBoundingClientRect();

highlight.style.width = rect.width + "px";
highlight.style.left = (rect.left - navRect.left) + "px";
highlight.style.top = "20px";

}

/* hover */

navLinks.forEach(link => {

link.addEventListener("mouseenter", () => {
moveHighlight(link);
});

link.addEventListener("click", () => {

navLinks.forEach(l => l.classList.remove("active"));

link.classList.add("active");
activeLink = link;

moveHighlight(link);

});

});

/* leave navbar */

document.querySelector(".nav-left").addEventListener("mouseleave", () => {

if(activeLink){
moveHighlight(activeLink);
}

});

/* initialize highlight */

window.addEventListener("load", () => {

if(activeLink){
moveHighlight(activeLink);
}

});

$( function() {
    $( ".outer" ).draggable();
    } );
    
    function closead() {
    const ad = document.querySelector(".ads");
    ad.style.display = "none";
}
/* calendar */
const datesContainer = document.getElementById("dates");
const eventList = document.getElementById("event-list");
const selectedDateText = document.getElementById("selected-date");
const monthLabel = document.getElementById("month-label");
const activeDot = document.getElementById("active-dot");

let currentYear = 2026;
let currentMonth = 3; // April (0 = Jan)
let selectedDate = 1;

const monthNames = [
  "Jan","Feb","Mar","Apr","May","Jun",
  "Jul","Aug","Sep","Oct","Nov","Dec"
];

/* update left panel */
function updateLeftPanel(day) {
  selectedDate = day;
  selectedDateText.innerText = day;
}

/* move active dot */
function moveDot(el) {
  const parent = document.querySelector(".calendar-base").getBoundingClientRect();
  const rect = el.getBoundingClientRect();

  activeDot.style.transform =
    `translate(${rect.left - parent.left}px, ${rect.top - parent.top}px)`;
}

/* build calendar grid */
function generateCalendar() {
  datesContainer.innerHTML = "";

  const firstDay = new Date(currentYear, currentMonth, 1).getDay();
  const daysInMonth = new Date(currentYear, currentMonth + 1, 0).getDate();

  monthLabel.innerText = monthNames[currentMonth] + " " + currentYear;

  /* blank spaces before first day */
  for (let i = 0; i < firstDay; i++) {
    datesContainer.appendChild(document.createElement("div"));
  }

  /* actual days */
  for (let i = 1; i <= daysInMonth; i++) {
    let day = document.createElement("div");
    day.classList.add("date");
    day.innerText = i;

    day.onclick = () => selectDate(i, day);

    datesContainer.appendChild(day);
  }
}

/* select a date */
function selectDate(day, el) {
  document.querySelectorAll(".date")
    .forEach(d => d.classList.remove("selected"));

  el.classList.add("selected");
  updateLeftPanel(day);
  moveDot(el);
}

/* change month */
function changeMonth(step) {
  currentMonth += step;

  if (currentMonth > 11) {
    currentMonth = 0;
    currentYear++;
  }

  if (currentMonth < 0) {
    currentMonth = 11;
    currentYear--;
  }

  generateCalendar();
}

/* init calendar on load */
window.addEventListener("load", () => {
  generateCalendar();

  const firstDate = document.querySelector(".date");
  if (firstDate) {
    selectDate(1, firstDate);
  }
});

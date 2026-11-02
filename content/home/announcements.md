+++
widget = "blank"
headless = true
active = true
weight = 12

title = ""
subtitle = ""

[design]
  columns = "2"

[design.spacing]
  padding = ["10px", "0", "60px", "0"]
+++

<style>
@media (min-width: 992px) {
  #announcements > .container {
    margin-bottom: -100px;
    transform: translateY(-100px);
  }
}

.hiring-notice {
  background: #d4e9e3;
  border-left: 4px solid #c02739;
  padding: 1.5rem 1.75rem;
}

.hiring-notice p {
  margin: 0;
}

.hiring-notice .hiring-title {
  color: #202020;
  font-family: "Arial Black", "Nunito", sans-serif;
  font-weight: 900 !important;
}

@media (max-width: 575px) {
  .hiring-notice {
    padding: 1.25rem;
  }
}
</style>

<div class="hiring-notice">
  <p><strong class="hiring-title">NOW HIRING:</strong> I am looking for a postdoctoral researcher to join the Milan NLP group. <strong>Application deadline: November 15, 2026.</strong> More information: <a href="https://milanlproc.github.io/join/">https://milanlproc.github.io/join/</a>.</p>
</div>

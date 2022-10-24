<script>
    import reports from "../../images/user-reports-dashboard.png";
    import iPie from "../../images/reports-interactive-pie.png";
    import last90 from "../../images/user-reports-last-90.png";
    import totalByDept from "../../images/user-reports-totals-by-dept.png";
  </script>
  
  <div class='main'>
    <h1>Using the Reports Dashboard</h1>
    <hr>
    <div class="list-with-image">
      <h3>Reports</h3>
      <div>
        <p>
          Using the <b>"Reports"</b> selector in the Navigation Bar will take you to
          your Reports Dashboard
        </p>
      </div>
      <img src={reports} alt="reports dashboard" width="90%" />
    </div>
    <hr>
    <h4>Getting around the Reports Dashboard</h4>
    <p>
      On first load you are greeting with statistics represented in graphs on the
      main page and an easy to use navigation menu on the left hand side
    </p>
    <div class="list-with-image">
      <ul>
        <h5>These statistics are:</h5>
        <li>Specific to all the Departments you are associated with.</li>
        <li>
          Designed to allow you a quick view of your data so they are interactive
          on some level.
          <ul>
            <li>
              Hover over a section of the pic chart too see additional details.
            </li>
          </ul>
        </li>
        <li>
          Most of the graphs have a corrosponding full screen version of the
          reports as well.
        </li>
      </ul>
      <img src={iPie} alt="cool pie chart" />
    </div>
    <div class="list-with-image">
      <img src={last90} alt="last 90 days report" width="90%" /><img
        src={totalByDept}
        alt="total by Department"
        width="90%"
      />
    </div>
  
</div>
  <style>
    p {
      text-align: left;
    }
    ul {
      text-align: left;
    }
    .list-with-image {
      display: grid;
      grid-template-columns: 1fr 1fr;
    }
    img{
        margin: 20px;
    }
    .main{
        margin: 30px;
        max-width: 1080px;
    }
    
  </style>
  